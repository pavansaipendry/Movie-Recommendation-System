# Movie Recommendation System - Cosine Similarity

This repository contains a Movie Recommendation System that suggests movies based on user input. It uses **Cosine Similarity** to recommend similar movies by analyzing features such as genres, keywords, cast, crew, and director from the dataset. The system can handle spelling mistakes using the `difflib` library to find the closest movie match.

## Introduction

The objective of this project is to recommend movies to users based on their favorite movie. The system uses **Cosine Similarity** to compute similarities between movies by considering important features such as genres, keywords, and cast. The model ensures accurate results even with spelling errors by finding the closest matching movie title using `difflib`.


## Project Workflow

1. **Data Loading**: Load the movie metadata dataset using Pandas.
2. **Data Preprocessing**: Fill missing values in important features and combine them into a single textual format.
3. **Vectorization**: Convert the combined textual data into numerical format using **TF-IDF Vectorizer**.
4. **Cosine Similarity**: Compute similarity between all movies using Cosine Similarity.
5. **Recommendation**: Suggest movies based on similarity scores for the user's favorite movie.


