# Spotify Recommendation Engine

Genre prediction and personalized music recommendation based on audio features and user behavior.

This project explores Spotify track data to address challenges such as incomplete genre metadata and imbalanced distributions. By analyzing audio features (e.g., energy, tempo, loudness), tag-based embeddings, and user behavior, it builds a genre prediction model and a personalized recommendation engine.

## Features

- **Power BI Dashboard**  
  Visual overview of dataset distributions, genre assignment results, and model outputs.

- **Genre Assignment**  
  - Data cleaning and preparation  
  - Specialized embeddings for categorical features  
  - Correction of skewed columns  
  - Multi-model training and evaluation  
  - Assigning genres using the optimized model

- **Recommendation Engine**  
  - Recommends tracks based on user listening history  
  - Optimizes recommendation weights  
  - Evaluates recommendations for a sample of 100 users

## Project Structure

- `Spotify_data_analysis.pbix`  
  Power BI report for data exploration and visual storytelling.

- `Genre_Assigning.ipynb`  
  Jupyter notebook for preprocessing, training genre prediction models, and assigning genres.

- `Recommendation_Engine.ipynb`  
  Jupyter notebook for defining, testing, and optimizing the recommendation logic.
