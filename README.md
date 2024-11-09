# 🕵️‍♂️ Credit Card Fraud Detection

Welcome to the **Credit Card Fraud Detection** project! This repository contains the code and analysis for building a model that identifies fraudulent credit card transactions. The dataset and models were used to predict if a given transaction is fraudulent or not based on anonymized transaction data.

## 📊 Project Overview
This project aims to:
- Analyze a dataset of credit card transactions.
- Build and evaluate a machine learning model to detect fraudulent activity.
- Demonstrate the use of Python libraries for data processing, visualization, and modeling.

## 📁 Dataset
The dataset consists of transactions made by European cardholders in September 2013. The features include:
- **Time**: Seconds elapsed between this transaction and the first transaction in the dataset.
- **V1-V28**: Principal components obtained via PCA (for privacy reasons, original features are not provided).
- **Amount**: The transaction amount.
- **Class**: The target variable (1 for fraud, 0 for non-fraud).

🔗 **Note**: The dataset is highly imbalanced, with fraudulent transactions accounting for only 0.172% of all transactions.

## 🛠️ Tools and Technologies Used
- **Python** 🐍: The main programming language used for this project.
- **Pandas** and **NumPy**: For efficient data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For data visualization to uncover trends and insights.
- **Scikit-learn** : For machine learning tasks, including data preprocessing, model building, and evaluation.
- **Logistic Regression**: The primary machine learning algorithm used to classify transactions as fraudulent or non-fraudulent.


