🧾 Decision Tree & Random Forest Classifier — Loan Default Prediction

📖 Project Overview

This project explores how Decision Tree and Random Forest classifiers can be used to predict loan repayment behavior. The dataset contains borrower information such as credit score, interest rate, loan purpose, and payment history. The goal is to build models that can predict whether a person will fully repay their loan or default, helping financial institutions assess lending risk.

🎯 Objective

To develop and compare two classification models — Decision Tree and Random Forest — for predicting loan repayment status based on customer features.

🧠 Key Steps

Data Exploration – Analyzing distributions, correlations, and loan repayment patterns.
Data Preprocessing – Encoding categorical features and preparing training/test sets.
Model Training – Building Decision Tree and Random Forest models using scikit-learn.
Model Evaluation – Using Confusion Matrix and Classification Report to assess performance.

📊 Dataset Information

Dataset Name: loan_data.csv
Target Variable: not.fully.paid (1 = Loan not fully repaid, 0 = Fully repaid)

⚙️ Technologies Used

Python 🐍
pandas
numpy
matplotlib
seaborn
scikit-learn

📈 Results

The Decision Tree Classifier performed well but showed signs of overfitting.
The Random Forest Classifier, due to its ensemble approach, achieved higher accuracy and better generalization.
Random Forest proved to be more robust in predicting loan repayment behavior.

💡 Learnings

Understanding ensemble learning and the advantages of Random Forest over single Decision Trees.
Feature importance analysis for interpretability in financial risk prediction.
Practical implementation of supervised classification models in scikit-learn.

📂 Dataset Source

Loan data — commonly used in machine learning exercises on classification and credit risk prediction.