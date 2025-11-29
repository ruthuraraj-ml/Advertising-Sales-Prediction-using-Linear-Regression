# 📊 Advertising Sales Prediction — Linear Regression

This project uses **Multiple Linear Regression** to analyze how advertising budgets across **TV**, **Radio**, and **Newspaper** channels influence **Sales**. It includes complete EDA, feature diagnostics, regression modeling, and business insights.

---

## 🚀 Project Overview
The goal of this project is to:
- Explore how media channels influence product sales  
- Build a predictive linear regression model  
- Interpret coefficients and statistical significance  
- Validate regression assumptions (normality, homoscedasticity, multicollinearity)  
- Provide actionable insights for budget optimization  

The final model achieves:
- **R² Score:** 0.91  
- **MAE:** 1.144  
- **RMSE:** 1.559  
- **Best Predictors:** TV & Radio  

---

## 📁 Dataset Details
- **Records:** 200  
- **Features:**
  - TV Advertising Budget  
  - Radio Advertising Budget  
  - Newspaper Advertising Budget  
  - Sales (response variable)  
- All variables are numerical and clean (no missing values/outliers).

---

## 🔍 Exploratory Data Analysis (Summary)
- TV has the strongest linear relationship with Sales.  
- Radio also shows meaningful correlation.  
- Newspaper’s impact is weak/negligible.  
- Correlation matrix confirms TV (0.78) and Radio (0.58) as strong features.  

---

## 🧠 Model Summary

### **Model Used**
Multiple Linear Regression:

\[
Sales = β_0 + β_1(TV) + β_2(Radio) + β_3(Newspaper)
\]

### **Model Findings**
- TV & Radio advertising significantly boost sales.  
- Newspaper budget shows negligible (slightly negative) impact.  
- VIF values indicate **no multicollinearity**.  
- Residuals are symmetric → regression assumptions hold.  

---

## 🎯 Key Insights
- TV advertising drives the highest return.  
- Radio further strengthens performance.  
- Newspaper ads can be safely reduced with **no loss in accuracy**.  
- Reallocating budget towards TV + Radio optimizes sales impact.

---

## 📦 Results Summary

| Item | Value |
|------|--------|
| Model | Multiple Linear Regression |
| Best Features | TV, Radio |
| Dropped Feature | Newspaper |
| MAE | 1.144 |
| RMSE | 1.559 |
| R² | 0.91 |
| Diagnostic Outcome | Regression assumptions satisfied |

---

## 🧱 Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter / Google Colab  
