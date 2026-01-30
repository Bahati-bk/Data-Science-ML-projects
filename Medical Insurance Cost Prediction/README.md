# 🏥 Medical Insurance Cost Prediction Using Linear Regression

## 📌 Project Overview

This project focuses on predicting **medical insurance costs** using **Linear Regression**, a supervised machine learning algorithm used for regression problems.

The goal of this project is to analyze how different personal and lifestyle factors influence medical insurance charges and build a model that can estimate insurance costs accurately.

This project is part of my learning journey in **Data Science and Machine Learning**, where I apply theoretical concepts to real-world datasets to strengthen my analytical and modeling skills.

## 🎯 Problem Statement

Medical insurance companies determine charges based on several factors such as age, BMI, smoking habits, and region.

The objective of this project is to:

> **Predict medical insurance costs based on personal attributes using Linear Regression.**

This is a **regression problem**, where the target variable is continuous.

## 📂 Dataset Description

The dataset contains demographic and health-related attributes that influence insurance charges.

### Features Include:

- **Age** → Age of the individual
- **Sex** → Gender
- **BMI** → Body Mass Index
- **Children** → Number of dependents
- **Smoker** → Smoking status
- **Region** → Residential area
- **Charges** → Medical insurance cost (Target Variable)

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
- Viewed structure and summary statistics
- Checked for missing values

### 2️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Distribution of insurance charges
- Impact of smoking on insurance cost
- Relationship between BMI and charges
- Age vs insurance cost trends
- Correlation between features

Key Insight:

- Smokers generally have significantly higher insurance charges.
- Age and BMI also influence medical costs.

### 3️⃣ Data Preprocessing

- Checked for null or missing values
- Converted categorical variables into numerical format:
  - Sex
  - Smoker
  - Region

- Prepared dataset for machine learning

### 4️⃣ Feature & Target Separation

- Features (X) → All independent variables
- Target (Y) → Insurance Charges

### 5️⃣ Train-Test Split

- Split data into training and testing sets
- Ensured unbiased evaluation of the model

## 🤖 Model Selection: Linear Regression

### 📌 Why Linear Regression?

Linear Regression was chosen because:

- It is simple and interpretable
- Works well for predicting continuous values
- Helps understand relationships between variables
- Serves as a strong baseline model

### 6️⃣ Model Training

- Trained the Linear Regression model using training data
- Model learned patterns between personal attributes and insurance costs

### 7️⃣ Model Evaluation

The model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

These metrics help measure:

- Prediction accuracy
- Model reliability
- Error margins

## 📊 Results & Insights

- Smoking status has the strongest impact on insurance cost
- Age and BMI are also significant predictors
- Linear Regression provided a good baseline performance
- The model can estimate insurance costs reasonably well

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/medical-insurance-cost-prediction.git
```

### 2️⃣ Navigate to Project Folder

```
cd medical-insurance-cost-prediction
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and execute all cells.

## 🔮 Future Improvements

- Use advanced regression models:
  - Random Forest Regression
  - Gradient Boosting
  - XGBoost
- Perform feature engineering
- Hyperparameter tuning
- Deploy as a web app for cost estimation

## 📚 Learning Outcomes

Through this project, I learned:

- How regression models work
- Data preprocessing techniques
- Exploratory Data Analysis skills
- Feature encoding methods
- Model evaluation for regression tasks
- Real-world applications of machine learning in healthcare

## 🤝 Contributing

This project is part of my learning journey. Suggestions, improvements, and feedback are welcome.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

⭐ If you found this project helpful, feel free to star the repository!
