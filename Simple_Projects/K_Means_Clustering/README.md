🧾 K-Means Clustering — University Dataset
📖 Project Overview

This project demonstrates the use of the K-Means Clustering algorithm to group universities into two distinct categories — Private and Public — based on various institutional and student-related features.
Although the dataset contains labeled information, the clustering is performed as an unsupervised learning task to observe how well K-Means can naturally separate the universities without using the labels.

🎯 Objective

To apply the K-Means Clustering algorithm on the university dataset and evaluate its ability to correctly classify universities into Private and Public groups based on numerical attributes.

🧠 Key Steps

Data Loading – Importing the dataset (College_Data.csv) using pandas.
Exploratory Data Analysis (EDA) – Visualizing feature relationships and distributions using Seaborn and Matplotlib.
Data Cleaning – Correcting invalid entries where Grad.Rate > 100.
Model training – Applying K-Means with n_clusters = 2 to identify natural groupings.
Model Evaluation – Comparing clustering results against true labels using confusion matrix and classification metrics.

📊 Dataset Information

Dataset Name: College Data (Universities Dataset)
Number of Samples: 777
Features Include:
Applications, Acceptances, Enrollments
Out-of-State Tuition (Outstate)
Room & Board Costs
Graduation Rate (Grad.Rate)
Faculty Ratios and PhD Percentages
Target Variable: Private (Yes/No)

⚙️ Technologies Used

Python 
pandas
numpy
matplotlib
seaborn
scikit-learn

📈 Results

The K-Means model successfully grouped universities with an overall accuracy of 78% when compared to actual labels.

💡 Learnings

K-Means can effectively find patterns in unlabeled datasets.
Proper data cleaning (e.g., fixing invalid values) improves clustering results.
Evaluating clustering results using known labels helps assess performance quality.
Visualization plays a key role in interpreting cluster separations.
