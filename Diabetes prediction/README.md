# 🩺 Diabetes Prediction Using Support Vector Machine (SVM)

## 📌 Project Overview

This project is a **machine learning classification model** that predicts whether a person is **diabetic or non-diabetic** based on medical diagnostic features.  
The model is built using **Support Vector Machine (SVM)**, a powerful supervised learning algorithm commonly used for classification tasks.

This project was developed as part of my **learning journey in Data Science and Machine Learning**, focusing on:

- Data preprocessing
- Model training and evaluation
- Understanding how SVM works in real-world problems

---

## 🎯 Problem Statement

Diabetes is a chronic disease that affects millions of people worldwide. Early detection can help individuals manage the condition better and prevent severe complications.

The goal of this project is to:

> **Build a machine learning model that predicts whether a person has diabetes based on health-related features.**

---

## 📂 Dataset

The dataset used in this project contains medical information such as:

- Number of pregnancies
- Glucose level
- Blood pressure
- Skin thickness
- Insulin level
- Body Mass Index (BMI)
- Diabetes pedigree function
- Age

**Target Variable:**

- `0` → Non-diabetic
- `1` → Diabetic

> The dataset is commonly used for educational and learning purposes in machine learning classification tasks.

---

## 🛠️ Technologies & Tools Used

- **Python**
- **NumPy** – numerical computations
- **Pandas** – data manipulation and analysis
- **Scikit-learn** – machine learning modeling
- **Python script**

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Collection

- Loaded the dataset into a Pandas DataFrame.
- Inspected data structure, shape, and basic statistics.

### 2️⃣ Data Preprocessing

- Checked for missing or inconsistent values.
- Split the data into **features (X)** and **target (y)**.
- Applied **feature scaling** using `StandardScaler` to improve SVM performance.

### 3️⃣ Train-Test Split

- Split the dataset into training and testing sets using `train_test_split`.
- This helps evaluate how well the model generalizes to unseen data.

### 4️⃣ Model Selection

- Used **Support Vector Machine (SVM)** with a linear kernel for classification.
- SVM was chosen because it performs well in high-dimensional spaces and classification problems.

### 5️⃣ Model Training

- Trained the SVM classifier on the training dataset.

### 6️⃣ Model Evaluation

- Evaluated the model using accuracy score.
- Compared predictions with actual values to assess performance.

---

## 📊 Model Performance

- **Evaluation Metric Used:** Accuracy Score
- The trained SVM model achieved satisfactory accuracy on the test dataset.

> Further improvements can be made by tuning hyperparameters or trying different kernels.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/diabetes-prediction-svm.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd diabetes-prediction-svm
```

### 3️⃣ Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook / Script

- Open the Jupyter Notebook and run all cells
  **OR**
- Run the Python script:

```bash
python diabetes_prediction.py
```

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try different SVM kernels (RBF, polynomial)
- Compare performance with other ML models (Logistic Regression, Random Forest, KNN)
- Build a simple web app using Flask or Streamlit
- Deploy the model on cloud platforms (e.g., Google Cloud, AWS)

---

## 📚 Learning Outcomes

Through this project, I learned:

- How to preprocess data for machine learning
- How Support Vector Machines work for classification
- Importance of feature scaling
- How to evaluate ML models
- How to structure and document an ML project properly

---

## 🤝 Contributing

This project is part of my learning journey.
Suggestions, improvements, and feedback are always welcome!

---

## 📬 Contact

If you'd like to connect or collaborate:

- Gmail: [bahatibk72@gmail.com]
- LinkedIn: [Bahati Brenda Kizito]

---

⭐ If you found this project helpful or interesting, consider giving it a star!
