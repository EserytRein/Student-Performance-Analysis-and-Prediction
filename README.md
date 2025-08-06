# 📊 Student Performance Prediction

This project focuses on predicting student final grades using various features such as academic history, personal background, and behavioral attributes. The objective is to develop predictive models that can accurately estimate student outcomes based on available data.

---

## 📂 Dataset
The dataset contains **395 observations** and **35 features**, including:
- Academic grades (G1, G2, G3)
- Demographics (age, address, family details)
- Behavioral patterns (absences, study time, etc.)
- School-related factors (school support, extracurricular activities)

---

## 📝 Project Workflow
1. **Data Exploration & Cleaning**
   - Checked for missing values and data types.
   - Combined grades **G1, G2, G3** into an aggregated feature **G_AVG** for simplifying visualization.
   - Applied **log transformation on Absences** due to high skewness.

2. **Exploratory Data Analysis (EDA)**
   - Univariate, Bivariate, and Multivariate visualizations.
   - Correlation analysis to identify relationships between features.
   - Visualized skewness, kurtosis, and distribution patterns.

3. **Feature Engineering**
   - Created new variables such as **G_AVG**.
   - Applied log transformations to normalize skewed data.

4. **Modeling**
   - **Multiple Linear Regression** to establish a baseline model.
   - **Random Forest Regressor** to capture non-linear relationships and improve predictive accuracy.

5. **Model Evaluation**
   - R² Score
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)

---

## 📈 Visualizations Included
- Distribution plots for G1, G2, G3, and Absences.
- Correlation Heatmaps.
- Actual vs Predicted Scatterplots.
- Residual Analysis.
- Random Forest Feature Importance plots.

## 📚 Credits
[![Kaggle Dataset](https://img.shields.io/badge/Kaggle-Student%20Performance-blue?logo=kaggle)](https://www.kaggle.com/datasets/devansodariya/student-performance-data/data) 


