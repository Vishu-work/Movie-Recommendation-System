# Movie-Recommendation-System
🎬 Movie Recommendation System using TMDB & Streamlit
A content-based movie recommendation app that suggests similar movies using natural language processing (NLP) techniques like CountVectorizer. Built with Streamlit for an interactive user interface and includes robust exception handling.

📌 Features

🔍 Recommends movies based on a selected movie
🧠 NLP-based vectorization (CountVectorizer)
💬 Cleaned and combined TMDB data (genres, keywords, cast, crew)
✅ Cosine similarity computation for recommendations
⚙️ Exception handling for missing/invalid inputs
🌐 Deployed with Streamlit for simple, shareable web UI

🧠 How It Works

Data Preprocessing: TMDB movie metadata is cleaned and features are merged into a single text column.
Vectorization: CountVectorizer transforms movie metadata into feature vectors.
Similarity: Cosine similarity is calculated between movie vectors.
Recommendation: Top 5 similar movies are returned based on user selection.
Streamlit Interface: Simple dropdown and button-based UI for input/output.

🖥️ Example UI

Input: Select a movie from a dropdown.
Output: List of 5 recommended movies.
Error Handling: Graceful fallback if the selected movie poster isn't found in the dataset.



