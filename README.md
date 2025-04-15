# 🎬 Movie Recommender System

This is a simple Movie Recommender System built using **Python**, **Streamlit**, and **TMDB (The Movie Database)** dataset. The app recommends movies similar to the one selected by the user, along with posters fetched using TMDB's API.

## 🔍 Features

- Recommend top 5 similar movies
- Fetch and display movie posters
- Lightweight UI with Streamlit
- Trained using cosine similarity on movie features

## 📦 Dataset

The dataset is based on metadata from [TMDB (The Movie Database)](https://www.themoviedb.org/), which includes:
- Movie titles
- Genre, keywords, cast, crew
- TMDB IDs (used to fetch posters)

## 🚀 Tech Stack

- **Python**
- **Streamlit** – for interactive UI
- **Pickle** – to store trained data
- **Pandas & Scikit-learn** – for data manipulation and modeling
- **Requests** – to call TMDB API

