# Twitter Sentiment Analysis Model

This repository contains a machine learning model for sentiment analysis on Twitter data. The model is trained to classify the sentiment (positive, negative, neutral or irrelavant) of tweets.

## Overview

Sentiment analysis is a natural language processing (NLP) task that involves determining the sentiment expressed in a piece of text. This model specifically focuses on sentiment analysis of tweets from Twitter.

The sentiment analysis model is built using machine learning techniques and utilizes a logistic regression classifier and SVM classifier trained on a dataset of labeled tweets.

## Features

- Preprocessing: The tweets are preprocessed to remove noise, including special characters, stop words, and URLs. Additionally, tokenization and lemmatization are applied to convert the text into a format suitable for machine learning.
- Feature Extraction: The preprocessed text data is transformed into numerical features using the CountVectorizer technique.
- Model Training: The logistic regression classifier is trained on the preprocessed and transformed text data.
- Prediction: The trained model is capable of predicting the sentiment (positive, negative, neutral or irrelevant) of new tweets.


Thank you!!