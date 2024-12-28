# Spotify Music Recommendation System 🎵

## Introduction

This project is a music recommendation system that suggests similar songs based on Spotify song features using machine learning models. The system groups songs into clusters and recommends the closest matches based on user input.

This project is documented using Jupyter Book for a step-by-step explanation of the data processing, modelling, and evaluation process.


## Features 
- **Data Cleaning & Preprocessing**: Removed invalid values (NA), filtered outliers, and normalized numeric columns for consistency.
- **K-Means Clustering**: Grouped songs into clusters based on numerical features (e.g., streams, release year, playlist count); Optimized the number of clusters (k) using the elbow method and silhouette score.
- **KNN-Based Recommendations**: Suggested similar songs within the same cluster using the K-Nearest Neighbors (KNN) algorithm.
- **Visualization**: Visualized clusters with scatter plots for better interpretability.
- **Interaction**: Deployed an interactive recommendation system accessible via Binder or Jupyter Notebook.


## Installation 

## Live Demo
Explore via Binder (No Installation Required)

Click the link below to open an interactive version of the notebook (in the file `Python_spotify`):
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MgSO477/Spotify_recommendation/HEAD)


## Technologies usage

## Future Application 
- Music Platforms: Enhance playlist curation on platforms like Spotify or Apple Music.
- User Personalization: Tailor recommendations based on user-specific listening history.
- Education: Use this project to teach clustering and recommendation algorithms.

## Acknowledgements
- Kaggle for providing the dataset.
- OpenAI for assisting with Python and recommendation techniques.
- Jupyter Book for creating an interactive documentation platform.
