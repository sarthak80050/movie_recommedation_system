# Movie Recommmendation System 
A content-based movie recommendation system built with Python, Scikit-learn, and Streamlit. This application suggests similar movies based on a user's selection and is deployed on Hugging Face Spaces.

---

## 🚀 Live Demo

You can try the live application here:
**[https://huggingface.co/spaces/sarthak80050/movie_recommend](https://huggingface.co/spaces/sarthak80050/movie_recommend)**

---

## 📸 Screenshot
<img width="1919" height="912" alt="Screenshot 2025-07-27 174611" src="https://github.com/user-attachments/assets/f3b97fac-0d81-4bac-a4eb-a604ecf1ec3b" />

---

## ✨ Features

- **Interactive UI**: Select a movie from a dropdown list.
- **Content-Based Recommendations**: Get 5 movie recommendations based on content similarity (genres, keywords, cast, etc.).
- **Visuals**: Displays the movie posters for the recommended films for a better user experience.

---

## 🛠️ How It Works & Tech Stack

This project uses a content-based filtering approach. The similarity between movies is calculated based on their metadata (genres, keywords, cast, and crew).

1.  **Data Preprocessing**: The text data for each movie is combined and converted into a vector representation using the `CountVectorizer`.
2.  **Similarity Calculation**: The **cosine similarity** is calculated between the vector representations of all movies.
3.  **Recommendation**: When a user selects a movie, the system finds the 5 most similar movies based on the pre-computed similarity scores.

The primary technologies used are:
- **Python**: Core programming language.
- **Pandas**: For data manipulation and processing.
- **Scikit-learn**: For calculating the cosine similarity matrix.
- **Streamlit**: To create the interactive web application interface.
- **Hugging Face Spaces**: For deployment and hosting.
- **TMDB 5000 Movie Dataset**: The dataset used for this project.


---



