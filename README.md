# movielens-recommender-systems

## Project Overview

Objective: The objective of this project is to investigate and compare recommender system algorithms using the MovieLens dataset provided by GroupLens Research. Specifically, the aim is to configure, evaluate, and compare different models against a baseline to assess their predictive performance.

## Tools and Libraries:

- Python
- NumPy
- Surprise (Simple Python Recommendation System Engine)
- Pandas
- Matplotlib
- Seaborn

## Final Models Used

NormalPredictor: A baseline model that makes random predictions based on the distribution of ratings in the training set.
KNNWithMeans: A neighbourhood-based method that predicts ratings using the mean ratings of similar users. It applies Z-score normalisation to account for individual rating biases.
SVD (Singular Value Decomposition): A matrix factorisation technique that captures latent user–item relationships for predicting missing ratings.

## Evaluation Metric

Root Mean Squared Error (RMSE), computed using 5-fold cross-validation. This metric measures the average magnitude of the error between predicted and actual ratings, with lower values indicating better performance.
