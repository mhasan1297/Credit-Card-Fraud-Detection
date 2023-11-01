# Credit Card Fraud Detection

This project is a credit card fraud detection system that uses machine learning techniques to identify fraudulent credit card transactions. It is designed to help financial institutions and credit card companies detect and prevent fraudulent activities, ultimately protecting both the customers and the organisations.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Data Analysis](#data-analysis)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)

## Introduction

Credit card fraud is a significant issue in the financial industry, and detecting fraudulent transactions is a crucial task to minimize financial losses. This project aims to build a machine-learning model to identify fraudulent credit card transactions based on historical transaction data.

## Dataset

The dataset used for this project is a credit card transaction dataset. It contains information about credit card transactions, including features like time, amount, and anonymized features (V1, V2, V3, ... V28). The dataset also includes a "Class" column, where "0" indicates a legitimate transaction, and "1" indicates a fraudulent transaction.

### Data Preprocessing

Data preprocessing is an essential step in building a machine-learning model. In this project, we perform the following preprocessing steps:

- Load the dataset into a Pandas DataFrame.
- Check for missing values (luckily, none are in this dataset).
- Explore the distribution of legit and fraudulent transactions.
- Create a balanced dataset by under-sampling legitimate transactions to match the number of fraudulent transactions.

### Data Analysis

We analyse the statistical measures of legitimate and fraudulent transactions, comparing various features to understand the differences between the two. We also explore the means of the features for both types of transactions.

### Model Training

We train a machine learning model to predict whether a transaction is fraudulent or legitimate. In this project, we use a Logistic Regression model for simplicity. The model is trained on a subset of the data after splitting it into training and testing sets.

Please note that the model's training may require further optimisation and tuning for real-world applications.

### Model Evaluation

After training the model, we evaluate its performance using accuracy scores on both the training and testing data. The accuracy score provides insights into the model's ability to classify transactions correctly.

- Training Data Accuracy: 93.90%
- Test Data Accuracy: 91.88%

It's important to note that accuracy is just one metric. In a real-world application, additional evaluation metrics, such as precision, recall, and F1 score, should be considered for a more comprehensive assessment of the model's performance.

**Feel free to explore the project code for more details and improvements.**

---

**Note:** This README serves as a high-level overview of the project. Detailed code and implementation can be found in the project's source files.
