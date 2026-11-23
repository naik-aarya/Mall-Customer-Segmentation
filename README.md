# Mall Customer Segmentation Using K-Means Clustering

## 1. Project Overview

This project focuses on segmenting mall customers based on their annual income and spending behaviour using the K-Means Clustering algorithm.

The objective is to identify different customer groups and understand their purchasing patterns to support better business and marketing decisions.

## 2. Problem Statement

Customers have different income levels and spending habits. Understanding these differences helps businesses develop targeted marketing strategies and improve customer satisfaction.

This project applies unsupervised machine learning to group customers into meaningful segments based on their characteristics.

## 3. Objectives

- Perform Exploratory Data Analysis (EDA).
- Analyze customer demographics and spending behaviour.
- Apply K-Means Clustering.
- Find the optimal number of clusters using the Elbow Method.
- Evaluate clustering performance using the Silhouette Score.
- Visualize and interpret customer segments.

## 4. Dataset Description

The project uses the Mall Customers dataset.

**Dataset Features:**

- CustomerID: Unique customer identification number.
- Gender: Customer gender.
- Age: Customer age.
- Annual Income (k$): Annual income in thousands of dollars.
- Spending Score (1–100): Score assigned based on customer spending behaviour.

## 5. Technologies and Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 6. Machine Learning Algorithm

**K-Means Clustering**

K-Means is an unsupervised machine learning algorithm that groups similar data points into K clusters based on their distance from cluster centroids.

It aims to minimize the within-cluster sum of squares (WCSS).

## 7. Project Workflow

1. Data Collection
2. Data Loading
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Optimal Cluster Selection using the Elbow Method
7. K-Means Clustering
8. Silhouette Score Evaluation
9. Customer Cluster Visualization
10. Cluster Interpretation

## 8. Model Evaluation

The clustering model is evaluated using:

- **Elbow Method:** Helps identify an appropriate number of clusters using WCSS.
- **Silhouette Score:** Measures how well-separated and cohesive the clusters are.

## 9. Business Applications

- Identify high-value customers.
- Understand customer spending patterns.
- Develop targeted marketing campaigns.
- Improve customer retention.
- Create personalized promotional offers.

## 10. Project Structure

```text
Mall-Customer-Segmentation/
│
├── README.md
├── requirements.txt
├── main.py
├── Mall_Customers.csv
└── images/
```

## 11. Installation and Execution

**Step 1: Clone the repository**

```bash
git clone https://github.com/naik-aarya/Mall-Customer-Segmentation.git
```

**Step 2: Navigate to the project directory**

```bash
cd Mall-Customer-Segmentation
```

**Step 3: Install dependencies**

```bash
pip install -r requirements.txt
```

## 12. Conclusion

This project demonstrates the application of K-Means Clustering for customer segmentation using annual income and spending behaviour. The identified customer groups can help businesses make data-driven decisions and improve marketing strategies.

---

**Author:** Aarya Naik

**GitHub:** https://github.com/naik-aarya
