# Movie Recommender System

An end-to-end content-based movie recommender system that suggests similar movies based on features such as genres, keywords, and tags. This system is built using Python and leverages machine learning techniques for recommending the top 5 movies similar to the one selected by the user.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project is a content-based recommendation system that uses movie metadata to find similar movies. The system is built using the Kaggle dataset of 5000 movies. It processes the data and generates movie recommendations based on cosine similarity between movies' feature vectors.

## Technologies Used

- Python
- NumPy
- Pandas
- scikit-learn
- NLTK
- Streamlit

## Dataset

The dataset used in this project contains metadata about 5000 movies, including information such as genres, keywords, cast, crew, and more. The dataset is publicly available on [Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata).

## Features

- **Data Preprocessing**: Cleaned and preprocessed the movie metadata, including handling missing values, generating tags, and feature extraction.
- **Bag of Words Model**: Created tags for each movie and transformed them into feature vectors using the Bag of Words technique.
- **Cosine Similarity**: Calculated cosine similarity between movies to recommend the top 5 movies most similar to the selected movie.
- **Interactive Interface**: Used Streamlit to build a simple and user-friendly interface where users can select a movie and receive movie recommendations.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Amanrai2004/MovieRecommenderSystem.git


cd MovieRecommenderSystem


#Create a virtual environment and install the required dependencies:

conda create -p venv python=3.9
conda activate ./venv
pip install -r requirements.txt



You can modify the `git clone` link and other project-specific details as needed!
