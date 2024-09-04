# Movie Genre Classification

## Overview

This repository contains a project for classifying movie genres based on their descriptions using machine learning models. The project demonstrates the use of various classification algorithms to predict the genre of a movie given its description. It includes data preprocessing, model training, evaluation, and testing.

## Project Structure

- `data/`: Contains the CSV files used for training and testing the models.
  - `train_data.csv`: Training data with movie descriptions and genres.
  - `test_data.csv`: Test data with movie descriptions.
  - `test_data_solution.csv`: Test data with movie descriptions and genres (for validation).

- `models/`: Contains the saved machine learning models.
  - `logistic_regression_model.pkl`: Logistic Regression model.


- `notebooks/`: Contains Jupyter notebooks for data analysis and model training.
  - `movie_genre_classification.ipynb`: Jupyter notebook with code for data preprocessing, model training, evaluation, and predictions.

- `try.py`: Python script to load a model and predict the genre of a movie based on a user-provided description.

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/movie-genre-classification.git
   cd movie-genre-classification
