# 🎬 Movie Recommendation System (FastAPI + ML)

This project is a *Movie Recommendation System* built using *Python, FastAPI, and Machine Learning*.
It recommends similar movies based on content features such as genres, keywords, cast, director, and tagline.

The system uses *TF-IDF Vectorization* and *Cosine Similarity* to calculate similarity between movies and exposes the recommendations through a *FastAPI REST API*.

---

## 🚀 Features

* Content-based movie recommendation system
* FastAPI backend for serving recommendations
* Fuzzy matching to handle partial or incorrect movie names
* JSON-based API request and response
* Interactive API documentation using Swagger UI
* CORS enabled for frontend integration

---

## 🛠 Technologies Used

* Python
* FastAPI
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity
* VS Code
* Git & GitHub

---

## 📂 Project Structure

bash
├── main.py
├── movies.csv
├── requirements.txt
├── README.md


---

## 📊 Dataset

* The project uses a movie dataset containing features such as:

  * Genres
  * Keywords
  * Tagline
  * Cast
  * Director

These features are combined to generate meaningful movie recommendations.

---

## ⚙ How the Recommendation Works

1. Missing values are handled in the dataset
2. Important movie features are combined into a single text field
3. TF-IDF Vectorizer converts text data into numerical vectors
4. Cosine similarity is used to measure similarity between movies
5. Movies with the highest similarity scores are recommended

---

## ▶ How to Run the Project Locally

### 1️⃣ Clone the repository

bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


### 2️⃣ Install dependencies

bash
pip install -r requirements.txt


### 3️⃣ Run the FastAPI server

bash
uvicorn main:app --reload


### 4️⃣ Open API Docs

* Swagger UI:
  👉 [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---
