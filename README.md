# Deep Learning Projects  
**Topics in Numerical Analysis: Deep Learning Homework Assignments**

This repository contains homework assignments from the *Topics in Numerical Analysis: Deep Learning* course. Each assignment focuses on implementing machine learning models to solve real-world prediction tasks using various datasets.

---

## Homework Overview

### HW1: House Price Prediction (Linear Regression)
- **Dataset**: `house_train.csv` (training), `house_test.csv` (test features), `House_feature_description.csv` (feature descriptions)
- **Model**: Linear Regression
- **Task**: Build a **linear regression** model to predict house prices.  
- **Notes**:  
  - Choose your own set of features to train the model.
  - Use appropriate preprocessing techniques if necessary.

---

### HW2: Medical Appointment No-Show Prediction
- **Dataset**: `noshow_train.csv` (training), `noshow_test.csv` (test features)
- **Model**: Logistic Regression
- **Task**: Predict whether a patient will **show up for a medical appointment**.
- **Notes**:  
  - Handle categorical variables appropriately.
  - Consider class imbalance when designing the model.

---

### HW3: Fashion MNIST Image Classification
- **Dataset**: `fashion_mnist_train.csv` (training), `fashion_mnist_test.csv` (test data)
- **Model**: Deep Neural Network (DNN)
- **Task**: Classify images of clothing items into different categories.
- **Notes**:  
  - Preprocessing image data may be necessary (normalization, reshaping).
  - Implement a DNN architecture for classification.

---

### HW4: General Classification Task
- **Dataset**: `train.csv` (training), `test.csv` (test data)
- **Model**: Convolutional Neural Network (CNN)
- **Task**: Predict the labels for a generic classification dataset.
- **Notes**:  
  - Apply a CNN architecture suited for feature extraction and classification.

---

### HW5: Twitter Sentiment Analysis
- **Dataset**: `twitter_train.csv` (training), `twitter_test.csv` (test data)
- **Model**: Gated Recurrent Unit (GRU)
- **Task**: Predict the **sentiment** (e.g., positive/negative) of tweets.
- **Notes**:  
  - Preprocessing text data (tokenization, vectorization) is required.
  - Use a GRU-based model for text sequence classification.

---

## General Notes
- Models are primarily implemented from scratch or using basic libraries (e.g., NumPy, pandas, scikit-learn, TensorFlow, PyTorch).
- Each homework explores different types of data (tabular, image, text) to apply machine learning techniques in diverse scenarios.
- Further model tuning, feature engineering, and evaluation metrics were considered where appropriate.
