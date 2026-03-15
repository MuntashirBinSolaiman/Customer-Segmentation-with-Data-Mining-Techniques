# Customer Segmentation using Data Mining Techniques

## Overview
This project applies **data mining techniques** to analyze customer purchasing behavior using the **Wholesale Customers dataset**. The goal is to identify patterns in customer spending and group similar customers together using clustering algorithms.

The project demonstrates how unsupervised learning methods can be used for **customer segmentation**, which helps businesses better understand purchasing patterns and make informed decisions.

---

## What This Project Does
This project performs **customer segmentation** by analyzing spending in different product categories:

- Fresh
- Milk
- Grocery
- Frozen
- Delicatessen

The main tasks include:

- Data preprocessing and normalization
- Customer clustering using **K-Means**
- Customer clustering using **Hierarchical (Agglomerative) Clustering**
- Evaluating cluster quality using **Silhouette Score**
- Visualizing cluster relationships using a **Dendrogram**
- Applying **Support Vector Machine (SVM)** for classification analysis

---

## Why This Project Was Done
Businesses often have large datasets of customer purchases but lack clear insights into customer behavior.

Using **data mining techniques**, we can:

- Discover hidden patterns in purchasing behavior
- Identify different types of customers
- Improve marketing strategies
- Support business decision-making
- Target customers more effectively

Customer segmentation is widely used in **retail, marketing, and supply chain management**.

---

## How It Works

### 1. Data Preprocessing
The dataset is cleaned and prepared for analysis. Numerical features are standardized using **StandardScaler** to ensure that all variables contribute equally to clustering.

### 2. Feature Standardization
Standardization converts features into **z-scores**, allowing clustering algorithms to compare variables on the same scale.

### 3. K-Means Clustering
K-Means groups customers by minimizing the distance between customers and cluster centroids.

Steps involved:
- Choose number of clusters
- Assign data points to nearest centroid
- Update centroids iteratively

### 4. Hierarchical Clustering
Agglomerative clustering builds clusters step-by-step by merging the closest clusters.

A **dendrogram** is used to visualize cluster relationships and determine suitable cluster numbers.

### 5. Cluster Evaluation
Cluster quality is evaluated using the **Silhouette Score**, which measures how well each data point fits within its cluster.

### 6. Classification Analysis
An **SVM (Support Vector Machine)** model is used to analyze classification performance based on the clustered data.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

---

## Libraries Used
```python
pandas
numpy
matplotlib
sklearn
scipy
