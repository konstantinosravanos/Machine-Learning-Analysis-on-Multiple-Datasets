## 📌 Overview
This repository contains the analysis and implementation of machine learning techniques applied to three different datasets.  
The work covers **classification**, **clustering**, and **regression** tasks, aiming to extract insights and build predictive models.

---

## 📂 Datasets

1. **Credit Card Customer Data.csv**
   - Contains demographic and financial information about credit card customers, such as age, gender, income, and spending patterns.
   - Used for **clustering** customers based on their characteristics.

2. **framingham.csv**
   - Data from the Framingham Heart Study.
   - Includes demographic, lifestyle, and medical history variables related to cardiovascular disease.
   - Used for **classification** to predict the probability of developing heart disease.

3. **Walmart.csv**
   - Historical sales data from Walmart stores.
   - Includes weekly sales, dates, product categories, and other influencing factors.
   - Used for **regression** to forecast future sales.

---

## 🛠️ Code Contents

### 1. Classification (framingham.csv)
- Data preprocessing (cleaning, handling missing values).
- Exploratory Data Analysis (EDA) with statistics and visualizations.
- Implementation of classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model evaluation using Accuracy, Precision, Recall, and F1-score.

### 2. Clustering (Credit Card Customer Data.csv)
- Feature normalization.
- Determining the optimal number of clusters (Elbow method, Silhouette score).
- Application of K-Means and other clustering algorithms.
- Visualization of clusters in 2D/3D.

### 3. Regression (Walmart.csv)
- Data exploration and preprocessing.
- Feature engineering.
- Implementation of regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Model evaluation using MAE, MSE, RMSE, and R².

---

## 📊 Results & Insights
- **Classification:** Random Forest achieved the best performance in predicting cardiovascular disease.
- **Clustering:** The optimal number of clusters was X (based on Silhouette Score), providing meaningful customer segmentation.
- **Regression:** Random Forest Regressor yielded the highest accuracy in sales forecasting.

---

## 📎 Files
- `classification.ipynb` → Classification analysis for framingham.csv.
- `clustering.ipynb` → Customer segmentation for Credit Card Customer Data.csv.
- `regression.ipynb` → Regression models for Walmart.csv.

---

## 👨‍💻 Author
Developed as part of a study on applying machine learning techniques to real-world datasets.
