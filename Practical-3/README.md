🐦 Twitter Sentiment Analysis
📌 Project Overview

This project builds a Sentiment Analysis Model to classify tweets as Positive, Negative, or Neutral using Natural Language Processing (NLP) techniques.

The model preprocesses text data using NLTK, applies stemming and stopword removal, and prepares cleaned text for machine learning classification.

📂 Dataset

Dataset Name: Twitter Entity Sentiment Analysis

Total Records: 74,682 tweets

Columns:

twitterid

identity

sentiment

tweet

🔗 Dataset Link:
https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

⚙️ Technologies Used

Python

Pandas

NumPy

NLTK

Scikit-learn

🧹 Data Preprocessing

Converted text to lowercase

Removed HTML tags

Removed special characters

Removed stopwords

Applied Porter Stemming

Tokenization & POS tagging

🚀 Model Workflow

Load Dataset

Clean & preprocess tweets

Convert text to numerical features (TF-IDF/CountVectorizer)

Train classification model

Evaluate using Accuracy, Precision, Recall

📊 Evaluation Metrics

Accuracy
Precision
Recall
Confusion Matrix