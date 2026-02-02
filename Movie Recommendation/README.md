# 🎬 Movie Recommendation System Using Cosine Similarity

## 📌 Project Overview

This project implements a **Movie Recommendation System** using **Python**, **TF-IDF vectorization**, **Cosine Similarity**, and the **difflib library**.

The goal is to recommend movies similar to a given movie based on movie descriptions or metadata. This approach mimics **content-based recommendation systems** used by streaming platforms like Netflix, Hulu, and Amazon Prime.

This project is part of my **Data Science and Machine Learning learning journey**, where I apply NLP techniques and similarity measures to real-world datasets.

## 🎯 Problem Statement

With thousands of movies available, users often struggle to find movies that match their interests. Recommendation systems help by automatically suggesting movies based on user preferences or content similarity.

The objective of this project is to:

> **Build a content-based movie recommendation system that recommends movies similar to the one selected by the user.**

## 📂 Dataset Description

The dataset contains movie information including metadata, descriptions, and genres.

### Features Include:

- **Title**: Name of the movie
- **Overview / Description**: Summary of the movie plot
- **Genres**: Movie categories or genres
- **Keywords / Tags**: Additional metadata for the movie

These features help determine similarity between movies.

## 🛠️ Technologies & Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn (TfidfVectorizer, Cosine Similarity)
- difflib (for fuzzy matching of movie titles)
- Jupyter Notebook

## 🧠 Machine Learning & NLP Workflow

### 1️⃣ Data Loading

- Loaded the movie dataset using Pandas
- Examined data structure and columns
- Checked for missing or duplicate entries

### 2️⃣ Data Cleaning & Preprocessing

- Filled missing descriptions with empty strings
- Lowercased all text for consistency
- Combined relevant text features (overview, genres, keywords) into a single column
- Removed punctuation and unnecessary characters

Why: Preprocessing ensures that textual features can be effectively transformed into vectors for similarity calculation.

### 3️⃣ Feature Extraction with TF-IDF

- Used **TfidfVectorizer** to convert text data into numerical vectors
- TF-IDF captures the importance of each word in the context of all movies
- Output is a matrix representing each movie in vector space

### 4️⃣ Calculating Similarity

- Calculated **Cosine Similarity** between all movie vectors
- Cosine similarity measures the angle between vectors to determine how similar two movies are

Why: Cosine similarity is effective for text-based recommendations, as it identifies movies with similar content.

### 5️⃣ Handling User Input with difflib

- Used **difflib.get_close_matches()** to match user input to the closest movie title in the dataset
- This handles spelling mistakes and ensures the recommendation system works even if the user types imperfectly

### 6️⃣ Recommendation Function

- Created a function `recommend(movie_name)` that:
  - Finds the closest matching movie
  - Computes similarity scores with all other movies
  - Returns the top 5-10 most similar movies

### 7️⃣ Example Output

If the user selects `"The Dark Knight"` as input, the system might recommend:

- `"Batman Begins"`
- `"The Dark Knight Rises"`
- `"Batman v Superman: Dawn of Justice"`
- `"Joker"`
- `"Watchmen"`

## 📊 Results & Insights

- Recommendations reflect movie similarity in content and genres
- Combining **overview + genres + keywords** improves recommendation quality
- TF-IDF + Cosine Similarity is lightweight and effective for content-based recommendations
- The system handles user input errors using difflib

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### 2️⃣ Navigate to Project Folder

```bash
cd movie-recommendation-system
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and execute all cells.

### 5️⃣ Test Recommendations

Use the `recommend()` function to get movie recommendations:

```python
recommend("Inception")
```

## 🔮 Future Improvements

- Incorporate **user-based collaborative filtering**
- Use **deep learning / embeddings** for better content representation
- Deploy as a **web app or API**
- Add **ratings and user preferences** to improve recommendations
- Handle multilingual datasets for global applications

## 📚 Learning Outcomes

Through this project, I learned:

- Text preprocessing for NLP
- Feature extraction using TF-IDF
- Calculating similarity with Cosine Similarity
- Handling user input errors with difflib
- Building a basic content-based recommendation system
- Practical implementation of ML for real-world applications

## 💼 Real-World Applications

- Movie streaming platforms (Netflix, Hulu)
- Music and book recommendation systems
- E-commerce product recommendations
- Personalized content feeds

## 🤝 Contributing

This project is part of my learning journey. Suggestions and improvements are welcome.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

I regularly document my **Data Science and ML projects** and share tutorials on my blog.

## 🌟 Star the Repository

⭐ If you found this project helpful, feel free to star the repository!
