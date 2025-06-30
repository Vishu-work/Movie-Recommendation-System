# 🎬 Movie Recommendation System using TMDB & Streamlit

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![NLP](https://img.shields.io/badge/NLP-CountVectorizer-orange)
![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-red)
![Status](https://img.shields.io/badge/Project-Completed-success)

> 🎥 Get personalized movie recommendations using content-based filtering and NLP techniques — all within a clean, interactive Streamlit UI!

---

## 🗂️ Table of Contents

- [📖 Overview](#-overview)
- [📦 Features](#-features)
- [🧠 How It Works](#-how-it-works)
- [🖥️ Streamlit Interface](#️-streamlit-interface)
- [🚀 Getting Started](#-getting-started)
- [📊 Dataset Info](#-dataset-info)
- [📸 Sample UI](#-sample-ui)
- [🔮 Future Enhancements](#-future-enhancements)
- [🙌 Acknowledgements](#-acknowledgements)
- [📬 Contact](#-contact)

---

## 📖 Overview

This is a **content-based movie recommendation system** that suggests similar movies based on your selection.  
It uses **NLP techniques (CountVectorizer + Cosine Similarity)** to process movie metadata (genre, cast, crew, keywords, etc.) and recommends top 5 similar titles.

🧠 Built using:
- Python
- Pandas, scikit-learn
- Streamlit (for deployment)
- TMDB dataset

---

## 📦 Features

✅ Recommends 5 similar movies based on selected title  
✅ Uses **CountVectorizer** to convert text to feature vectors  
✅ Computes **Cosine Similarity** between movie vectors  
✅ Handles missing posters or bad inputs gracefully  
✅ Interactive **Streamlit-based** web UI  
✅ Cleaned TMDB data: genres, cast, crew, keywords merged into one tag  

---

## 🧠 How It Works

```mermaid
graph LR
  A[TMDB Dataset] --> B[Data Cleaning and Preprocessing]
  B --> C[Tag Creation: Genres + Cast + Crew + Keywords]
  C --> D[Vectorization via CountVectorizer]
  D --> E[Cosine Similarity Matrix]
  E --> F[Recommendation Logic]
  F --> G[Top 5 Similar Movies]
