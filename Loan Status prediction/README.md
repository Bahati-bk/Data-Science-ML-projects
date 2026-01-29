# 🏦 Loan Status Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on building a **machine learning model** that predicts whether a loan application will be **Approved or Rejected** based on applicant and financial details.

The project was developed as part of my **learning journey in Data Science and Machine Learning**, with the goal of understanding how ML models are used in real-world financial decision-making systems.

Loan prediction systems help financial institutions:

- Reduce risk
- Automate decision-making
- Improve fairness and efficiency

## 🎯 Problem Statement

Loan approval is traditionally a manual and time-consuming process that depends on several factors such as income, credit history, and employment status.

The objective of this project is to:

> **Predict the loan approval status of an applicant using machine learning techniques.**

## 📂 Dataset

The dataset used contains information about loan applicants, including:

### Features (Examples)

- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Gender
- Marital Status
- Education
- Self Employment
- Property Area

### Target Variable

- `Loan_Status`
  - `1` → Loan Approved
  - `0` → Loan Rejected

The dataset is commonly used for educational purposes in classification problems.

## 🛠️ Technologies & Tools Used

- **Python**
- **NumPy** – numerical computations
- **Pandas** – data manipulation and analysis
- **Seaborn** – data visualization
- **Scikit-learn** – machine learning models & evaluation
- **Python script**

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading & Exploration

- Loaded the dataset using Pandas
- Inspected dataset shape, data types, and missing values
- Performed exploratory data analysis (EDA) to understand patterns and relationships

### 2️⃣ Data Cleaning & Preprocessing

- Handled missing values using appropriate strategies
- Converted categorical variables into numerical format using encoding techniques
- Removed unnecessary or redundant features

### 3️⃣ Feature Selection

- Selected relevant features that contribute most to loan approval
- Improved model performance and reduced overfitting

### 4️⃣ Train-Test Split

- Split the dataset into training and testing sets
- Ensured the model is evaluated on unseen data

### 5️⃣ Model Selection

Trained and evaluated one machine learning algorithm:

- Support Vector Machine (SVM)

### 6️⃣ Model Training

- Trained the selected model using the training dataset
- Tuned hyperparameters where necessary

### 7️⃣ Model Evaluation

Evaluated the model using:

- Accuracy Score

These metrics help assess how well the model predicts loan approval status.

## 📊 Results & Performance

- The trained model achieved good performance in predicting loan approval status
- Results indicate that features like **credit history and income** play a significant role in loan approval decisions

> Performance may vary depending on the model and preprocessing techniques used.

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/loan-status-prediction.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd loan-status-prediction
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Project

- Open the Jupyter Notebook and run all cells
  **OR**
- Run the Python script:

```bash
python loan_prediction.py
```

## 🔮 Future Improvements

- Perform hyperparameter tuning using GridSearchCV
- Handle class imbalance using resampling techniques
- Try advanced models like XGBoost or LightGBM
- Deploy the model using Streamlit or Flask
- Add explainability using SHAP or feature importance plots

## 📚 Learning Outcomes

Through this project, I learned:

- How to clean and preprocess structured data
- How to handle categorical variables in ML
- How different ML models perform on classification problems
- How to evaluate and compare machine learning models
- How ML is applied in financial decision-making systems

## 🤝 Contributing

This project is part of my learning journey.
Suggestions, improvements, and feedback are welcome!

## 📬 Contact

- Gmail: [bahatibk72@gmail.com]

⭐ If you find this project helpful or interesting, feel free to star the repository!
