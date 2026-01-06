# 🎬 Movie Recommendation System

A machine learning–based **Movie Recommendation System** that suggests similar movies based on content similarity.  
The system is built using **Python**, **TF-IDF vectorization**, and **cosine similarity**, and deployed as an interactive **Streamlit web application**.

---

## 🚀 Features
- Content-based movie recommendation
- Uses movie **overview, genres, keywords, cast, and director**
- TF-IDF vectorization for text processing
- Cosine similarity for recommendation
- Interactive **Streamlit web interface**

---

## 🛠 Tech Stack
- Python
- Pandas & NumPy
- Scikit-learn
- NLTK
- Streamlit

---

## 📊 Dataset
- **TMDB 5000 Movies Dataset**
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

The dataset contains information about movies such as genres, overview, cast, crew, and keywords.

---

## 🧠 How It Works
1. Movie metadata is cleaned and combined into a single text feature called **tags**
2. Text data is converted into numerical vectors using **TF-IDF Vectorizer**
3. **Cosine similarity** is calculated between all movies
4. The system recommends the **top 5 most similar movies** based on the selected movie

---

## 📁 Project Structure
