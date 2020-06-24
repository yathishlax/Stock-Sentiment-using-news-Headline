Goal:
This project is basically focused on identifying the stock movement based on 
news headlines.
It is applied in following Bag of words model.vectorizing methods.

Source:
The source of this dataset is from Kaggle.com scrapped from yahoo finance

About the dataset:
Dataset contains top 25 headlines of stock names from 2000 to 2016 

Features:
Date: Date of News
Top1- 25: Top 25 headlines
label: a label that marks the increase in stock price
1: Increase
0: stable or decrease

Libraries Used:
pandas- it offers data structures and operations for manipulating numerical tables and time series.
Numpy – for numerical operations.
Stopwords – It is used to remove stop words from the sentences.
PorterStemmer – used for stemming, identifying the base stem word.
CountVectorizer – it is used to convert a collection of text documents to a matrix of token counts in Bag of words model.
TFIDFVectorizer – it is used to convert a collection of raw documents to a matrix of TF-IDF features. Where TF- IDF imputes weights to words based on TF*IDF.
Sklearn - For Machine Learning operations.
train_test_split – for splitting data into training and testing purpose.
matplotlib.pyplot – for visualizing the observations
metrics – to measure accuracy related factors such as confusion matrix, accuracy score etc.
RandomForestClassifier – it is a Boosting technique uses aggregation or voting to decide the best DT based on row sampling and random sampling.
MultinomialNB – Navyes bayes classifier for predicting text data.
PassiveAggressiveClassifier – Linear model classifier for predicting text data


Approach

•	Text Cleaning
•	Vectorizing using CountVectorizer/TF-IDF
•	Train test split
•	Apply Models
•	Hyperparameter tuning on best model
•	Calculating accuracy of both CountVectorizer/TF-IDF
