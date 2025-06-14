# 🧠 Breast Cancer Prediction Using PCA 🎯

This project focuses on predicting **breast cancer diagnosis** using machine learning techniques after **dimensionality reduction** via **Principal Component Analysis (PCA)**. The dataset used is the **Breast Cancer Wisconsin (Diagnostic) dataset**, available from `sklearn.datasets`.

## 📌 Objective

To build an efficient ML model that:
- Reduces feature space using PCA
- Predicts whether a tumor is **benign (B)** or **malignant (M)**

## 📊 Dataset Overview

- **Features:** 30 numerical features computed from digitized images of a breast mass (radius, texture, perimeter, area, smoothness, etc.)
- **Target Variable:** Diagnosis (M = Malignant, B = Benign)
- **Source:** `sklearn.datasets.load_breast_cancer()`

## 🔍 Technologies & Tools

- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

## 📈 Workflow

1. **Data Preprocessing**
   - Dataset loading & exploration
   - Label encoding
   - Feature scaling using `StandardScaler`

2. **Dimensionality Reduction**
   - Applying **PCA** to reduce from 30 features to 2 principal components
   - Visualizing the spread of the data in reduced dimension

3. **Model Building**
   - Using **Logistic Regression** for classification
   - Training and testing on PCA-transformed data

4. **Evaluation**
   - Accuracy score
   - Confusion matrix
   - PCA component visualization

## 📉 PCA Visualization

<img src="https://github.com/shivamverma18/Breast-Cancer-Prediction-Using-PCA/assets/pca-plot.png" alt="PCA scatter plot" width="600"/>

> The PCA transformation allows us to **visualize** the data separability between benign and malignant classes clearly.

## ✅ Results

- **Model:** Logistic Regression (on PCA-reduced features)
- **Accuracy:** ~93%
- **Advantages:**
  - Reduced overfitting
  - Lower computational complexity

## 🗂️ Project Structure

