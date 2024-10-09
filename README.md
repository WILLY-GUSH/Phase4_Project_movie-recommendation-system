Movie Recommendation System
Project Overview
This project implements a Movie Recommendation System using two main approaches:

Content-Based Filtering: Recommends movies based on the similarity between movie attributes (e.g., genres, descriptions).

Collaborative Filtering: Recommends movies by finding patterns from user ratings (using matrix factorization or neighborhood-based approaches).

The goal is to provide personalized movie recommendations based on user preferences and movie characteristics.

Table of Contents
Project Overview

Features

Datasets

Setup Instructions

Usage

Evaluation

Contributors

FEATURES

Content-Based Filtering: Recommends movies similar to those a user has liked in the past based on metadata (e.g., genres, keywords).

Collaborative Filtering: Recommends movies based on user interactions (ratings) by leveraging similarities between users and movies.

Evaluation Metrics: Implements evaluation techniques such as Precision@K, Recall@K, and Root Mean Squared Error (RMSE) for both recommendation models.

DATASETS

The project uses two main datasets:

Movies Metadata: Contains movie attributes such as genres, release year, and title.

User Ratings: Contains user ratings for various movies, with each entry capturing the user ID, movie ID, and rating.

DATASETS:

movies.csv

ratings.csv

tags.csv

links.csv

Each dataset is loaded as a pandas DataFrame

USAGE

The recommandation system is used to recommend movies to viewers based on their genre prefrence and also based on users ratings

EVALUATION

To evaluate the model we used RMSE a common metrics for evaluating predictive system
