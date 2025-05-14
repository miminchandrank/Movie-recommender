# 🎬 Movie Recommendation System 🚀

Welcome to the **Movie Recommendation System**, a machine learning-powered project designed to deliver personalized movie suggestions based on user preferences. Built with **Python** and **Streamlit**, this content-based recommender system offers a fast and interactive user experience.

📽️ **Demo Video**: [Watch on LinkedIn](https://www.linkedin.com/posts/miminchandrank_machinelearning-datascience-python-activity-7304875045502210048-5hmX?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFD4aN8BBSizqogKnOr2eBg_WSmXdqUej4w)

---

## 🔍 Overview

This project utilizes a **content-based filtering** approach to recommend movies similar to the one selected by the user. It analyzes metadata such as **genres**, **keywords**, **cast**, and **crew**, then uses **cosine similarity** to identify the most relevant movies.

---

## 🧠 Key Features

- ✅ **Content-Based Filtering**: Computes similarity using a custom textual feature vector.
- ✅ **Real-Time Recommendations**: Instantly suggests similar movies based on selection.
- ✅ **Streamlit UI**: Clean and intuitive web interface for a smooth user experience.
- ✅ **Poster Fetching (Optional)**: Extendable with IMDb or TMDb API for richer visual output.

---

## 📦 Tech Stack

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Scikit-learn** – Vectorization and cosine similarity
- **Streamlit** – Web-based user interface
- **Pickle** – Model serialization
- *(Optional)* **TMDb API / IMDb API** – For movie posters and metadata

---

## 🚀 How It Works

### 🔧 1. Data Preprocessing
- Merge important metadata (title, genres, keywords, cast, crew)
- Create a unified **"tags"** column
- Clean and normalize text for vectorization

### 📐 2. Model Building
- Use `CountVectorizer` to convert text to vectors
- Apply **cosine similarity** to calculate closeness between movies
- Store similarity matrix for efficient lookup

### 🖥️ 3. Web Interface
- Movie selector dropdown via Streamlit
- Display **Top 5 recommended movies** with optional poster thumbnails
