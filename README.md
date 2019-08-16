# US-Airlines-Sentiment-Analysis

In this notebook, we will perform sentiment analysis on a dataset containing tweets on US airlines during 2015. We will first explore the dataset, do so some cleaning and feature selection, and then run a few machine learning algortihms to predict the sentiment of a particular tweet using NLP methods such as Term Frequency-Inverse Document Frequency (TF-IDF) which convert strings into numerical vectors for analysis. In the end, we will compare the performance of the algorthms to see which one performed the best.

Workflow:
Load the dataset into a dataframe
Explore the dataframe
Remove unnecessary columns
Remove all punctuation from the text column
Convert the text column into TF-IDF feature vectors
Use classification algorithms to predict the sentiment using K-Fold Cross validation with a grid search on a few relevant hyperparameters. The classification algortihms we will be using are Logistic Regression, Multinomial Naive Bayes, and Support Vector Machines
Compare the accuracies of the three classifiers
