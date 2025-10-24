🧾 Natural Language Processing — Yelp Reviews Classification

📖 Project Overview

This project applies Natural Language Processing (NLP) techniques to classify Yelp reviews based on their textual content.
Using the Yelp dataset, the goal is to predict the star rating (1–5) given by a user solely from the review text.
Two feature extraction techniques were compared — Count Vectorizer and TF-IDF — with Naive Bayes as the classifier.
Surprisingly, the Count Vectorizer approach achieved better accuracy than TF-IDF.

🎯 Objective

To build and evaluate a text classification model that predicts Yelp review ratings from text data using vectorization and the Naive Bayes algorithm.

🧠 Key Steps

Data Loading – Importing the Yelp dataset containing text reviews and ratings.
Data Exploration – Analyzing text length, rating distribution, and sentiment trends.
Text Vectorization – Converting text into numeric features using:
Count Vectorizer (word frequency)
TF-IDF Vectorizer (term importance weighting)
Model Training – Applying Multinomial Naive Bayes for classification.
Model Evaluation – Assessing performance using confusion matrix and classification report.

📊 Dataset Information

Dataset Name: Yelp Reviews Dataset
Number of Samples: ~10,000 (subset used for faster training)
Features Include:

text — Customer review content
stars — Review rating (1–5)
cool, useful, funny — User reaction counts
Target Variable: stars

⚙️ Technologies Used
Python 
pandas
numpy
matplotlib, seaborn
scikit-learn 

📈 Results

✅ CountVectorizer + Naive Bayes achieved the best performance with around 84% accuracy.
📊 Predictions were well-balanced across different review ratings.
⚠️ TF-IDF performed worse due to overemphasis on rare words.
💡 Count-based features captured sentiment patterns more effectively for short reviews.
🔍 Demonstrated that simple vectorization can outperform complex methods for opinion-heavy text data.

💡 Learnings

CountVectorizer can outperform TF-IDF for short, opinionated text (like reviews).
Naive Bayes is fast, interpretable, and effective for text classification.
Text preprocessing and feature representation play a critical role in NLP model success.
Simple models can outperform complex ones with proper data cleaning and feature tuning.

📂 Dataset Source

The Yelp Reviews Dataset is available publicly via Yelp Open Dataset and commonly used for NLP experiments.