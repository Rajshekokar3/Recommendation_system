# Recommendation_system
# Content-Based Movie Recommendation System
This repository contains a content-based recommendation system built using Python. The system suggests movies similar to a given input by analyzing textual features such as genres, keywords, cast, crew, and overview.

# Features
# Data Preprocessing:

Merging datasets (movies and credits).
Extracting relevant columns (e.g., genres, keywords, overview, cast, crew).
Handling missing and duplicate data.
Text cleaning and transformation.


# Feature Engineering:

Converting textual data into machine-readable format using Bag of Words and stemming.
Combining multiple features into a single tags column for model input.
Similarity Computation:

Using cosine similarity to measure the distance between movie vectors.
Implementing a recommendation function to fetch the top 10 similar movies.
Model Export:

Saving processed data and the similarity model using pickle for deployment.
Dataset
The model uses the TMDb 5000 Movie Dataset, which includes details about movies, such as genres, cast, crew, and keywords.

# Usage
Preprocessing: The notebook demonstrates how to clean and prepare the data for recommendation.

# Model: The recommend(movie_name) function provides movie recommendations based on the given input title.

# Deployment:

Preprocessed data and similarity matrices are saved as pickle files (movies.pkl, similarity.pkl, movie_dict.pkl) for integration with applications
