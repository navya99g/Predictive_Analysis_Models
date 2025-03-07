# World Happiness Prediction 🌍😊

## Introduction  
Happiness is a key indicator of a nation's well-being and quality of life. This project applies **predictive modeling** to the **2019 World Happiness dataset** to estimate happiness scores based on key socio-economic factors. The goal is to understand how economic, social, and health indicators impact happiness and to provide insights that can guide policymakers in enhancing citizens' well-being.  

## Dataset  
- **Source:** [World Happiness Report 2019](https://www.kaggle.com/unsdsn/world-happiness)  
- **Exploratory Data Analysis (EDA):** Available in the [Exploration_Data_Analysis Repository](https://github.com/navya99g/Exploration_Data_Analysis/tree/main/World_Happiness_EDA).  

## Objectives  
- ✅ Identify key factors influencing happiness.
- ✅ Address multi collinearity among variables.
- ✅ Build and evaluate multiple regression models.
- ✅ Optimize model performance using hyperparameter tuning. 

## 🏗️ Model Approach  
- 1️⃣ Data Preprocessing & Feature Selection:
    - Handled missing values and standardized features.
    - Used Variance Inflation Factor (VIF) to detect multi collinearity.
- 2️⃣ Model Selection & Training:
    - Models Used: Ridge Regression, Random Forest, XGBoost.
    - **Ridge Regression** performed best, handling multi collinearity effectively.
    - Hyperparameter tuning using **Grid Search**.
- 3️⃣ Model Evaluation:
    - Best Model: Ridge Regression (α = 17.48)
    - R² Score: 0.8719 (87.19% variance explained).
    - RMSE: 0.4261 (lowest prediction error).

## Key Insights 📊  
- ✅ **Ridge Regression effectively handled multi collinearity**, outperforming tree-based models.  
- ✅ Economic, social, and health indicators collectively provide a **strong predictive foundation** for happiness levels.  
- ✅ Future enhancements include **residual analysis, time-series trends, and policy-based insights** to refine predictions.  

## 📌 Future Enhancements
- 🔹 Investigate **non-linear techniques** for improved generalization.  
- 🔹 Perform **residual analysis** and feature engineering to enhance model robustness.  

## Acknowledgments  
- Dataset: [Kaggle](https://www.kaggle.com)  
- Inspired by the application of **machine learning in hospitality analytics**.  
