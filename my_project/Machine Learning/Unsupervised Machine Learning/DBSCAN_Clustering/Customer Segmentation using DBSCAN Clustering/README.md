# Customer Segmentation using DBSCAN Clustering

## Overview
This project applies **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to segment customers based on their **Age** and **Balance**.  
Unlike K-Means, DBSCAN can identify **noise points (outliers)** and does not require specifying the number of clusters in advance.

---

## Objective
- Apply density-based clustering on customer data  
- Identify natural clusters and noise points  
- Visualize customer distribution based on Age and Balance  

---

## Dataset
- **Churn_Modelling.csv**
- Features used:
  - `Age`
  - `Balance`
- Numeric features used directly for clustering

---

## Methodology
- Data loading and basic exploration  
- Feature selection (`Age`, `Balance`)  
- Data scaling using `StandardScaler`  
- DBSCAN clustering with:
  - `eps = 1`
  - `min_samples = 4`
- Cluster label analysis  

---

## Visualization
- Scatter plot of Age vs Balance  
- Label distribution showing clusters and noise (`-1`)  

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
This project demonstrates how DBSCAN can detect density-based customer segments and identify outliers in real-world datasets.
