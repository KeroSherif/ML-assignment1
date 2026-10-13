# ML Assignment 1 — MovieLens Collaborative Filtering

## Project Overview

This project implements a movie recommendation system using the MovieLens dataset. It explores collaborative filtering techniques to predict user ratings based on similarities between users and movies.

## Assignment Parts

### Part A — Data Loading and Exploration
- Load the ratings and movies datasets.
- Calculate the number of users, movies, and ratings.
- Calculate dataset sparsity.
- Construct the user-item rating matrix.
- Analyze rating distribution and ratings per user.

### Part B — Similarity Measures
- Extract co-rated items between users or movies.
- Implement Euclidean Similarity.
- Implement Cosine Similarity.
- Implement Pearson Similarity.
- Handle cases with insufficient co-rated items.

### Part C — User-Based Collaborative Filtering
- Find the nearest neighbors of a target user.
- Select neighbors who rated the target movie.
- Predict ratings using similarity-weighted ratings.
- Return no prediction when suitable neighbors are unavailable.

### Part D — Item-Based Collaborative Filtering
- Calculate similarities between movies.
- Find the nearest neighboring movies.
- Predict user ratings based on similar movies the user has rated.

### Part E — Evaluation and Experiments
- Split each user's ratings into training and testing sets using an 80/20 ratio.
- Evaluate predictions using RMSE and MAE.
- Calculate the fraction of test ratings that can be predicted.
- Compare 24 configurations using:
  - 2 collaborative filtering methods.
  - 3 similarity measures.
  - 4 values of \(k\): 5, 10, 20, and 50.

### Part F — Analysis and Discussion
- Analyze and compare experimental results.
- Provide an example comparing Euclidean and Pearson similarity rankings.
- Discuss computational complexity and scalability.

### Bonus
- Implement user-based collaborative filtering with mean-centered ratings.
- Compare its RMSE with the standard approach.
- Generate the top 10 movie recommendations for a user.

## Dataset

The project uses the MovieLens dataset, including:
- `ratings.csv`
- `movies.csv`

## Technologies
- Python
- NumPy
- Pandas
- Jupyter Notebook

## Project Status

The project is currently in progress.
