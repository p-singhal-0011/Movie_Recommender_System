# 🎬 Movie Recommender System

A content-based movie recommender system built using Python, Streamlit, and scikit-learn. This application allows users to select a movie and get five similar movie recommendations based on content features like overview, genres, keywords, and more.

---

## 🚀 Features

- 📌 Select any movie from a dropdown list
- 🧠 Uses content similarity to recommend 5 similar movies
- 📊 Based on NLP techniques and vectorization
- ⚡ Fast and easy to use with Streamlit web interface

---

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- Pickle (for model persistence)
- Streamlit (for the web interface)

---

## 📁 Project Structure
```
📁 Movie_Recommender_System/

  📁 ── venv/
    ├── app.py
    ├── app_ph.py
    ├── Procfile
    ├── requirements.txt
    ├── setup.sh
    ├── movie_dict.pkl
    ├── movie_list.pkl
    ├── similarity.pkl
    └── .gitignore
  ├── movie_dict.pkl
  ├── movie_list.pkl
  ├── similarity.pkl
  ├── Movie_Recommend_System.ipynb
  ├── README.md
  📁 ── assets/
    └── screenshot.png
```


---

## 📊 How It Works

- A similarity matrix is generated using vectorized movie content (like genres, keywords, overviews).
- On selecting a movie, its vector is compared to others using cosine similarity.
- The top 5 most similar movies are shown in the UI.

---

## ▶️ How to Run the App Locally

### 🔹 Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/Movie_Recommender_System.git
cd Movie_Recommender_System
```
### 🔹 Step 2: Set Up Virtual Environment
```
python -m venv venv
venv\Scripts\activate 
```
### 🔹 Step 3: Install Dependencies
```
pip install -r requirements.txt
```
### 🔹 Step 4: Run Streamlit App
```
streamlit run app.py
```
