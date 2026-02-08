# Book-Recommender-System-using-Collaborative-Filtering

This project implements a **Book Recommendation System** using **item-based collaborative filtering**.  
The system recommends books based on user rating behavior using **cosine similarity**.

---

## 🔍 Project Overview

Recommender systems help users discover relevant items by analyzing interaction patterns.  
In this project, recommendations are generated based on how users rate books rather than book metadata.

---

## 🧠 Approach Used

- Item-based Collaborative Filtering
- Cosine Similarity for measuring similarity between books
- Popularity-based recommendation as a fallback for cold start scenarios

---

## ⚙️ Workflow

1. Load and preprocess book and rating datasets
2. Filter users and books with very few ratings to reduce sparsity
3. Create a **user–item matrix** from rating data
4. Compute **cosine similarity** between books
5. Recommend **Top-N similar books**
6. Handle cold start using **popularity-based recommendations**

---

## 📊 Key Concepts

- User–Item Matrix
- Sparsity and Cold Start Problem
- Cosine Similarity
- Collaborative Filtering
- Popularity-based Recommendation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
