🧾 Support Vector Machine (SVM) Classifier — Iris Dataset

📖 Project Overview

This project demonstrates the use of a Support Vector Machine (SVM) classifier to identify different species of the Iris flower based on their sepal and petal dimensions. The Iris dataset is one of the most popular datasets for practicing machine learning classification, containing three flower species — Setosa, Versicolor, and Virginica.
Using scikit-learn, this project trains an SVM model to classify the flower species and evaluates its performance through confusion matrix and classification metrics.

🎯 Objective

To build a Support Vector Machine (SVM) classifier that accurately classifies Iris flowers into their respective species based on petal and sepal measurements.

🧠 Key Steps

Data Loading – Importing the Iris dataset using seaborn.
Exploratory Data Analysis (EDA) – Visualizing relationships between features using pair plots.
Model Training – Building and training an SVM model using scikit-learn’s SVC.
Model Evaluation – Assessing model performance with a confusion matrix and classification report.

📊 Dataset Information

Dataset Name: Iris Dataset
Number of Samples: 150
Features:
sepal_length
sepal_width
petal_length
petal_width

Target Variable: species (Setosa, Versicolor, Virginica)

⚙️ Technologies Used

Python 🐍
pandas
numpy
matplotlib
seaborn
scikit-learn

📈 Results

The SVM classifier achieved an overall accuracy of 98%.
Setosa was perfectly classified.
Versicolor and Virginica showed minor overlap due to feature similarity.
Metrics Summary:
Precision: 0.97
Recall: 0.98
F1-score: 0.98

💡 Learnings

Understanding how SVM separates classes using hyperplanes and margins.
Visualizing class separability through EDA.
Applying performance metrics for multi-class classification.

📂 Dataset Source

The Iris dataset is available in the seaborn and scikit-learn libraries.