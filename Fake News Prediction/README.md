# 📰 Fake News Detection Using Logistic Regression

## 📌 Project Overview

This project focuses on building a **machine learning classification model** that predicts whether a news article is **Real or Fake** based on its textual content.

The model is built using **Logistic Regression**, a widely used and effective algorithm for binary classification problems, especially in **Natural Language Processing (NLP)** tasks.

This project was developed as part of my **learning journey in Data Science and Machine Learning**, with a strong focus on:

- Text preprocessing
- Feature extraction from text
- Building and evaluating a classification model
- Understanding how ML can be applied to real-world problems like misinformation

## 🎯 Problem Statement

The spread of fake news has become a major challenge in the digital age, influencing public opinion and decision-making.

The goal of this project is to:

> **Automatically classify news articles as Real or Fake using machine learning techniques.**

## 📂 Dataset

The dataset used in this project contains news articles with:

- **Text content** of the news
- **Labels** indicating whether the news is real or fake

**Target Variable:**

- `0` → Fake News
- `1` → Real News

The dataset is commonly used for educational purposes in fake news detection and NLP-based classification tasks.

## 🛠️ Technologies & Tools Used

- **Python**
- **NumPy** – numerical operations
- **Pandas** – data loading and manipulation
- **Scikit-learn** – machine learning models and evaluation
- **NLTK** – text preprocessing
- **TF-IDF Vectorizer** – feature extraction from text
- **Python script**

## 🧠 Machine Learning Workflow

### 1️⃣ Data Collection

- Loaded the dataset into a Pandas DataFrame.
- Explored the dataset to understand structure, labels, and text length.

### 2️⃣ Text Preprocessing

Performed several preprocessing steps to clean the text data:

- Converted text to lowercase
- Removed punctuation and special characters
- Removed stopwords
- Tokenized the text

These steps help improve model performance by reducing noise in the data.

### 3️⃣ Feature Extraction

- Converted text data into numerical features using **TF-IDF (Term Frequency–Inverse Document Frequency)**.
- TF-IDF helps identify important words while reducing the impact of commonly used words.

### 4️⃣ Train-Test Split

- Split the dataset into training and testing sets using `train_test_split`.
- This allows evaluation of how well the model performs on unseen data.

### 5️⃣ Model Selection

- Used **Logistic Regression** for binary classification.
- Logistic Regression is efficient, interpretable, and works well with high-dimensional text data.

### 6️⃣ Model Training

- Trained the Logistic Regression model on the TF-IDF transformed training data.

### 7️⃣ Model Evaluation

Evaluated the model using:

- Accuracy Score

## 📊 Model Performance

- The Logistic Regression model achieved strong performance in classifying news articles.
- The evaluation metrics show a good balance between precision and recall.

> Performance can be further improved with hyperparameter tuning or by experimenting with other models.

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/fake-news-detection.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd fake-news-detection
```

### 3️⃣ Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook or Script

- Open the Jupyter Notebook and run all cells
  **OR**
- Run the Python script:

```bash
python fake_news_detection.py
```

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try advanced NLP models (Naive Bayes, SVM, Random Forest)
- Use word embeddings (Word2Vec, GloVe)
- Apply deep learning models (LSTM, BERT)
- Build a web app using Streamlit or Flask
- Deploy the model as an API

## 📚 Learning Outcomes

Through this project, I learned:

- How to preprocess text data for NLP tasks
- How TF-IDF works for feature extraction
- How Logistic Regression performs in text classification
- How to evaluate classification models
- How to structure and document an ML project properly

## 🤝 Contributing

This project is part of my learning journey.
Feedback, suggestions, and improvements are welcome!

## 📬 Contact

- Gmail: [bahatibk72@gmail.com]

⭐ If you found this project interesting, feel free to star the repository!
