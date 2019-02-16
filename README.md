# Data Science Portfolio - Joey Chao

This repository contains a collection of my data science projects. Each of the projects I worked on in the folders above feature data analysis skills from scraping and cleaning data to analyzing and modelling with the data. Feel free to read the overviews below and explore the folders above.

### [Classifying Rx Medication](https://github.com/jowaychao/Portfolio/tree/master/Classifying-Rx-Medication)

**Overview:** During my last job as a pharmacy technician at CVS pharmacy, I often encountered patients who came in with mixed up pills that they needed help with identifying. What if we could save patients the trip to the pharmacy by identifying images of pills through deep learning? This project uses images scraped from Google.com and [Pillbox](https://pillbox.nlm.nih.gov/) (National Institute of Health drug database) to train deep learning models capable of classifying drugs.

**Skills:** Web Scraping, Image Augmentation, Deep Learning                                                                               
**Toolkit:** Image Processing: cv2, PIL  **/**  Deep Learning: Keras, FastAi

### [Analysis of Property Listings](https://github.com/jowaychao/Portfolio/tree/master/Analysis-of-Property-Listings)

**Overview:** (In Progress) Investing in properties has long been perceived as a safe investment, but with prices for single family homes trending upwards for the 7th straight year, it can be difficult to find a worthwhile investment. This project analyzes the expected return on investment for properties in 5 metro areas. I scraped listing information such as property attributes, rental estimate, market value, tax information, appreciation.

**Skills:** Web Scraping, EDA, Visualizations                                                                                             
**Toolkit:** Scraping: BeautifulSoup, Selenium  **/**  Visualizations: Matplotlib, Seaborn

### [Classifying Tweets by Music Artists](https://github.com/jowaychao/Portfolio/tree/master/Classifying-Tweets-by-Music-Artists)

**Overview:** Twitter has become one of the most popular social media outlets for celebrities as it allows them to interact with their fans and make announcements. This project uses NLP techniques and machine learning models to match tweets with their authors. The data was obtained via the Twitter API and consists of roughly 3000 tweets per artist (the limit that Twitter API access allows). The tweets were processed and used to train supervised learning models and Word2Vec models.

**Skils:** Natural Language Processing, Machine Learning, Topic Clustering, Classification                                                 
**Toolkit:** Data Collection: Tweepy  **/**  NLP: Spacy, NLTK  **/**  Modelling: XGBoost, Scikit-Learn, Word2Vec
