# 🚗 Car Price Prediction Using Linear Regression & Lasso Regression

## 📌 Project Overview

This project focuses on predicting the **selling price of cars** using machine learning techniques, specifically **Linear Regression** and **Lasso Regression**.

The goal of this project was to understand how regression models work, how feature selection affects performance, and how regularization techniques like Lasso help prevent overfitting.

This project is part of my **learning journey in Data Science and Machine Learning**, where I explore real-world datasets and apply ML techniques to solve practical problems.

## 🎯 Problem Statement

Car prices depend on several factors such as:

- Brand
- Age of the car
- Fuel type
- Transmission
- Mileage
- Engine capacity
- Number of previous owners

The objective of this project is to:

> **Predict the price of a car based on its features using regression models.**

This is a **supervised learning regression problem**.

## 📂 Dataset

The dataset contains information about used cars and their features.

### Features Include:

- Car Name / Company
- Year of Purchase
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission Type
- Owner Count

### Target Variable:

- `Selling_Price`

## 🛠️ Technologies & Tools Used

- **Python**
- **NumPy** – numerical operations
- **Pandas** – data cleaning and analysis
- **Matplotlib / Seaborn** – data visualization
- **Scikit-learn** – machine learning models & evaluation
- **Python script**

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading & Exploration

- Loaded the dataset using Pandas
- Checked dataset shape, data types, and summary statistics
- Identified categorical and numerical features
- Explored relationships between features and car prices

### 2️⃣ Data Cleaning & Preprocessing

- Checked for missing values
- Converted categorical variables into numerical format using encoding
- Removed unnecessary columns
- Ensured all features were suitable for regression models

### 3️⃣ Exploratory Data Analysis (EDA)

- Visualized relationships between features and selling price
- Observed trends such as:
  - Newer cars generally have higher prices
  - Lower mileage often leads to higher resale value
  - Fuel type influences pricing

### 4️⃣ Feature Selection

- Selected features that significantly influence car prices
- Reduced noise and improved model performance

### 5️⃣ Train-Test Split

- Divided the dataset into training and testing sets
- Ensured the model was evaluated on unseen data

## 🤖 Model 1: Linear Regression

### 📌 Why Linear Regression?

Linear Regression:

- Is simple and interpretable
- Provides a baseline model
- Shows relationships between features and target

### Training

- Trained the Linear Regression model using training data
- Predicted car prices on test data

### Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## 🌟 Model 2: Lasso Regression

### 📌 Why Lasso Regression?

Lasso Regression:

- Adds regularization
- Reduces overfitting
- Performs automatic feature selection
- Helps simplify the model

### Training

- Applied Lasso Regression with tuned parameters
- Compared performance with Linear Regression

## 📊 Model Comparison

| Model             | Strength                                             |
| ----------------- | ---------------------------------------------------- |
| Linear Regression | Simple, interpretable, good baseline                 |
| Lasso Regression  | Handles overfitting, reduces less important features |

Lasso helped improve generalization by penalizing less useful features.

## 🚀 Results

- Both models performed well in predicting car prices
- Lasso Regression showed better control over overfitting
- Important factors influencing price included:
  - Year of purchase
  - Present price
  - Kilometers driven
  - Fuel type

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try Ridge Regression and ElasticNet
- Use more advanced models like Random Forest or XGBoost
- Deploy as a web application using Streamlit
- Add model explainability techniques

## 📚 Learning Outcomes

Through this project, I learned:

- How regression models work
- Differences between Linear and Lasso Regression
- Importance of feature selection
- How regularization improves model performance
- How ML can be applied to price prediction problems

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/car-price-prediction.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd car-price-prediction
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Project

- Open the Jupyter Notebook and run all cells
  OR

```bash
python car_price_prediction.py
```

## 🤝 Contributing

This project is part of my learning journey, and I welcome feedback, suggestions, and improvements.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

⭐ If you find this project interesting, feel free to star the repository!
