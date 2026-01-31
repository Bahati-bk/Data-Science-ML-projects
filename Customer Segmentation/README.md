# 🧠 Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project focuses on **Customer Segmentation** using **K-Means Clustering**, an unsupervised machine learning algorithm used to group similar data points together.

The goal is to analyze customer data and identify distinct customer groups based on their purchasing behavior. These insights can help businesses create targeted marketing strategies, improve customer experience, and increase profitability.

This project is part of my Data Science and Machine Learning learning journey, where I apply theoretical knowledge to real-world datasets to strengthen my analytical and problem-solving skills.

## 🎯 Problem Statement

Businesses often have large amounts of customer data but lack insights into customer behavior patterns.

The objective of this project is to:

> **Segment customers into different groups based on shared characteristics using K-Means Clustering.**

This is an **unsupervised learning problem**, meaning there is no labeled target variable.

## 📂 Dataset Description

The dataset contains customer information such as demographics and spending behavior.

### Features Include:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

These features help identify patterns in customer behavior.

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
- Checked data structure and summary statistics
- Ensured no major inconsistencies in the dataset

### 2️⃣ Data Cleaning

- Checked for missing values
- Removed unnecessary columns (e.g., Customer ID)
- Ensured data was ready for clustering

### 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis to understand:

- Age distribution
- Income distribution
- Spending patterns
- Relationship between income and spending score

Key insights:

- Customers with similar income levels often showed similar spending patterns.
- Certain age groups demonstrated distinct purchasing behaviors.

### 4️⃣ Feature Selection

Selected relevant features for clustering:

- Annual Income
- Spending Score

These features were chosen because they directly influence customer purchasing behavior.

### 5️⃣ Finding the Optimal Number of Clusters

Used the **Elbow Method** to determine the ideal number of clusters:

- Plotted Within-Cluster Sum of Squares (WCSS)
- Identified the "elbow point" where additional clusters no longer significantly reduce WCSS

## 🤖 Model Selection: K-Means Clustering

### 📌 Why K-Means?

K-Means was chosen because:

- It is simple and efficient
- Works well for customer segmentation
- Helps identify natural groupings in data
- Easy to visualize and interpret

### 6️⃣ Model Training

- Applied K-Means clustering algorithm
- Assigned customers to different clusters
- Each cluster represents a unique customer segment

### 7️⃣ Data Visualization

Visualized customer segments using scatter plots:

- Different colors represented different clusters
- Centroids highlighted the center of each cluster
- Helped interpret customer group behavior

## 📊 Results & Insights

The model successfully segmented customers into distinct groups such as:

- High income – high spending
- High income – low spending
- Low income – high spending
- Low income – low spending

These insights can help businesses:

- Create targeted marketing campaigns
- Improve customer retention strategies
- Optimize product offerings

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/customer-segmentation-kmeans.git
```

### 2️⃣ Navigate to Project Folder

```
cd customer-segmentation-kmeans
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open Jupyter Notebook and run all cells.

## 🔮 Future Improvements

- Try other clustering algorithms:
  - Hierarchical Clustering
  - DBSCAN

- Add more customer features
- Build a dashboard for visualization
- Deploy as a web application
- Automate cluster updates with new data

## 📚 Learning Outcomes

Through this project, I learned:

- The difference between supervised and unsupervised learning
- How clustering algorithms work
- Feature selection for segmentation
- Data visualization techniques
- Interpreting clustering results
- Real-world business applications of machine learning

## 💼 Business Value

Customer segmentation helps organizations:

- Improve marketing efficiency
- Personalize customer experiences
- Increase revenue through targeted campaigns
- Make data-driven business decisions

## 🤝 Contributing

This project is part of my learning journey. Feedback, suggestions, and improvements are welcome.

## 📬 Contact

- Gmail: bahatibk72@gmail.com
- Blog: [https://godfident-data.hashnode.dev](https://godfident-data.hashnode.dev)

I regularly document my learning journey and share insights about Data Science and Machine Learning on my blog.

## ⭐️ Support

⭐ If you found this project helpful, feel free to star the repository!
