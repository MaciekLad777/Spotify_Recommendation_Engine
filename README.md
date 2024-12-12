# Spotify Recommendation Engine

**Welcome to the Spotify Genre Prediction and Recommendation Engine project! This repository explores Spotify track data to address challenges such as incomplete genre information and imbalanced genre distributions. By analyzing key factors like audio features (e.g., energy, tempo, and loudness), tag-based embeddings, and artist patterns, we develop a reliable genre prediction model and a personalized recommendation system.**

## Project Overview

The project consists of three main sections:

1. **Power BI Report**
   - Serves as the central guide and narrative for the project.
   - Provides insights into the data.
   - Examines the results of genre assignment, model performance, and the recommendation engine.

2. **Genre assignment**
   - Data cleaning and preparation.
   - Creation of specialized embeddings for categorical features and correction of skewed columns.
   - Training, testing, and evaluating multiple models.
   - Assigning genres to tracks using the final, optimized model.

3. **Recommendation Engine**
   - Building a function to recommend songs based on user history.
   - Optimizing the function’s weights for best performance.
   - Generating song recommendations for a sample of 100 users and evaluating the results.

## Project Structure

- `Spotify data analysis.pbix`: Power BI report for data exploration and the main narrative of the project.
- `Genre_assigning.ipynb`: Jupyter notebook for data preprocessing, training the genre prediction model, and filling in missing genres.
- `Recommendation_Engine.ipynb`: Jupyter notebook for defining, testing, and optimizing the song recommendation function based on user listening history.
