📈 Financial Market Sentiment Analysis using Machine Learning

🚀 A Machine Learning project that uses NLP techniques to predict stock market movement (Up/Down) based on daily financial news headlines.

📌 Dataset

The dataset used for this project is available on Kaggle:

🔗 https://www.kaggle.com/datasets/sushantbmujagule/financial-market-news-sentiment-analysis-dataset

The dataset contains top 25 daily financial news headlines along with market movement labels.

📌 Overview

The model analyzes the top 25 daily news headlines and predicts:

1 → Market Up

0 → Market Down

🧠 Workflow

✔ Combined 25 headlines into one single text column
✔ Text preprocessing:

Convert text to lowercase

Remove special characters

Remove stopwords using NLTK

✔ Applied TF-IDF Vectorizer (5000 features)
✔ Used Logistic Regression classifier
✔ Train-Test Split: 80% / 20%

📊 Results

Accuracy: ~49%

Evaluation Metrics Used:

Accuracy

Precision

Recall

F1-Score

⚠ Market prediction is highly challenging due to volatility, macroeconomic events, and multiple external influencing factors.

📈 Stock Visualization

✔ Stock data downloaded using yFinance
✔ Example Stock: Tesla (TSLA)
✔ Closing prices visualized using Matplotlib

🛠 Technologies Used

Python
Pandas
NumPy
NLTK
Scikit-learn
Matplotlib
yFinance