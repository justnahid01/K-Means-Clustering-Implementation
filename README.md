# K-Means-Clustering-Implementation



# K-Means Clustering Implementation

## Project Overview

This project implements the K-Means Clustering algorithm for customer segmentation using the Mall Customers dataset. The objective is to identify groups of customers with similar characteristics based on Age, Annual Income, and Spending Score.

The project includes data exploration, preprocessing, cluster optimization using the Elbow Method, model training, visualization, and model persistence.

---

## Dataset

Dataset: Mall Customers Dataset

Features Used:

* Age
* Annual Income (k$)
* Spending Score (1-100)

---

## Project Workflow

### 1. Data Exploration (EDA)

The dataset was analyzed using:

* Dataset overview
* Missing value analysis
* Duplicate record analysis
* Descriptive statistics
* Feature distribution analysis
* Correlation analysis
* Outlier detection

### 2. Data Preprocessing

* Feature selection
* Standardization using StandardScaler

### 3. Cluster Optimization

The Elbow Method was used to determine the optimal number of clusters.

Selected Number of Clusters:

K = 5

### 4. Model Training

K-Means clustering was trained using:

* n_clusters = 5
* init = 'k-means++'
* random_state = 42
* n_init = 10

### 5. Model Persistence

The following files are generated:

* kmeans_model.pkl
* scaler.pkl

### 6. Visualization

The project includes:

* Elbow Curve
* 3D Cluster Visualization
* Cluster Analysis Summary

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Results

The K-Means algorithm successfully segmented customers into five distinct groups based on spending behavior, age, and income characteristics.

These customer segments can be used for:

* Customer profiling
* Targeted marketing
* Business intelligence
* Customer retention strategies

---

## Repository Structure

dataset/
Mall_Customers_Dataset.csv

model/
kmeans_model.pkl
scaler.pkl

notebook/
KMeans_Implementation.ipynb

README.md

---

## Author

Nahid Hasan
