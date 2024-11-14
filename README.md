# Spam Email Detector

This project focuses on developing a supervised machine learning (ML) model to classify emails as either spam or not spam. The models created in this project aim to improve the email filtering system for an Internet Service Provider (ISP), allowing spam emails to be effectively filtered out of customer inboxes.

## Project Overview:

The goal of this project is to:

- Develop two machine learning models: Logistic Regression and Random Forest Classifier.
  
- Evaluate the models based on accuracy to determine which model performs better in detecting spam emails.
  
- Scale the features, train the models, and interpret the results to identify the most effective model.

  
## Dataset:

The dataset used in this project contains various features extracted from emails, including:

- Frequencies of specific words and characters in the email.
  
- Presence of certain patterns that are indicative of spam emails.

### Target Column:

spam: The column indicates whether an email is spam (1) or legitimate (0).

### Source

The dataset file spam-data.csv is included in this repository.

## Models:

The following machine learning models were implemented and compared:

- Logistic Regression: A statistical method for binary classification that predicts the probability of a label being spam or not spam.
Advantage: Simple and interpretable.

- Random Forest Classifier: An ensemble learning method that builds multiple decision trees and combines their results for more robust classification.
Advantage: Handles non-linear relationships well and is less prone to overfitting.

## Steps to Run the Project

### Prerequisites:

- Python 3.x installed on your system.

### Required libraries installed:

- pandas

- scikit-learn

- Jupyter Notebook

- Install the required libraries with:

## Results

### Accuracy Scores:

- Logistic Regression Accuracy: ~92.6%

- Random Forest Accuracy: ~95.0%

## Conclusion:

The Random Forest Classifier performed better than Logistic Regression, achieving higher accuracy in detecting spam emails.

