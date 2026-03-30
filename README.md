# 🏠 California Housing Regression Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)  ![Data Analysis](https://img.shields.io/badge/DataAnalysis-EDA-orange)  ![Visualization](https://img.shields.io/badge/Visualization-Seaborn-green)  ![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)

A supervised machine learning project focused on applying and comparing multiple regression algorithms on real-world housing data.

---

## 🚀 Run Notebook in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RMY6E-UBoBE8JtKDv-HwjVZDJfFYinUR)

---

## 📘 Project Overview

- This project performs a detailed regression analysis using the **California Housing dataset** available from the `sklearn` library.  
- The dataset contains **20,640 records and 8 numerical features**, along with a continuous target variable representing median house value.  
- The objective is to understand how different housing-related features influence house prices and compare multiple regression models.

---

## 🎯 Objective

🔹 Data loading and preprocessing  

🔹 Feature scaling and data preparation

🔹 Implementation of multiple regression algorithms  

🔹 Model evaluation and comparison  

🔹 Visualizations and result interpretation  

🔹 Clean and reproducible Google Colab notebook  

---

## 📂 Dataset Description

The dataset represents housing information collected from California census data.

| Feature Name | Description |
|-------------|------------|
| MedInc | Median income in the block group |
| HouseAge | Median house age in the block group |
| AveRooms | Average number of rooms per household |
| AveBedrms | Average number of bedrooms per household |
| Population | Population of the block group |
| AveOccup | Average household occupancy |
| Latitude | Latitude of the block group |
| Longitude | Longitude of the block group |
| MedHouseValue | Median house value (target variable) |

---

## 🧹 Preprocessing Steps

✔ Dataset loaded using `fetch_california_housing`  

✔ Converted to Pandas DataFrame  

✔ Checked for missing values (none found)  

✔ Outlier removal using IQR method  

✔ Train–Test split performed 

✔ Feature scaling applied where required  

---

## 📈 Regression Models Implemented

- Linear Regression
  
- Decision Tree Regressor
  
- Random Forest Regressor
  
- Gradient Boosting Regressor
  
- Support Vector Regressor (SVR)  

---

## 📊 Model Evaluation Metrics

- Mean Absolute Error (MAE)
  
- Mean Squared Error (MSE)
  
- R² Score  

---

## 📊 Model Performance & Comparison

The performance of different regression models is summarized below:

| Model | MAE | MSE | R² Score |
|------|------|------|----------|
| Linear Regression | 0.4603 | 0.3697 | 0.5953 |
| Decision Tree Regressor (Pruned) | 0.4688 | 0.3907 | 0.5724 |
| Random Forest Regressor | 0.3305 | 0.2223 | 0.7567 |
| Gradient Boosting Regressor | 0.3325 | 0.2157 | 0.7639 |
| Support Vector Regressor | 0.3377 | 0.2384 | 0.7390 |

---

### 🏆 Best Performing Model

**Gradient Boosting Regressor**  

✔ R² Score: **0.7639**  

✔ Lowest error among all models  

✔ Best overall performance  

---

### ⚠️ Worst Performing Model

**Decision Tree Regressor (Pruned)**  
❌ R² Score: **0.5724**  

❌ Higher error compared to other models  

---

### 📌 Key Insight

- Ensemble models (**Random Forest & Gradient Boosting**) outperform traditional models
  
- Gradient Boosting provides the most accurate and stable predictions  
## 📊 Visualizations Included

| Purpose | Visualization Type |
|--------|-------------------|
| Actual vs Predicted Values | Scatter Plot |
| Feature Importance | Bar Chart |
| Model Comparison | Tabular Comparison |

---

## 🧠 Key Observations

✔ Ensemble models performed better than basic models  

✔ Gradient Boosting achieved the highest R² score  

✔ Median income and geographic features strongly influence house prices  

✔ Simpler models are easier to interpret but less accurate  

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|--------|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Visualization |
| Scikit-learn | Machine learning |
| Google Colab | Execution environment |

---

## 📁 Repository Structure

ML-Assignment-2-Regression/

├── Regression.ipynb  

├── README.md  

---

## 🚀 How to Run the Project

1️⃣ Open the notebook using the Colab link above  

2️⃣ Run all cells sequentially

3️⃣ View preprocessing, model training, evaluation, and visualizations  

---

## 📌 Academic Submission

This project was developed as part of a **Python Module / Machine Learning academic assignment**, demonstrating the application of regression techniques on real-world housing data. It includes data preprocessing, exploratory data analysis, model building, evaluation, and interpretation of results.

---

## ⚠️ Limitations

- Dataset is limited to California region only
- 
- External economic and market factors are not included
- 
- Outlier removal may affect real-world interpretation
-  
- Models may not generalize well to other regions
-  
- Limited feature set restricts deeper insights  

---

## 📌 Future Enhancements

- Use larger and more diverse datasets
- 
- Apply advanced models (XGBoost, LightGBM)
- 
- Perform hyperparameter tuning
- 
- Deploy as a web application (Streamlit)
-  
- Add interactive dashboards  

---

## 👤 Author

**Name:** Laya Mary Joy  

**Organization:** Entri Elevate  

**Date:** January 15, 2026  

---

## ⭐ Acknowledgment

Thanks to **Entri Elevate** for guidance and support throughout this project.
