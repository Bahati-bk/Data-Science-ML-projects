# ❤️ Heart Disease Prediction Using Logistic Regression

## 📌 Project Overview

This project focuses on predicting whether a person has heart disease using **Logistic Regression**, based on medical and diagnostic features.

The goal of this project was to understand:

- how classification algorithms work
- how to preprocess medical data
- how machine learning can assist in healthcare decision-making

This project is part of my **learning journey in Data Science and Machine Learning**, where I apply ML techniques to real-world datasets to strengthen my analytical and modeling skills.

## 🎯 Problem Statement

Heart disease is one of the leading causes of death worldwide. Early detection can help in better treatment and prevention.

The objective of this project is to:

> **Predict whether a patient has heart disease based on clinical features using Logistic Regression.**

This is a **supervised machine learning classification problem**.

## 📂 Dataset Description

The dataset contains medical attributes of patients that help determine the presence of heart disease.

### Features (Columns)

- **Unnamed: 0** – Index column
- **Age** – Age of the patient
- **Sex** – Gender of the patient
- **ChestPain** – Type of chest pain
- **RestBP** – Resting blood pressure
- **Chol** – Serum cholesterol level
- **Fbs** – Fasting blood sugar
- **RestECG** – Resting electrocardiographic results
- **MaxHR** – Maximum heart rate achieved
- **ExAng** – Exercise-induced angina
- **Oldpeak** – ST depression induced by exercise
- **Slope** – Slope of peak exercise ST segment
- **Ca** – Number of major vessels colored by fluoroscopy
- **Thal** – Thalassemia type
- **AHD** – Target variable (Heart Disease: Yes/No)

## 🎯 Target Variable

- **AHD**
  - `0` → No Heart Disease
  - `1` → Heart Disease Present

## 🛠️ Technologies & Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Python

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading

- Imported dataset using Pandas
- Inspected structure, data types, and summary statistics
- Checked for missing or inconsistent values

### 2️⃣ Data Cleaning & Preprocessing

To prepare the data for machine learning, categorical values were converted into numerical format.

### Encoding Target Variable

```
df.replace({'AHD':{'No': 0, 'Yes': 1}}, inplace=True)
```

### Encoding Thal Feature

```
df.replace({'Thal':{'fixed': 0, 'normal': 1, 'reversable': 2}}, inplace=True)
```

### Encoding Chest Pain Type

```
df.replace({'ChestPain':{'typical': 0, 'asymptomatic': 1, 'nonanginal': 2, 'nontypical': 3}}, inplace=True)
```

This step ensures the model can interpret categorical values numerically.

### 3️⃣ Exploratory Data Analysis (EDA)

- Analyzed distribution of features
- Identified relationships between variables
- Checked correlations to understand feature importance

### 4️⃣ Feature Selection

- Removed unnecessary columns
- Selected relevant medical indicators for prediction

### 5️⃣ Train-Test Split

- Divided dataset into:
  - Training data
  - Testing data

- Ensured unbiased model evaluation

## 🤖 Model Selection: Logistic Regression

### 📌 Why Logistic Regression?

Logistic Regression was chosen because:

- It is simple and interpretable
- Works well for binary classification
- Efficient for small-to-medium datasets
- Provides probability-based predictions

### 6️⃣ Model Training

- Trained Logistic Regression on training data
- Learned relationships between medical features and heart disease

### 7️⃣ Model Evaluation

The model was evaluated using:

- Accuracy Score

This metric helps determine how well the model predicts heart disease.

## 📊 Results & Insights

- Logistic Regression performed effectively in classifying patients
- Certain features such as chest pain type, maximum heart rate, and cholesterol levels showed strong influence on predictions
- The model demonstrates how machine learning can support early disease detection

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/heart-disease-prediction.git
```

### 2️⃣ Navigate to the Project Folder

```
cd heart-disease-prediction
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and run all cells.

## 🔮 Future Improvements

- Try advanced models like Random Forest or XGBoost
- Perform hyperparameter tuning
- Use cross-validation
- Deploy the model as a web app
- Use larger healthcare datasets

## 📚 Learning Outcomes

Through this project, I learned:

- How classification algorithms work
- How to preprocess categorical medical data
- How Logistic Regression predicts probabilities
- How to evaluate classification models
- How machine learning can support healthcare analytics

## 🤝 Contributing

This project is part of my learning journey, and suggestions or feedback are welcome.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

⭐ If you find this project interesting, feel free to star the repository!
