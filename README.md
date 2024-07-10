# Bank-Customer-Churn-Prediction

Overview

This project aims to predict customer churn in a bank using the Bank Customer Churn Prediction dataset from Kaggle. The prediction is performed using an Artificial Neural Network (ANN) built with Keras and TensorFlow. Customer churn refers to when customers stop doing business with a company. Understanding and predicting churn helps banks to improve customer retention.

Data Preprocessing

Encoding categorical variables: Used one-hot encoding and label encoding for categorical variables like 'Geography' and 'Gender'.
Feature scaling: Scaled numerical features to normalize the data for better performance of the ANN.

Model

The ANN consists of the following layers:

1. Input layer
2. Dense layers with ReLU activation
3. Dropout layers for regularization
4. Output layer with sigmoid activation for binary classification
