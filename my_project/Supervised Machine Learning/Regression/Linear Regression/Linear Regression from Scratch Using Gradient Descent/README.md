# Linear Regression from Scratch Using Gradient Descent

## Overview
This project demonstrates how **Linear Regression** works internally by implementing **Gradient Descent from scratch** using NumPy.  
Instead of relying on pre-built machine learning models, the project focuses on understanding **model optimization, error minimization, and parameter convergence** through visualization.

Synthetic data is generated to clearly illustrate how coefficients are learned and how the error surface behaves during optimization.

---

## Objective
- Understand linear regression mathematically and visually  
- Implement gradient descent without using Scikit-learn  
- Observe how model coefficients converge over iterations  
- Visualize error surfaces and optimization paths  

---

## Dataset
- **Synthetic dataset** generated using NumPy
- Features:
  - `Feature1`
  - `Feature2`
- Target:
  - Linear combination of features with added Gaussian noise

---

## Data Generation
- Randomly generated feature values
- Known true coefficients used to generate target values
- Noise added to simulate real-world data
- Data stored in a Pandas DataFrame for analysis

---

## Model Implementation
- Linear regression implemented using:
  - Mean Squared Error (MSE) loss function
  - Batch Gradient Descent optimization
- Bias term explicitly added to the feature matrix
- Parameters initialized to zero and updated iteratively

---

## Training Process
- Learning rate (`alpha`) = 0.01  
- Number of iterations = 1000  
- Cost (MSE) tracked at each iteration  
- Final learned coefficients compared with true coefficients  

---

## Visualization
The project includes multiple visualizations:
- **3D scatter plot** of synthetic data and true regression line
- **Loss vs iteration plot** showing gradient descent convergence
- **2D contour plot** of error surface with optimization path
- **3D surface plot** of Mean Squared Error landscape

These plots help build intuition about how gradient descent navigates the error surface.

---

## Key Insights
- Gradient descent successfully learns coefficients close to true values
- Loss decreases smoothly with proper learning rate
- Error surface is convex, ensuring convergence to a global minimum
- Visualization clearly explains optimization dynamics

---

## Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Jupyter Notebook / VS Code  

---

## Author
**Neel Arora**  
BCA Undergraduate | Focused on Artificial Intelligence & Machine Learning  

## Notes
This README provides a brief overview of the project structure and methodology.
