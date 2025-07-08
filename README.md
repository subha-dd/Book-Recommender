# 📚 Book Recommendation System

A content-based Book Recommendation System built using Python and Jupyter Notebook. The system suggests books to users based on their preferences and also incorporates average book ratings to improve recommendation quality.

---

## 🚀 Overview

This project aims to provide personalized book recommendations to users based on:
- Similarity of book content (e.g., title, author, genre)
- User input or selected books
- Popularity and average ratings from a dataset

It uses Natural Language Processing (NLP) techniques and a content-based filtering approach to recommend books that are similar in nature or highly rated by other users.

---

## 🧠 Features

- 📖 Recommends books based on user’s selected title
- ⭐ Considers average ratings for more relevant suggestions
- 🗂️ Works on a dataset of thousands of books
- 🛠️ Built completely in Jupyter Notebook
- 📊 Clean visualizations for data understanding and EDA

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK (for basic NLP)
- Matplotlib, Seaborn
- Jupyter Notebook

---

📊 Dataset
The dataset used in this project includes:

Book metadata: books.csv

User ratings: ratings.csv

User information: users.csv

---

🔍 Recommendation Logic
Content-Based Filtering:
Uses cosine similarity on book features (title, author, genre, etc.)

Rating-Based Sorting:
After filtering, top recommended books are sorted based on average rating.

