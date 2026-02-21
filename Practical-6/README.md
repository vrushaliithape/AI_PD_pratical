# Practical 6: SMS Spam Detection using Machine Learning

## Aim
To develop a machine learning model that classifies SMS messages as Spam or Ham (Not Spam) using Natural Language Processing (NLP) techniques and evaluate its performance using standard metrics.

---

## Introduction
Spam detection is a common real-world application of Machine Learning and Natural Language Processing (NLP). It helps automatically filter unwanted messages and protect users from fraud or promotional spam.

In this project, we built an SMS Spam Detection model using the Multinomial Naive Bayes algorithm and TF-IDF vectorization technique.

---

## Dataset Description
The dataset used is **spam.csv**, which contains SMS messages labeled as:

- ham → Not Spam (0)
- spam → Spam (1)

### Dataset Information:
- Total Messages: 5572
- Ham Messages: 4825
- Spam Messages: 747
- Features: Message Text
- Target Variable: Label (Spam / Ham)

The dataset was cleaned by removing unnecessary columns and converting labels into numeric format.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

## Data Preprocessing
The following preprocessing steps were applied:

1. Removed unnecessary columns
2. Renamed columns to `label` and `message`
3. Converted labels:
   - ham → 0
   - spam → 1
4. Split dataset into:
   - 80% Training Data
   - 20% Testing Data
5. Applied TF-IDF Vectorization (max_features = 3000)

---

## Model Used
### Multinomial Naive Bayes

Naive Bayes is a probabilistic machine learning algorithm commonly used for text classification problems.

It works well with:
- Text data
- Word frequency features
- High-dimensional datasets

---

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Performance Metrics:

- Accuracy: 97.84%
- Precision: 1.00
- Recall: 0.84
- F1-Score: 0.91

The model performs very well in detecting spam messages with high precision.

---

## Sample Prediction

Example:

Message: "Congratulations! You have won $5000 cash!"
Prediction: Spam

Message: "Hey, are we meeting tomorrow?"
Prediction: Ham

---

## Results
The model achieved high accuracy and precision, showing that Multinomial Naive Bayes combined with TF-IDF is effective for spam detection tasks.

---

## Conclusion
In this practical, we successfully implemented an SMS Spam Detection system using Machine Learning techniques. The model can accurately classify SMS messages as spam or ham.

This project demonstrates the application of NLP and text classification in real-world problems.

---

## Learning Outcomes
- Understanding Text Preprocessing
- Applying TF-IDF Vectorization
- Implementing Naive Bayes Algorithm
- Evaluating Classification Models
- Building Real-world NLP Applications