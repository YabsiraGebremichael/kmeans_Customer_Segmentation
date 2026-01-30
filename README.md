# Customer Segmentation with K-Means

## Overview

This project applies **K-Means clustering** to segment customers based on demographic and behavioral data. The goal is to identify meaningful customer groups that can support targeted marketing and business decisions.

The project covers the core data science workflow, from data cleaning to clustering and visualization.

---

## Data Preparation

Key preprocessing and feature engineering steps include:

* Handling missing values
* Converting date columns to datetime format
* Creating new features such as:

  * Age
  * Total Children
  * Total Spending
  * Customer Tenure

---

## Exploratory Data Analysis

Basic EDA was performed to understand customer behavior, including:

* Distributions of age, income, and spending
* Comparisons across education and marital status
* Correlation analysis between key numerical features

---

## Clustering Approach

Selected features for clustering:

* Age
* Income
* Total Spending
* Number of Web Purchases
* Number of Store Purchases
* Number of Web Visits per Month
* Recency

All features were standardized using **StandardScaler**.

The **Elbow Method** was used to determine the optimal number of clusters, and **6 clusters** were selected. Each customer was assigned a cluster label using K-Means.

---

## Code

# File overview:

* clustering.ipynb – Jupyter notebook containing data cleaning, feature engineering, exploratory data analysis, K-Means clustering, and PCA-based visualization.

* customer_segmentation.csv – Customer dataset used for segmentation and analysis.

---

## Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Jupyter Notebook

---


