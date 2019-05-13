# Classifying-Rx-Medication
Utilizing deep neural networks to classify prescription medicine.  

I wanted to test multiple different NN models. Originally, I had tried to create an CNN architecture by looping through a range of nodes, hidden layers, and dropouts. I wasn't able to get consistent results with any of the architectures through this method. Eventually I settled on using ResNet34's architecture trained on ImageNet images for transfer learning on my prescription images.  

**ImageProcessingAugmentation.ipynb:** In this notebook I use OpenCV to normalize and transform my limited number of images and output a numpy array of the images.  
**RxClassification:** In this notebook, I use FastAi to train ResNet34 on 5 classes of medications (~400 images). I found an ideal leaning rate using the built-in lr-finder to train the model. Unfreezing the layers allowed me to re-train the original ResNet weights. Depending on how many classes I used, I ended up with 95.8% accuracy (5 classes) and 98.4% accuracy (10 classes).  
**SiameseNetDrugs.ipynb** I attempted an one-shot learning solution by employing Siamese Neural Networks. Images were paired up into positive pairs and negative pairs. The images of each pair were run through a parrallel CNN and then the distance between the 2 outputs was fed into a dense layer. I acheived 93.43% accuracy.
