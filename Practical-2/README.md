# Practical 2: Implementation of Basic AI Prototype using TensorFlow

## Aim
To implement a basic Artificial Intelligence (AI) prototype using TensorFlow for a real-world application, train the model using a relevant dataset, and evaluate its performance using appropriate evaluation metrics.

---

## Introduction
Artificial Intelligence enables machines to learn patterns from data and make predictions. In this practical, we build a basic Neural Network model using TensorFlow to perform a classification task. The model is trained on a dataset and evaluated using performance metrics such as accuracy, precision, and recall.

---

## Tools and Technologies Used
- Python
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset Description
The dataset used in this experiment contains input features and corresponding output labels.

- Type of problem: Classification  
- Number of features: (mention your number)  
- Target variable: (mention your target column name)  
- Dataset split: 80% Training, 20% Testing  

The data is preprocessed before training the model.

---

## Model Architecture
The model is built using TensorFlow Sequential API and consists of:

- Input Layer
- Hidden Layer (ReLU activation)
- Hidden Layer (ReLU activation)
- Output Layer (Sigmoid activation for binary classification)

Optimizer used: Adam  
Loss function: Binary Crossentropy  
Evaluation metric: Accuracy  

---

## Model Training
The model is trained using:

- Epochs: 20  
- Batch size: 32  
- Validation split: 0.2  

During training, the model learns patterns from the dataset to improve prediction performance.

---

## Model Evaluation
The trained model is evaluated on the test dataset using the following metrics:

- Accuracy
- Precision
- Recall

These metrics help measure the performance and reliability of the model.

---

## Results
The model was successfully trained and evaluated. The obtained performance metrics demonstrate that the model can effectively classify the given data.

(You can add your actual accuracy, precision, recall values here.)

---

## Conclusion
In this practical, we successfully implemented a basic AI prototype using TensorFlow. The model was trained on a dataset and evaluated using performance metrics. This experiment helped in understanding neural networks, training processes, and model evaluation techniques.

---

## Learning Outcomes
- Understanding TensorFlow framework
- Building and training Neural Networks
- Evaluating AI models using performance metrics
- Applying AI to real-world datasets