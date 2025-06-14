
# 🧠 Breast Cancer Prediction Using PCA 🎯

This project focuses on predicting **breast cancer diagnosis** using machine learning techniques after **dimensionality reduction** via **Principal Component Analysis (PCA)**. The model helps classify tumors as **benign** or **malignant** efficiently using reduced features.

---

## 📌 Objective

- Apply **PCA** to reduce the dimensionality of breast cancer dataset features.
- Build a machine learning model to predict cancer diagnosis.
- Visualize how PCA helps separate data points in lower dimensions.

---

## 📊 Dataset Overview

- **Features:** 30 numerical features computed from digitized images of a breast mass (radius, texture, perimeter, area, smoothness, etc.)
- **Target Variable:** Diagnosis (M = Malignant, B = Benign)
- **Source:** `sklearn.datasets.load_breast_cancer()`

---

## ⚙️ Technologies Used

- **Languages:** Python
- **Libraries:**  
  - `numpy`, `pandas`  
  - `matplotlib`, `seaborn`  
  - `scikit-learn`  
  - `jupyter-notebook`

---

## 📈 Workflow

### 1. Data Preprocessing
- Load dataset using `sklearn`
- Encode diagnosis labels to numeric
- Standardize features using `StandardScaler`

### 2. PCA Transformation
- Reduce 30 features to **2 principal components**
- Visualize data distribution after PCA

### 3. Model Building
- Use **Logistic Regression** on PCA-transformed data
- Train-test split (80-20)
- Model fitting and prediction

### 4. Evaluation
- Accuracy score
- Confusion Matrix
- Visual separation of cancer types via PCA

---

## 📉 PCA Visualization

The PCA plot below shows how the two principal components separate benign and malignant tumor data points:

![PCA Visualization](./a605b051-5bb2-4d6e-b0ac-936094848253.png)

> 🟡 Yellow: Benign tumors  
> 🔵 Blue: Malignant tumors  

---

## ✅ Results

- **Model Used:** Logistic Regression  
- **Accuracy Achieved:** ~93%  
- **Observations:**
  - PCA successfully captures variance with just 2 components.
  - Even with reduced dimensions, classification is quite effective.

---

## 🗂 Project Structure


