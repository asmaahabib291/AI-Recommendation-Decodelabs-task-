# 🎬 Movie Recommendation System

## 📌 Overview

This project is a **Movie Recommendation System** built using the MovieLens dataset.
It applies both **Content-Based Filtering** and **Collaborative Filtering** techniques to recommend movies based on user preferences and similarity patterns.

The goal is to understand how recommendation systems work in real-world applications like Netflix and YouTube.


## 📊 Dataset

We used the **MovieLens Latest Small Dataset**, which includes:

* Movies dataset (`movies.csv`)
* Ratings dataset (`ratings.csv`)

Dataset source: [https://grouplens.org/datasets/movielens/](https://grouplens.org/datasets/movielens/)

---

## ⚙️ Project Workflow

### 1. Data Loading

* Loaded movies and ratings datasets using Pandas

### 2. Data Cleaning

* Handled missing values
* Removed duplicates
* Processed genres column

### 3. Exploratory Data Analysis (EDA)

* Distribution of ratings
* Most rated movies
* Most common genres
* User activity analysis

### 4. Content-Based Filtering

* Used TF-IDF Vectorizer on movie genres
* Computed cosine similarity between movies
* Recommended movies similar to a given movie

### 5. Collaborative Filtering

* Built user-movie matrix
* Applied Truncated SVD for dimensionality reduction
* Computed user similarity
* Recommended movies based on similar users

### 6. Evaluation Metrics

* **Hit Rate**: measures recommendation accuracy
* **Coverage**: measures diversity of recommendations
* **RMSE**: evaluates prediction error

### 7. Diversity Improvement

* Added random movie sampling
* Included long-tail (less popular) movies
* Improved recommendation variety


## 🧠 Techniques Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity
* SVD (Singular Value Decomposition)

---

## 📈 Results

* Hit Rate: ~0.60
* Coverage: ~0.027 (can be improved with more diversity techniques)
* Model successfully recommends similar and relevant movies

---

## 🚀 Future Improvements

* Build a **Hybrid Recommendation System**
* Improve diversity and coverage
* Deploy using Streamlit or Flask web app
* Add user interface for interaction

---

## 👩‍💻 Author

Developed as part of an AI learning project focused on recommendation systems and machine learning fundamentals.



# 💡 لو عايزة مستوى أعلى

أقدر أعملك:

* README أقوى (ATS + Internship level)
* أو أزبطه portfolio ready مع صورة و badges
* أو أعملك Streamlit app للمشروع

قولي 👍
