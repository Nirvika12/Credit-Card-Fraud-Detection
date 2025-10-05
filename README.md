# CREDIT CARD FRAUD DETECTION

This repository contains a fraud detection project using the “Credit Card Fraud Detection” dataset from Kaggle.  

## PROBLEM STATEMENT
- The task involves analyzing the Credit Card Fraud Detection dataset to identify fraudulent credit card transactions. 
- The dataset contains transactions made by European cardholders over two days, with a total of 284,807 transactions, of which only 492 are fraudulent (approximately 0.17%). 
- The primary goal is to create a model that can accurately classify whether a given transaction is fraudulent or legitimate. 
- This is a binary classification problem where the target variable, labeled as "Class", indicates the transaction type: 1 for fraud and 0 for legitimate transactions.

The target variable, "Class", has two labels:

0: Legitimate transaction. 1: Fraudulent transaction. The dataset contains 30 features:

Input Features: 28 anonymized features (V1 to V28) from PCA. "Time" (elapsed seconds) and "Amount" (transaction value).

The task involves handling the dataset's severe imbalance to accurately classify fraud while minimizing false positives.

Link for Dataset : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
