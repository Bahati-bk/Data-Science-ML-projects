# 🛒 Big Mart Sales Prediction Using XGBoost Regression

## 📌 Project Overview

This project focuses on predicting product sales in Big Mart stores using **XGBoost Regression**, an advanced machine learning algorithm known for high performance and efficiency.

The objective is to analyze historical sales data, understand the factors influencing product sales, and build a predictive model that can accurately estimate future sales.

This project is part of my learning journey in **Data Science and Machine Learning**, where I apply real-world datasets to strengthen my skills in data preprocessing, feature engineering, and predictive modeling.

## 🎯 Problem Statement

Retail businesses need accurate sales predictions to manage inventory, plan marketing strategies, and maximize profits.

The goal of this project is to:

> **Predict the sales of products at Big Mart outlets based on product attributes and store details.**

This is a **regression problem**, where the target variable (sales) is continuous.

## 📂 Dataset Description

The dataset contains sales data of products across different Big Mart outlets.

### Features Include:

- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type
- Item Outlet Sales (Target Variable)

## 🛠️ Technologies & Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading

- Loaded dataset using Pandas
- Examined dataset structure
- Checked for missing values
- Reviewed data types

### 2️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Distribution of sales
- Relationship between item price and sales
- Outlet characteristics impact
- Correlation between features

Key insights:

- Item MRP strongly influences sales
- Outlet type and size affect product performance
- Some features required cleaning and transformation

### 3️⃣ Data Cleaning

- Handled missing values
- Standardized inconsistent categories
- Removed or corrected anomalies
- Ensured data quality before modeling

### 4️⃣ Feature Engineering

- Converted categorical variables into numerical format
- Encoded outlet and item categories
- Created meaningful feature relationships
- Improved dataset usability for machine learning

### 5️⃣ Feature & Target Separation

- Features (X) → Independent variables
- Target (Y) → Item Outlet Sales

### 6️⃣ Train-Test Split

- Split data into training and testing sets
- Ensured fair evaluation of model performance

## 🤖 Model Selection: XGBoost Regression

### 📌 Why XGBoost?

XGBoost was chosen because:

- High predictive accuracy
- Handles missing values effectively
- Reduces overfitting through regularization
- Efficient and scalable
- Works well with structured data

### 7️⃣ Model Training

- Trained XGBoost Regressor on training data
- Model learned patterns affecting sales
- Optimized performance through parameter tuning

### 8️⃣ Model Evaluation

The model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

These metrics helped assess:

- Prediction accuracy
- Model reliability
- Error margins

## 📊 Results & Insights

- Item price is one of the strongest predictors of sales
- Outlet type significantly affects product performance
- XGBoost provided better performance compared to basic regression models
- Feature engineering improved prediction accuracy

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/big-mart-sales-prediction.git
```

### 2️⃣ Navigate to Project Folder

```
cd big-mart-sales-prediction
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and execute all cells.

## 🔮 Future Improvements

- Hyperparameter tuning
- Try other regression models
  - Random Forest
  - Gradient Boosting
- Build a web app for sales prediction
- Deploy model using Flask or Streamlit

## 📚 Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Feature engineering methods
- Regression modeling
- Importance of EDA
- Model evaluation metrics
- How XGBoost improves prediction performance

## 🤝 Contributing

This project is part of my learning journey. Suggestions, feedback, and improvements are welcome.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

⭐ If you found this project helpful, feel free to star the repository!
