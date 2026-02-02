# 📧 Spam Mail Detection Using Logistic Regression

## 📌 Project Overview

This project focuses on **detecting spam emails** using **Logistic Regression**, a supervised machine learning algorithm for classification tasks.

The goal is to analyze email text data, extract meaningful features, and build a model that can automatically classify emails as **spam** or **not spam**.

This project is part of my **Data Science and Machine Learning learning journey**, where I apply real-world datasets to strengthen my skills in **Natural Language Processing (NLP), feature engineering, and predictive modeling**.

## 🎯 Problem Statement

Spam emails are a common problem for individuals and businesses. Automatically detecting spam is essential to prevent phishing attacks, scams, and cluttered inboxes.

The objective of this project is to:

> **Classify emails as spam or non-spam based on their textual content.**

This is a **binary classification problem**, where:

- 0 → Spam
- 1 → Not Spam

## 📂 Dataset Description

The dataset contains emails labeled as **spam** or **ham (not spam)**.

### Features Include:

- **Email Text**: The content of the email (input features)
- **Label**: Indicates if the email is spam or not (target variable)

Key characteristics:

- Text data requires preprocessing for machine learning
- Imbalanced classes may need attention

## 🛠️ Technologies & Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading

- Loaded the dataset using Pandas
- Examined structure, columns, and class distribution

### 2️⃣ Data Preprocessing

- Converted text to lowercase
- Removed punctuation, numbers, and special characters
- Tokenized text and removed stopwords
- Applied stemming or lemmatization
- Converted categorical labels to numerical (spam → 1, ham → 0)

Why this is done: Text data cannot be fed directly into ML algorithms, so preprocessing converts it into a usable form.

### 3️⃣ Feature Extraction

- Converted text into numeric vectors using:
  - **TF-IDF Vectorizer**

Why this is done: Machine learning models need numerical input. Vectorization transforms emails into feature vectors representing word frequency or importance.

### 4️⃣ Train-Test Split

- Split dataset into training and testing sets (e.g., 80/20)
- Ensured that both spam and ham emails were represented proportionally

Why this is done: To evaluate model performance on unseen data, ensuring unbiased results.

### 5️⃣ Model Selection: Logistic Regression

- Logistic Regression is suitable for binary classification
- Provides probability-based outputs for predictions
- Efficient and interpretable

### 6️⃣ Model Training

- Trained Logistic Regression on vectorized training data
- Learned patterns distinguishing spam from ham emails

### 7️⃣ Model Evaluation

The model was evaluated using:

- **Accuracy**
- **Precision, Recall, F1 Score**
- **Confusion Matrix**

Why: Spam detection is sensitive; false positives and false negatives have different impacts. Metrics like Precision and Recall provide a better picture than accuracy alone.

## 📊 Results & Insights

- The model achieved high classification accuracy
- Common spam keywords were identified as significant features
- Proper preprocessing (stopword removal, stemming) improved performance
- Vectorization method choice (CountVectorizer vs TF-IDF) influenced results

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/spam-mail-detection.git
```

### 2️⃣ Navigate to Project Folder

```bash
cd spam-mail-detection
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and execute all cells.

## 🔮 Future Improvements

- Try other classifiers: Random Forest, Naive Bayes, XGBoost
- Hyperparameter tuning
- Use word embeddings (Word2Vec, GloVe) for better feature representation
- Deploy as a spam filter web application
- Handle class imbalance with oversampling/undersampling

## 📚 Learning Outcomes

Through this project, I learned:

- Text preprocessing and NLP techniques
- Feature extraction for textual data
- Logistic Regression for classification
- Model evaluation metrics beyond accuracy
- Real-world applications of ML in email security

## ⚠️ Disclaimer

This project is for **educational purposes only** and is not intended for actual production spam filtering.

## 🤝 Contributing

This project is part of my learning journey. Suggestions, feedback, and improvements are welcome.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

I document my Data Science and ML journey, share tutorials, and explain concepts on my blog.

## 🌟 Support

⭐ If you found this project helpful, feel free to star the repository!
