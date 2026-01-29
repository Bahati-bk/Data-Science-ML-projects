# 🟡 Gold Price Prediction Using Random Forest Regression

## 📌 Project Overview

This project focuses on predicting **gold prices** using a **Random Forest Regression** model based on historical financial data.

The goal of this project was to understand how ensemble regression models work, how financial indicators influence gold prices, and how machine learning can be used for forecasting real-world economic trends.

This project is part of my **learning journey in Data Science and Machine Learning**, where I apply ML techniques to real-world datasets to strengthen my analytical and modeling skills.

## 🎯 Problem Statement

Gold prices fluctuate due to various economic factors such as currency value, stock market performance, and global market trends.

The objective of this project is to:

> **Predict the price of gold using historical financial data and machine learning regression techniques.**

This is a **supervised learning regression problem**.

## 📂 Dataset

The dataset contains historical financial indicators related to gold prices.

### Features Include:

- Date
- SPX (S&P 500 Index)
- USO (United States Oil Fund Price)
- SLV (Silver Price)
- EUR/USD Exchange Rate

### Target Variable:

- Gold Price

## 🛠️ Technologies & Tools Used

- **Python**
- **NumPy** – numerical operations
- **Pandas** – data manipulation and preprocessing
- **Seaborn** – data visualization
- **Scikit-learn** – machine learning modeling and evaluation
- **Python script**

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading & Exploration

- Loaded the dataset using Pandas
- Checked data types and dataset structure
- Explored summary statistics
- Identified trends and correlations between variables

### 2️⃣ Data Preprocessing

- Checked for missing values
- Converted date columns where necessary
- Selected relevant features for prediction
- Ensured data was clean and consistent

### 3️⃣ Exploratory Data Analysis (EDA)

- Visualized relationships between gold prices and other financial indicators
- Observed how market trends influence gold price fluctuations
- Used correlation analysis to understand feature importance

### 4️⃣ Feature Selection

- Selected features that strongly influence gold price movement
- Reduced noise and improved model efficiency

### 5️⃣ Train-Test Split

- Divided the dataset into training and testing sets
- Ensured unbiased evaluation on unseen data

## 🌲 Model Selection: Random Forest Regression

### 📌 Why Random Forest?

Random Forest Regression was chosen because:

- It handles non-linear relationships well
- It is resistant to overfitting
- It works effectively on structured datasets
- It provides feature importance insights

### 6️⃣ Model Training

- Trained the Random Forest model on historical data
- Used multiple decision trees to improve prediction stability

### 7️⃣ Model Evaluation

The model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

These metrics help determine how well the model predicts gold prices.

## 📊 Results & Insights

- The Random Forest model showed strong predictive performance
- Financial indicators such as stock market trends and currency values influenced gold price predictions
- Feature importance analysis provided insights into which variables had the greatest impact

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/gold-price-prediction.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd gold-price-prediction
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Project

- Open the Jupyter Notebook and run all cells
  OR

```bash
python gold_price_prediction.py
```

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try other regression models such as XGBoost or Linear Regression
- Incorporate more financial indicators
- Use time-series forecasting models
- Deploy the model as a web application

## 📚 Learning Outcomes

Through this project, I learned:

- How regression models work in financial forecasting
- How ensemble learning improves prediction accuracy
- How to preprocess and analyze financial datasets
- How to evaluate regression models effectively
- How machine learning can be applied to economic trend prediction

## 🤝 Contributing

This project is part of my learning journey, and feedback or suggestions are welcome!

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

⭐ If you find this project helpful or interesting, feel free to star the repository!
