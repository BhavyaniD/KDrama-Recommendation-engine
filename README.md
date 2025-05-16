# 📺 K-Drama Recommendation Engine

This project builds a **content-based recommendation system** for Korean dramas (K-Dramas), allowing users to discover new shows based on their favorite titles, genres, or actors. It leverages metadata and similarity scoring to generate personalized recommendations.

---

## 🎯 Objective

To recommend Korean dramas to users based on:
- Title similarity
- Genre overlap
- Cast and tag relevance

The model is designed to simulate the recommendation experience on platforms like **Netflix**, **Viki**, or **MyDramaList**.

---

## 📂 Dataset

- Sourced from: [MyDramaList](https://mydramalist.com)
- Key Features:
  - Drama title
  - Synopsis/description
  - Genre tags (e.g., Romance, Comedy, Thriller)
  - Cast list
  - Viewer ratings and counts
  - Language and country

---

## 🛠️ Techniques Used

- **Natural Language Processing (NLP)**:
  - TF-IDF Vectorization of plot summaries and genres
- **Similarity Matching**:
  - Cosine similarity matrix for content relevance
- **Filtering & Ranking**:
  - Top-N recommendation logic
- **Visualization**:
  - Pandas, Matplotlib, Seaborn (if included in notebook)

---

## 💡 Features

- Input: A drama title (e.g., *Crash Landing on You*)
- Output: Top 10 most similar K-Dramas
- Bonus: Extendable to other Asian dramas using metadata and similarity logic

---

## 🔍 How It Works

1. **Preprocess metadata**: clean genres, cast, tags
2. **Convert text features** into numerical representations using TF-IDF
3. **Compute pairwise similarity** between all shows
4. **Return sorted results** for the given drama title

---

## 👩‍💻 Author

**Bhavyani Dodda**  
MS Data Science – Rutgers University  
📧 bhavyani.dodda123@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/bhavyani-dodda-414ab6195)
