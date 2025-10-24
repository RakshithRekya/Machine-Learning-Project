🧾 Movie Recommender System — Movie Dataset
📖 Project Overview

This project demonstrates a basic movie recommender system that suggests movies similar to a given title based on user rating correlations.
Using the movie dataset, the model finds movies with similar audience preferences while ensuring reliable recommendations through a rating count threshold.

🎯 Objective

To build a simple, correlation-based movie recommender system that recommends similar movies to a given title (e.g., Liar Liar), ensuring results are statistically reliable.

🧠 Key Steps

Data Loading – Import the movie dataset containing movie names and user ratings.
Data Preparation – Create a pivot table of users and movie ratings.
Correlation Computation – Calculate pairwise correlations between movie ratings.
Filtering – Include only movies with more than 100 user ratings to improve recommendation reliability.
Recommendation Generation – Display the top 10 movies most similar to the selected movie.

📊 Dataset Information

Dataset Name: movie_id_title

Features Include:
movie_id — Unique identifier for each movie
title — Movie name
user_id — Identifier for users providing ratings
rating — User’s rating for the movie

⚙️ Technologies Used

Python 
pandas
numpy
scikit-learn 
matplotlib

📈 Results

After filtering movies with fewer than 100 ratings, the system outputs a ranked list of movies most similar to “Liar Liar” and “Star Wars” based on user rating correlations.

💡 Learnings

Correlation-based recommender systems are simple yet powerful for small datasets.
Filtering by rating count improves reliability by reducing noise from under-rated movies.
Similarity measures can effectively capture user preference trends.

📂 Dataset Source

The movie dataset is a common sample dataset used in recommender system tutorials, containing movie titles, user IDs, and ratings.