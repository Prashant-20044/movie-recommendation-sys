# 🎬 Movie Recommendation System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Framework-Streamlit-FF4B4B.svg)](https://streamlit.io/)
[![Machine Learning](https://img.shields.io/badge/ML-Content--Based-green.svg)](https://scikit-learn.org/)

A machine learning-based application that recommends movies similar to the one selected by the user. It analyzes movie metadata such as genres, keywords, cast, and crew to provide accurate suggestions.

---

## 🚀 Overview
This project uses **Content-Based Filtering**. By converting movie tags into numerical vectors using `CountVectorizer`, the system calculates the **Cosine Similarity** between movies to find the best matches.

## 🛠️ Tech Stack
* **Language:** Python
* **Web Framework:** Streamlit
* **Libraries:** Pandas, NumPy, Scikit-learn, Pickle, Requests
* **API:** [The Movie Database (TMDB)](https://www.themoviedb.org/)

## 📂 Dataset
The project uses the **TMDB 5000 Movie Dataset** which includes:
* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Prashant-20044/movie-recommendation-sys.git](https://github.com/Prashant-20044/movie-recommendation-sys.git)
   cd movie-recommendation-sys
