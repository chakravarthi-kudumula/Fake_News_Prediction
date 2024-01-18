<h5>Fake News Prediction</h5>

<h3>Overview</h3>

This project aims to predict the reliability of news articles using machine learning techniques. The dataset consists of labeled news articles, categorized as reliable (0) or potentially unreliable (1). The classification model is trained on the provided train dataset and evaluated.

<h2>Dataset</h2>

Dataset CSV file : https://www.kaggle.com/competitions/fake-news/data?select=train.csv#:~:text=calendar_view_week-,train,-.csv

<h2>Attributes in the dataset:</h2>

id: Unique identifier for a news article
title: Title of the news article
author: Author of the news article
text: Text of the article (could be incomplete)
label: Binary label indicating reliability (0: reliable, 1: unreliable)
Dataset Link: Link to Dataset

<h2>Python Libraries Used</h2>

numpy
pandas
re
nltk (Natural Language Toolkit)
sklearn (scikit-learn)

<h2>Important Steps</h2>

Importing Libraries: Importing necessary Python libraries for data manipulation, preprocessing, and machine learning.
Data Preprocessing: Cleaning and preparing the dataset for analysis.
Stemming: Reducing words to their root form for better analysis.
Splitting the Dataset: Dividing the dataset into training and testing sets.
Training the Model: Utilizing logistic regression for training the predictive model.
Evaluation: Assessing the model's performance and accuracy scores.
Making a Predictive System: Developing a system for predicting the reliability of news articles.
