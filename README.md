# Movie-Recommendation-System
# Overview
This project implements a movie recommendation system using Python and machine learning techniques. The system provides recommendations based on various criteria such as movie name, genre, year, director, and top-rated movies. It utilizes a dataset sourced from a CSV file containing information about various movies.

# Features
Get movie recommendations by movie name: Provides recommendations similar to a specified movie.
Get movie recommendations by genre: Lists top-rated movies of a given genre.
Get movie recommendations by year: Displays top-rated movies released in a specific year.
Get movie recommendations by director: Recommends movies directed by a specified director.
Get top 20 highest rated movies: Displays a list of the top-rated movies in the dataset.
# Data Source
The movie data is sourced from a CSV file (movies.csv) containing columns such as title, genres, keywords, tagline, cast, director, release date, and vote average.

# Technologies Used
Python
pandas
scikit-learn (for TF-IDF vectorization and cosine similarity)
matplotlib and seaborn (for data visualization)
# Project Structure
1. movies.csv: CSV file containing the movie dataset.
2. Movie Recommendation System.ipynb: Python script implementing the recommendation system.
- Data preprocessing: Combines features and calculates similarity using TF-IDF and cosine similarity.
- Functions to get recommendations based on movie name, genre, year, director, and top ratings.
- Menu-driven interface for user interaction.
3. README.md: This file, providing an overview of the project.
