## 📌 Project Overview

This project develops a **Movie Recommender System** using user ratings data from the dataset `3A.tsv`. The goal is to provide personalized movie recommendations by analyzing user preferences and behavior patterns.

The notebook performs **exploratory data analysis (EDA)**, **data preprocessing**, and implements both **item-based** and **user-based collaborative filtering**, along with **matrix factorization** using **Singular Value Decomposition (SVD)**.

---

## 🔍 Key Steps & Methods

### 1. Data Preprocessing

* Handled missing values (if any)
* Checked rating distributions and sparsity of the matrix
* Visualized number of ratings per user and per movie

### 2. Exploratory Data Analysis (EDA)

* Correlation matrix heatmap
* Distribution plots (ratings, user/movie frequency)
* Boxplots to detect outliers
* Top-rated and most-rated movies identified

### 3. Collaborative Filtering

#### ✅ User-Based Collaborative Filtering

* Calculated user similarity (e.g., cosine similarity)
* Recommended movies based on similar user preferences

#### ✅ Item-Based Collaborative Filtering

* Used similarity between movies
* Recommended similar movies based on a user’s past ratings

### 4. Matrix Factorization (SVD)

* Decomposed the user-item matrix using SVD
* Predicted missing ratings
* Generated personalized recommendations

---

## 📊 Evaluation

* Predicted ratings were compared with actual ones for known user-movie pairs
* Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) used to evaluate performance
* Recommendation examples shown for specific users

---

## 📌 Conclusion

This recommender system is capable of:

* Providing personalized movie suggestions using collaborative filtering
* Handling sparse rating matrices effectively
* Improving recommendations using SVD-based matrix factorization
