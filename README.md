# Fake-News-Detection Using LSTM

#Project Overview

This project detects whether a news article is Real or Fake using Machine Learning.
It uses a Deep Learning model (LSTM) to analyze the text and predict the result.
The main goal of this project is to reduce the spread of fake news by automatically classifying news articles.

#Problem Statement
Nowadays, fake news spreads very quickly on social media and websites.
It is difficult for people to identify whether the news is true or false.

This project builds a model that:
Takes news text as input
Analyzes the content
Predicts whether it is Real News or Fake News

#Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
TensorFlow / Keras
LSTM (Long Short-Term Memory)

#Dataset
The dataset contains:
News title
News text
Label (Real or Fake)
The model is trained using this labeled dataset.

#Project Workflow (Step-by-Step)
1️. Data Collection
Load dataset (CSV file)
Combine title and text if needed

2️. Data Preprocessing
Remove special characters
Convert text to lowercase
Remove stopwords
Tokenization
Padding sequences

3️. Model Building
Use LSTM model
Add Embedding layer
Add Dense layer with activation function

4️. Model Training
Split dataset into training and testing
Train the model
Check accuracy

5️. Model Evaluation
Calculate accuracy score
Confusion matrix
Loss and accuracy graphs

#Model Performance
Achieved good accuracy on test data.
Successfully classifies real and fake news articles.

