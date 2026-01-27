# 🏡 California Housing Price Prediction using XGBoost

This project builds a **machine learning regression model** to predict housing prices in California using the **XGBoost** algorithm.
It follows a complete ML workflow: **EDA → preprocessing → modeling → evaluation**.

## 📌 Project Overview

- **Problem type:** Regression
- **Goal:** Predict median house values based on socioeconomic and geographic features
- **Dataset:** California Housing dataset (from `sklearn.datasets`)
- **Model used:** XGBoost Regressor

## 📊 Dataset Description

The dataset contains information collected from the 1990 California census.
Each row represents a housing block group.

### Features

| Feature      | Description                  |
| ------------ | ---------------------------- |
| `MedInc`     | Median income in block group |
| `HouseAge`   | Median house age             |
| `AveRooms`   | Average number of rooms      |
| `AveBedrms`  | Average number of bedrooms   |
| `Population` | Block group population       |
| `AveOccup`   | Average house occupancy      |
| `Latitude`   | Latitude                     |
| `Longitude`  | Longitude                    |

### Target

- `MedHouseVal` → Median house value (in $100,000s)

## 🔍 Exploratory Data Analysis (EDA)

The following steps were performed during EDA:

- Checked dataset shape and data types
- Verified missing values (none found)
- Analyzed summary statistics
- Visualized feature distributions
- Examined correlation between features and target
- Plotted target variable distribution

## ⚙️ Model Pipeline

### 1. Data Preparation

- Split dataset into features (`X`) and target (`y`)
- Performed an 80/20 train-test split

### 2. Model Selection

- Used **XGBoost Regressor**, a gradient boosting model based on decision trees

### 3. Training

- Model trained on the training set using optimized hyperparameters

### 4. Evaluation

- Evaluated using:
  - **RMSE (Root Mean Squared Error)**
  - **R² Score**

## 🧠 Model Configuration

Key hyperparameters used:

- `n_estimators = 300`
- `learning_rate = 0.05`
- `max_depth = 5`
- `subsample = 0.8`
- `colsample_bytree = 0.8`
- `random_state = 42`

## 📈 Results

- The model achieves a **strong R² score**, indicating it captures most of the variance in housing prices.
- Median income (`MedInc`) is the most influential feature.
- Geographic features (`Latitude`, `Longitude`) also play a significant role.

## 📌 Feature Importance

XGBoost’s feature importance shows which variables contribute most to predictions, helping interpret model behavior.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

## 🚀 How to Run This Project

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or script step by step

## 📂 Project Structure (Suggested)

```
├── data/
├── notebooks/
│   └── california_housing_xgboost.ipynb
├── README.md
├── requirements.txt
```

## 🌱 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Model comparison with Linear Regression, Random Forest
- Model persistence (saving/loading model)
- Deployment as a web app or API
