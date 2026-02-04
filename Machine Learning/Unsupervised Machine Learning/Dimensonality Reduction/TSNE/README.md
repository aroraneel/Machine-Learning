# t-SNE Visualization of Handwritten Digits

## 📊 Overview
This project explores **t-Distributed Stochastic Neighbor Embedding (t-SNE)** for **non-linear dimensionality reduction** using the handwritten digits dataset from Scikit-learn.  
The goal is to visualize high-dimensional image data in **2D space** and study how different **perplexity values** affect cluster separation.

---

## 🎯 Objectives
- Apply **t-SNE** to high-dimensional image data  
- Compare embeddings using different **perplexity values (20 vs 40)**  
- Visualize class-wise clustering of handwritten digits  
- Build intuition around **manifold learning techniques**

---

## 📁 Dataset
- **Digits Dataset** (Scikit-learn)
- Samples: 1,200 randomly selected images  
- Features: 64 pixel-intensity values per image  
- Target: Digit labels (0–9)

---

## 🔍 Methodology
1. **Data Sampling**
   - Randomly sample 1,200 digit images for efficiency

2. **Preprocessing**
   - Standardize features using `StandardScaler`

3. **Dimensionality Reduction**
   - Apply t-SNE with:
     - Perplexity = 20
     - Perplexity = 40
   - Reduce data from 64D → 2D

4. **Visualization**
   - Scatter plots with color-coded digit classes
   - Side-by-side comparison of embeddings

---

## 📌 Key Observations
- t-SNE effectively separates digit classes in 2D space  
- Lower perplexity captures **local structure more strongly**  
- Higher perplexity emphasizes **global relationships**  
- Cluster shapes and overlaps vary significantly with perplexity choice  

---

## 🛠️ Tools & Libraries
- Python  
- NumPy, Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📚 Applications
- Exploratory Data Analysis (EDA)  
- Visualization of high-dimensional datasets  
- Manifold learning intuition  
- Pre-analysis for clustering or classification tasks  

---

## 👤 Author
**Neel Arora**  
BCA Undergraduate | Data Science & Machine Learning Enthusiast  
