
# SmartCart Customer Segmentation System

## Customer Segmentation Using Unsupervised Machine Learning

An end-to-end Machine Learning project that identifies distinct customer groups based on demographics, purchasing behavior, and engagement patterns. The system leverages clustering techniques to uncover hidden customer segments, enabling personalized marketing, customer retention, and data-driven business decisions.

---

## Project Overview

SmartCart is a growing e-commerce platform that serves customers across multiple regions. The company currently applies the same marketing strategy to all customers, resulting in inefficient campaigns and missed business opportunities.

This project develops an intelligent customer segmentation system using Unsupervised Machine Learning to discover meaningful customer groups and support targeted marketing strategies.

---

## Business Problem

Challenges faced by SmartCart:

* Generic marketing campaigns for all customers
* Difficulty identifying high-value customers
* Delayed detection of churn-prone users
* Inefficient allocation of marketing resources
* Lack of customer-specific engagement strategies

### Solution

Build a customer segmentation system that automatically groups customers based on:

* Spending behavior
* Income level
* Purchase frequency
* Customer engagement
* Loyalty indicators

---

## Tech Stack

**Programming Language**

* Python

**Libraries**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

**Machine Learning Techniques**

* Feature Engineering
* One-Hot Encoding
* Standard Scaling
* Principal Component Analysis (PCA)
* K-Means Clustering
* Agglomerative Clustering

---

## Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Outlier Removal
      ↓
Encoding
      ↓
Feature Scaling
      ↓
PCA
      ↓
K-Means Clustering
      ↓
Agglomerative Clustering
      ↓
Cluster Evaluation
      ↓
Customer Insights
```

---

## Feature Engineering

New features were created to improve customer understanding:

* Age
* Total Spending
* Customer Tenure
* Total Children

These engineered features provide better behavioral insights compared to the raw dataset.

---

## Clustering Approach

### K-Means Clustering

Used to partition customers into distinct groups by minimizing the distance between data points and cluster centroids.

### Agglomerative Clustering

A hierarchical clustering approach used to compare clustering performance and customer group structures.

---

## Model Evaluation

The quality of clusters was evaluated using:

* Elbow Method
* Silhouette Score

These techniques helped determine the optimal number of customer segments and assess cluster separation.

---

## Key Features

* End-to-End Machine Learning Pipeline
* Customer Behavior Analysis
* Customer Segmentation
* Feature Engineering
* Dimensionality Reduction with PCA
* Clustering Model Comparison
* Business-Oriented Insights
* Data Visualization

---

## Customer Segments Identified

Example business-oriented customer groups:

### VIP Customers

* High income
* High spending
* Strong loyalty

### Regular Customers

* Consistent purchasing behavior
* Moderate engagement

### Churn Risk Customers

* Low activity
* Reduced purchasing frequency

### New Customers

* Recent customers with limited purchase history

---

## Business Impact

This system can help businesses:

* Personalize marketing campaigns
* Improve customer retention
* Identify high-value customers
* Detect churn-prone users
* Increase marketing efficiency
* Support strategic decision-making

---

## Repository Structure

```text
SmartCart-Customer-Segmentation/
│
├── smartCart.ipynb
├── README.md
├── requirements.txt
│
├── data/
│   └── customer_data.csv
│
└── images/
    ├── elbow_method.png
    ├── pca_visualization.png
    └── cluster_analysis.png
```

---

## Future Improvements

* Deploy using Streamlit
* Build an interactive dashboard
* Implement DBSCAN and Gaussian Mixture Models
* Perform Customer Lifetime Value Analysis
* Integrate Recommendation Systems

---

## Results

Successfully segmented customers into meaningful clusters using unsupervised learning techniques, providing actionable insights for personalized marketing and customer retention strategies.

---


