# 🚢 Titanic Survival Prediction Using Logistic Regression

## 📌 Project Overview

This project focuses on predicting whether a passenger survived the Titanic disaster using **Logistic Regression**, a supervised machine learning algorithm used for classification tasks.

The goal of this project is to analyze passenger data and build a predictive model that determines survival chances based on factors such as age, gender, ticket class, and family relationships.

This project is part of my Data Science and Machine Learning learning journey, where I apply theoretical knowledge to real-world datasets to strengthen my analytical, preprocessing, and modeling skills.

## 🎯 Problem Statement

The Titanic disaster is one of the most well-known historical events, and analyzing passenger data can reveal patterns that influenced survival rates.

The objective of this project is to:

> **Predict whether a passenger survived or not based on demographic and travel information.**

This is a **binary classification problem**, where:

- 0 → Did Not Survive
- 1 → Survived

## 📂 Dataset Description

The dataset contains information about Titanic passengers, including demographic details and travel information.

### Features Include:

- PassengerId
- Pclass → Ticket class
- Name
- Sex
- Age
- SibSp → Number of siblings/spouses aboard
- Parch → Number of parents/children aboard
- Ticket
- Fare
- Cabin
- Embarked → Port of embarkation
- Survived → Target Variable

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
- Examined dataset structure
- Checked for missing values
- Reviewed data types

### 2️⃣ Data Cleaning

- Handled missing values in Age, Cabin, and Embarked columns
- Removed irrelevant features (e.g., PassengerId, Name, Ticket)
- Ensured data quality before modeling

### 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Survival distribution
- Gender vs survival rate
- Passenger class vs survival rate
- Age distribution
- Correlation between features

Key insights:

- Females had higher survival rates than males
- First-class passengers had better survival chances
- Younger passengers were more likely to survive

### 4️⃣ Data Preprocessing

- Converted categorical variables into numerical format:
  - Sex
  - Embarked

- Feature scaling applied where necessary
- Prepared dataset for machine learning

### 5️⃣ Feature & Target Separation

- Features (X) → Passenger attributes
- Target (Y) → Survival status

### 6️⃣ Train-Test Split

- Divided dataset into training and testing sets
- Ensured fair and unbiased evaluation

## 🤖 Model Selection: Logistic Regression

### 📌 Why Logistic Regression?

Logistic Regression was chosen because:

- Suitable for binary classification
- Easy to interpret
- Efficient and reliable
- Provides probability-based predictions

### 7️⃣ Model Training

- Trained Logistic Regression model using training data
- Model learned patterns affecting survival chances

### 8️⃣ Model Evaluation

The model was evaluated using:

- Accuracy Score

This metric helped measure:

- Prediction reliability
- Classification performance
- Model effectiveness

## 📊 Results & Insights

- Gender and passenger class strongly influenced survival
- Logistic Regression provided reliable baseline performance
- Proper data preprocessing significantly improved results

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/titanic-survival-prediction.git
```

### 2️⃣ Navigate to Project Folder

```
cd titanic-survival-prediction
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and execute all cells.

## 🔮 Future Improvements

- Try advanced classification models:
  - Random Forest
  - Gradient Boosting
  - XGBoost
- Hyperparameter tuning
- Feature engineering
- Model deployment as a web app

## 📚 Learning Outcomes

Through this project, I learned:

- Data cleaning and preprocessing
- Feature encoding techniques
- Exploratory data analysis
- Logistic Regression fundamentals
- Model evaluation methods
- Real-world application of machine learning

## ⚠️ Disclaimer

This project is for educational purposes only.

## 🤝 Contributing

This project is part of my learning journey. Suggestions and feedback are welcome.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

I regularly document my learning journey and share insights about Data Science and Machine Learning on my blog.

## 🌟 Support the Project

⭐ If you found this project helpful, feel free to star the repository!
