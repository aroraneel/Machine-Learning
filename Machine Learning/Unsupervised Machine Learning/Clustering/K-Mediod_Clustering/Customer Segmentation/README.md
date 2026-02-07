# Customer Segmentation using K-Medoids Clustering

## Overview
This project performs **customer segmentation** using the **K-Medoids clustering algorithm** on credit card customer data.  
K-Medoids is a robust alternative to K-Means that uses actual data points as cluster centers, making it less sensitive to outliers.

---

## Objective
- Segment customers based on spending and payment behavior  
- Apply K-Medoids clustering on scaled financial features  
- Analyze cluster distribution for customer profiling  

---

## Dataset
- **CC GENERAL.csv**
- Customer credit card usage data
- Removed non-informative column: `CUST_ID`

---

## Data Preprocessing
- Selected key financial features such as:
  - Balance, Purchases, Cash Advance
  - Credit Limit, Payments, Minimum Payments
  - Transaction-related attributes
- Handled missing values using mean imputation  
- Standardized features using **StandardScaler**

---

## Methodology
- Scaled the dataset for fair distance computation  
- Applied **K-Medoids clustering** with `k = 5`  
- Assigned cluster labels to each customer  
- Analyzed cluster sizes using bar plots  

---

## Results
- Customers successfully grouped into **5 distinct clusters**  
- Cluster distribution visualized to understand customer segmentation  
- Each cluster represents a unique spending and payment behavior pattern  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Scikit-learn-extra  
- Matplotlib  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This project demonstrates the use of K-Medoids for real-world customer segmentation and highlights its robustness compared to distance-based clustering methods like K-Means.
