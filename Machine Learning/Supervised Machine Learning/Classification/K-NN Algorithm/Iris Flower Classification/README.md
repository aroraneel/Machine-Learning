# Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Overview
This project classifies iris flowers into three species using the **K-Nearest Neighbors (KNN)** machine learning algorithm.

The Iris dataset is one of the most popular beginner datasets in machine learning, containing flower measurements that help predict the flower category.

The model is trained and evaluated using accuracy and confusion matrix visualization.

---

## 🎯 Objectives
- Load and explore the Iris dataset  
- Visualize relationships between flower features  
- Build a classification model using **KNN**  
- Evaluate performance using:
  - Accuracy Score  
  - Confusion Matrix Heatmap  
- Test multiple values of **k** to find the best neighbor count  

---

## 📁 Dataset Information
- Dataset: **Iris Flower Dataset (Scikit-learn built-in)**
- Total Samples: 150  
- Classes:
  - Setosa  
  - Versicolor  
  - Virginica  

### Features Used:
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

Target Variable:
- `target` (0, 1, 2)

---

## 🔍 Methodology

### 1. Data Loading
- Load dataset using `load_iris()` from Scikit-learn  
- Convert into Pandas DataFrame for easier analysis  

---

### 2. Data Exploration & Visualization
- Add target labels and flower names  
- Split dataset into three groups based on species  
- Create scatter plots:
  - Sepal Length vs Sepal Width  
  - Petal Length vs Petal Width  

These plots help visualize separability between flower categories.

---

### 3. Feature and Target Selection
- Features (`X`) → Flower measurements  
- Target (`y`) → Species class  

---

### 4. Train-Test Split
- Training Set: 70%  
- Testing Set: 30%  
- Random state fixed for reproducibility  

---

### 5. Model Training (KNN Classifier)
Algorithm:
- **KNeighborsClassifier**
- Initial neighbors: `k = 5`

KNN predicts flower species based on the majority class of nearest neighbors.

---

### 6. Model Evaluation
- Calculate model accuracy on test data  
- Generate confusion matrix  
- Visualize results using Seaborn heatmap  

---

### 7. Hyperparameter Testing
To improve accuracy, multiple values of **k (1–9)** are tested to observe performance changes.

---

## 📊 Results & Insights
- KNN performs very well on the Iris dataset due to clear feature separation  
- Accuracy varies slightly depending on the value of **k**  
- Confusion matrix highlights correct and misclassified flower species  

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🚀 Applications
- Beginner-friendly classification example  
- Pattern recognition in biological datasets  
- Feature-based multi-class classification tasks  

---

## 👤 Author
**Neel Arora**  
BCA Undergraduate | Data Science & Machine Learning Enthusiast  

---
