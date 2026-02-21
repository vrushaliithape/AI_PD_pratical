# Practical 3: Sentiment Analysis using TensorFlow

## Aim
To develop a Sentiment Analysis model that analyzes customer reviews of products or services and classifies them as Positive or Negative using a Deep Learning approach.

---

## Introduction
Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine whether a piece of text expresses positive, negative, or neutral sentiment.

In this project, we build a Deep Learning model using TensorFlow to analyze customer reviews and automatically classify their sentiment. This helps businesses understand customer feedback and improve their products or services.

---

## Application
This AI prototype can be used in:

- E-commerce platforms (Amazon, Flipkart)
- Service feedback systems
- Product review analysis
- Social media monitoring
- Customer satisfaction analysis

---

## Tools and Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- NLP techniques (Tokenization, Padding)

---

## Dataset Description
The dataset contains customer reviews and corresponding sentiment labels.

- Input: twitter training dataset 
- Output: Sentiment (Positive / Negative)
- Type of problem: Binary Classification
- Dataset split: 80% Training, 20% Testing

Before training, the text data is preprocessed using:
- Tokenization
- Sequence padding
- Conversion of text to numerical format

---

## Model Architecture
The model is built using TensorFlow Sequential API and includes:

- Embedding Layer
- LSTM / Dense Layer
- Output Layer (Sigmoid activation)

Loss Function: Binary Crossentropy  
Optimizer: Adam  
Evaluation Metrics: Accuracy, Precision, Recall  

---

## Model Training
The model is trained using:

- Epochs: 10–20
- Batch Size: 32
- Validation Split: 0.2

The model learns patterns from customer review text to classify sentiment correctly.

---

## Model Evaluation
The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- Confusion Matrix (optional)

These metrics measure how well the model predicts customer sentiment.

---

## Results
The model successfully classifies twitter training  reviews into positive and negative categories.


The results indicate that the model performs effectively in sentiment prediction.

---

## Conclusion
In this practical, we successfully developed a Sentiment Analysis model using TensorFlow. The model was trained on customer review data and evaluated using standard performance metrics.

This project demonstrates how AI can be used to automatically analyze customer feedback and assist businesses in decision-making.

---

## Learning Outcomes
- Understanding Natural Language Processing (NLP)
- Implementing Text Preprocessing techniques
- Building Deep Learning models using TensorFlow
- Evaluating classification models
- Applying AI to real-world business problems