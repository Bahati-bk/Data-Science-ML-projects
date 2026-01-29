# 🍷 Wine Quality Prediction Using Random Forest Classifier (Red Wine)

## 📌 Project Overview

This project focuses on predicting the **quality of red wine** based on its **physicochemical properties** using a **Random Forest Classifier**.

The project was built as part of my **learning journey in Data Science and Machine Learning**, with the goal of understanding how ensemble models like Random Forest work on real-world tabular data and how machine learning can be applied to quality control problems.

Wine quality prediction helps:

- Standardize quality assessment
- Reduce human subjectivity
- Support data-driven decision-making in production

## 🎯 Problem Statement

Wine quality is influenced by several chemical characteristics such as acidity, alcohol content, and sulphates. Manually evaluating wine quality can be subjective and inconsistent.

The objective of this project is to:

> **Predict whether a red wine is of good quality or not using machine learning.**

This is a **supervised classification problem**.

## 📂 Dataset

The dataset used is the **Red Wine Quality Dataset**, which contains physicochemical properties of red wine samples.

### Features

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target Variable

- `quality` (original score between 0–10)

For classification purposes, the target was transformed into:

- `1` → Good Quality Wine (quality ≥ 7)
- `0` → Not Good Quality Wine (quality < 7)

## 🛠️ Technologies & Tools Used

- **Python**
- **Pandas** – data manipulation and analysis
- **NumPy** – numerical computations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – machine learning models & evaluation
- **Python script**

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading & Exploration

- Loaded the dataset using Pandas
- Inspected data types, feature distributions, and dataset shape
- Checked for missing values and class distribution

### 2️⃣ Exploratory Data Analysis (EDA)

- Analyzed summary statistics
- Observed how chemical properties vary across wine samples
- Examined class imbalance in wine quality labels

### 3️⃣ Data Preprocessing

- Converted the wine quality score into binary classes (good / not good)
- Separated features and target variable
- No scaling was required since Random Forest is not sensitive to feature scaling

### 4️⃣ Train-Test Split

- Split the dataset into training and testing sets
- Ensured the model was evaluated on unseen data

### 5️⃣ Model Selection

The **Random Forest Classifier** was chosen because:

- It handles non-linear relationships well
- It performs strongly on tabular numerical data
- It reduces overfitting compared to single decision trees
- It provides feature importance for interpretability

### 6️⃣ Model Training

- Trained the Random Forest model on the training data
- Used multiple decision trees to improve prediction robustness

### 7️⃣ Model Evaluation

The model was evaluated using:

- Accuracy Score

These metrics help assess how well the model distinguishes between good and poor-quality wine.

## 📊 Results & Insights

- The Random Forest model achieved strong performance in predicting wine quality
- Features such as **alcohol content, sulphates, and acidity** were found to be important contributors to wine quality
- Feature importance analysis helped interpret model decisions

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/wine-quality-prediction.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd wine-quality-prediction
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
python wine_quality_prediction.py
```

## 🔮 Future Improvements

- Perform hyperparameter tuning using GridSearchCV
- Extend to multi-class classification (low, medium, high quality)
- Apply cross-validation for better generalization
- Compare Random Forest with other models (Logistic Regression, XGBoost)
- Deploy the model using Streamlit or Flask

## 📚 Learning Outcomes

Through this project, I learned:

- How ensemble models like Random Forest work
- How to preprocess and analyze structured datasets
- How to evaluate classification models beyond accuracy
- How to interpret feature importance
- How machine learning can be applied to quality control problems

## 🤝 Contributing

This project is part of my learning journey.
Feedback, suggestions, and improvements are welcome!

## 📬 Contact

- Gmail: [bahatibk72@gmail.com]
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

⭐ If you find this project interesting or helpful, feel free to star the repository!
