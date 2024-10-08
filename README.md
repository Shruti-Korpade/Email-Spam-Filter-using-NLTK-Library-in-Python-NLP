﻿# Email-Spam-Filter-using-NLTK-Library-in-Python-NLP

This project presents an efficient Email Spam Filter that uses Multinomial Naive Bayes, Term Frequency-Inverse Document Frequency (TF-IDF), a curated email corpus, the Natural Language Toolkit (NLTK), and a Streamlit app for user-friendly interaction.
The Multinomial Naive Bayes classifier is used to classify incoming messages based on word occurrence probabilities in spam and non-spam emails. 
TF-IDF transforms the text into numerical features, enhancing its ability to distinguish between spam and legitimate content. 
A curated email corpus is used to train and test the model, ensuring its accuracy and robustness. 
The NLTK library is used for natural language processing tasks like tokenization, stemming, and stop-word removal, enhancing the input data quality. 
A user-friendly Streamlit app is developed to make the spam filter accessible and user-friendly, allowing users to input and classify their emails as spam or not spam. 
This robust solution effectively filters out unwanted emails

# DAA_CP.ipynb File

This code is a Python script for performing a variety of tasks related to text classification, including data cleaning, exploratory data analysis, data preprocessing, model building, and model evaluation. 
It appears to be working with a dataset of text messages (likely SMS messages) and aims to classify them as either "ham" or "spam." 
This code is a comprehensive example of text classification, covering data preprocessing, feature engineering, model selection, and evaluation. 
It explores multiple classifiers and ensemble techniques to improve performance.

# App.py File

This code is a Python script that uses the Streamlit framework to create a simple web application for classifying email messages as either spam or not spam. 
The code loads a pre-trained text classification model and a TF-IDF vectorizer, allowing users to input a message and get a spam classification prediction.
This code creates a user-friendly web application using Streamlit, which takes an email message as input, processes it, and predicts whether it's spam or not. 
The prediction is made using a pre-trained model and vectorizer that have been pickled and loaded into the application. 
This type of application can be useful for end-users who want to quickly classify their email messages.
