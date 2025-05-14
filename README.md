# 🎬 Movie Recommendation System 🚀

Welcome to the **Movie Recommendation System**, a machine learning-powered project designed to provide personalized movie suggestions based on user preferences. Built with Python and Streamlit, this content-based recommendation engine offers an interactive and intuitive user experience.

## 🔍 Overview

This project uses a **content-based filtering approach** to recommend movies that are similar to the user's choice. The similarity between movies is computed using features like genres, keywords, cast, and more, enabling tailored suggestions.

## 🧠 Key Features

- ✅ **Content-Based Filtering**: Uses cosine similarity to find movies similar to the user's selection.
- ✅ **Streamlit UI**: Lightweight and elegant interface for interacting with the recommender.
- ✅ **Real-Time Suggestions**: Users can select a movie and instantly get a list of recommended titles.
- ✅ **Clean and Minimal Design**: Engaging, user-friendly design built with Streamlit components.

## 📦 Tech Stack

- **Python**
- **Pandas, NumPy, Scikit-learn** – Data preprocessing and ML modeling
- **Streamlit** – Web app interface
- **Pickle** – Saving the similarity model
- **IMDb/TMDB API (optional)** – For fetching posters and details (if integrated)

## 🚀 How It Works

1. **Data Preprocessing**:
   - Clean and merge metadata (genres, cast, crew, keywords, etc.).
   - Create a new feature by combining important textual information.
   - Use CountVectorizer and cosine similarity for recommendations.

2. **Similarity Model**:
   - Vectorize the combined textual data.
   - Compute the cosine similarity matrix.
   - Recommend top N similar movies based on input.

3. **Web Interface**:
   - Select a movie from the dropdown.
   - Display recommendations with posters and titles.

