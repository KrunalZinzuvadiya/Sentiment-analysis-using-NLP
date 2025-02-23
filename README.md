# Sentiment Analysis of Tweets to Predict Depression

## Overview
This project applies Natural Language Processing (NLP) and Machine Learning techniques to analyze Twitter data and predict potential signs of depression in users. It classifies tweets as either "depressed" or "non-depressed" using various machine learning models.

## Features
- **Data Collection:**  
  - A dataset of 20,000 labeled English tweets was collected via the Twitter API.  
  - Labels indicate whether the users who posted them are depressed or non-depressed.  

- **Data Preprocessing:**  
  - Tokenization, stop word removal, punctuation removal.  
  - Text normalization using lemmatization.  
  - Converting text into numerical feature representations using Bag-of-Words (BoW) and TF-IDF.  

- **Machine Learning Models Used:**  
  - Decision Tree  
  - Random Forest Classifier  
  - K-Nearest Neighbors (KNN)  
  - Naïve Bayes  

- **Sentiment Analysis:**  
  - TextBlob was used to compute sentiment scores (-1 to +1).  
  - Tweets were classified based on sentiment polarity.  

## Dataset
The dataset consists of English tweets labeled as:
- **Depressed (1)** – Indicating potential signs of depression.  
- **Non-depressed (0)** – No signs of depression detected.  

## Dependencies
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn nltk textblob scikit-learn
