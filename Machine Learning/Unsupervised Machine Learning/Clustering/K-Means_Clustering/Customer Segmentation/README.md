# Customer Segmentation using K-Means Clustering

## Overview
This project demonstrates **customer segmentation** using the **K-Means clustering algorithm** on credit card customer data.  
The goal is to group customers based on their **BALANCE** and **CREDIT_LIMIT** to identify distinct spending patterns.

---

## Objective
- Perform unsupervised learning using K-Means  
- Determine the optimal number of clusters using the **Elbow Method**  
- Segment customers into meaningful groups  
- Visualize clusters and centroids  

---

## Dataset
- **CC GENERAL.csv** (Credit Card customer dataset)
- Features used:
  - `BALANCE`
  - `CREDIT_LIMIT`
- Missing values handled using mean imputation

---

## Methodology
- Data loading and basic exploration  
- Feature selection and null-value handling  
- Calculation of **WCSS** for different cluster counts  
- Elbow Method to choose optimal `k`  
- K-Means clustering with `k = 4`  
- Visualization of clusters and centroids  

---

## Visualization
- Elbow curve to identify optimal clusters  
- Scatter plot showing:
  - Customer clusters
  - Cluster centroids  

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Artificial Intelligence & Machine Learning  

---

## Notes
This project provides a clear example of applying K-Means clustering for real-world customer segmentation problems.
