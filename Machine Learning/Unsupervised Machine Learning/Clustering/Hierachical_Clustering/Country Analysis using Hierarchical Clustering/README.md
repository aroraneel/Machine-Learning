# Country Analysis using Hierarchical Clustering

## Overview
This project demonstrates **Hierarchical Clustering (Agglomerative Clustering)** to analyze and group countries based on socio-economic indicators.  
The approach builds clusters step by step and visualizes relationships using a **dendrogram**, helping to understand how countries are grouped based on similarity.

---

## Objective
- Perform country-level clustering using hierarchical methods  
- Visualize cluster formation with a dendrogram  
- Identify groups of countries with similar characteristics  

---

## Dataset
- **Country-data.csv**
- Features used for clustering:
  - `child_mort`
  - `exports`
- Dataset contains socio-economic indicators for multiple countries

---

## Methodology
- Load and inspect the dataset  
- Check for missing values  
- Perform exploratory analysis using pair plots  
- Select numeric features for clustering  
- Build a dendrogram using Ward’s linkage  
- Apply Agglomerative Clustering with:
  - `n_clusters = 2`
  - `linkage = 'ward'`  

---

## Visualization
- Pair plot for feature relationships  
- Dendrogram showing hierarchical cluster formation  
- Scatter plot displaying final cluster assignments  

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- SciPy  
- Scikit-learn  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

---

## Notes
This project illustrates how hierarchical clustering helps uncover structured relationships in country-level data without requiring predefined cluster counts.
