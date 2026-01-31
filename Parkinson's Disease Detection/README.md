# 🧠 Parkinson’s Disease Prediction Using Support Vector Machine (SVM)

## 📌 Project Overview

This project focuses on predicting whether a person has **Parkinson’s Disease** using a **Support Vector Machine (SVM)** classification model. Parkinson’s Disease is a neurological disorder that affects movement, and early detection can play a crucial role in medical intervention.

The goal of this project is to analyze biomedical voice measurements and build a machine learning model that can accurately classify whether a person has Parkinson’s Disease or not.

This project is part of my Data Science and Machine Learning learning journey, where I apply theoretical knowledge to real-world healthcare datasets to strengthen my skills in data preprocessing, feature analysis, and model building.

## 🎯 Problem Statement

Parkinson’s Disease is often difficult to diagnose in its early stages. Machine learning can assist in detecting patterns that may not be obvious through traditional analysis.

The objective of this project is to:

> **Predict whether a person has Parkinson’s Disease based on biomedical voice measurements using an SVM classifier.**

This is a **binary classification problem**, where:

- 0 → Healthy
- 1 → Parkinson’s Disease

## 📂 Dataset Description

The dataset consists of biomedical voice measurements from individuals, some diagnosed with Parkinson’s Disease.

### Features Include:

- Various vocal frequency measures
- Signal-to-noise ratios
- Voice amplitude variations
- Nonlinear dynamical complexity measures
- Status (Target Variable)

These features help detect subtle voice changes associated with Parkinson’s Disease.

## 🛠️ Technologies & Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading

- Loaded dataset using Pandas
- Checked data structure
- Reviewed summary statistics
- Identified feature types

### 2️⃣ Data Preprocessing

- Checked for missing values
- Ensured data consistency
- Separated features and target variable
- Normalized data for better SVM performance

### 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Feature distributions
- Class balance
- Correlation between variables
- Patterns in voice measurements

Key Insight:

- Some voice features show noticeable differences between healthy individuals and Parkinson’s patients.

### 4️⃣ Feature & Target Separation

- Features (X) → Voice measurement attributes
- Target (Y) → Status (Parkinson’s or Healthy)

### 5️⃣ Data Scaling

Feature scaling was applied because:

- SVM is sensitive to feature magnitude
- Scaling improves model performance
- Ensures fair comparison among features

## 🤖 Model Selection: Support Vector Machine (SVM)

### 📌 Why SVM?

SVM was chosen because:

- Effective for high-dimensional data
- Works well for classification problems
- Helps create a clear decision boundary
- Performs well with smaller datasets

### 6️⃣ Train-Test Split

- Divided dataset into training and testing sets
- Ensured unbiased model evaluation

### 7️⃣ Model Training

- Trained SVM classifier using training data
- Model learned patterns distinguishing healthy individuals from Parkinson’s patients

### 8️⃣ Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision & Recall

These metrics helped assess:

- Prediction reliability
- Model performance
- Classification effectiveness

## 📊 Results & Insights

- The SVM model successfully classified individuals with good accuracy
- Certain voice measurements strongly contributed to prediction
- Feature scaling improved model performance

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/parkinsons-disease-prediction.git
```

### 2️⃣ Navigate to Project Folder

```
cd parkinsons-disease-prediction
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and execute all cells.

## 🔮 Future Improvements

- Try other classification models:
  - Random Forest
  - Logistic Regression
  - Neural Networks

- Hyperparameter tuning
- Feature selection techniques
- Deploy as a web application
- Improve dataset size for better generalization

## 📚 Learning Outcomes

Through this project, I learned:

- Data preprocessing for healthcare datasets
- Feature scaling importance
- How SVM works
- Model evaluation techniques
- Real-world application of machine learning in medical diagnosis

## ⚠️ Disclaimer

This project is for educational purposes only and is **not intended for medical diagnosis**.

## 🤝 Contributing

This project is part of my learning journey. Suggestions and feedback are welcome.

## 📬 Contact

- GitHub: [Your GitHub Link]
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

I regularly document my learning journey and share insights about Data Science and Machine Learning on my blog.

## 🌟 Support the Project

⭐ If you found this project helpful, feel free to star the repository!
