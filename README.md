# Movie Recommender System

## Project Overview

This **Movie Recommender System** leverages machine learning and data science techniques to recommend 5 similar movies based on a given movie. The system uses 5000 movie records sourced from Kaggle, which include various movie details such as titles, genres, and poster images. The project is built using `numpy`, `pandas`, `scikit-learn`, `streamlit`, `requests`, `nltk`, `cosine_similarity`, and `pickle` for saving the model.

## Features

- **Movie Recommendation**: Given the name of a movie, the system recommends 5 similar movies.
- **Movie Posters**: Displays the poster images of recommended movies.
- **Streamlit Interface**: Interactive web app for users to input movie names and get recommendations.
- **API Integration**: Fetches movie posters from an external API (e.g., TMDB API).
- **Natural Language Processing**: Uses `nltk` for text processing in movie descriptions.
- **Cosine Similarity**: Implements cosine similarity for calculating movie similarities based on features.
- **Pickle Model**: Saves the trained recommendation model using `pickle`.
