Loan Prediction with Logistic Regression
This project uses Logistic Regression to predict whether a loan is healthy or high-risk based on various borrower features.

Project Overview
The goal of this project is to predict loan statuses:

Healthy Loan (0)
High-Risk Loan (1)
The model is evaluated using metrics such as accuracy and balanced accuracy.

How It Works
Load the Dataset
The dataset lending_data.csv contains information on loans, including the target variable (loan_status).

Data Preparation
The data is split into:

Features (X): Information used to predict the loan status (e.g., income, credit score).
Labels (y): The loan status (0 for healthy loan and 1 for high-risk loan).
Model Training
A Logistic Regression model is trained using the training data (X_train, y_train).

Making Predictions
The model predicts loan statuses on the test data (X_test).

Model Evaluation
We evaluate the model using:

Accuracy Score: Overall percentage of correct predictions.
Balanced Accuracy: Accuracy for each class (healthy and high-risk loans).
Confusion Matrix: Shows how many predictions were correct or wrong.
Classification Report: Includes precision, recall, and F1 score for both classes.

Key Results
Accuracy Score: 99.18%
Balanced Accuracy Score: 95.20%
The model performs well in predicting healthy loans, but it struggles more with high-risk loans due to the imbalanced dataset. The dataset has 96.77% healthy loans and 3.23% high-risk loans.

Requirements
Python 3.x
Libraries:
pandas
numpy
scikit-learn

Conclusion
The Logistic Regression model is effective at predicting healthy loans but has room for improvement in predicting high-risk loans due to the imbalance in the dataset. Future improvements could include techniques like oversampling or using other models.
