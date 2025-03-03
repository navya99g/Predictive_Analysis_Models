# World Happiness Prediction 🌍😊

## Introduction  
Happiness is a key indicator of a nation's well-being and quality of life. This project applies **predictive modeling** to the **2019 World Happiness dataset** to estimate happiness scores based on key socio-economic factors. The goal is to understand how economic, social, and health indicators impact happiness and to provide insights that can guide policymakers in enhancing citizens' well-being.  

## Objectives  
- ✅ **Predict Happiness Scores** using key socio-economic indicators:  
  - `GDP per Capita` (Economic Prosperity)  
  - `Social Support` (Strength of Community and Relationships)  
  - `Healthy Life Expectancy` (Overall Well-being)  
- ✅ **Address Multicollinearity** and select the best-performing model.  

## Approach  
- ✔ **Data Preprocessing:** Handled missing values and standardized features.  
- ✔ **Multicollinearity Check:** Used **Variance Inflation Factor (VIF)** to detect highly correlated features.  
- ✔ **Model Selection:** Compared multiple regression techniques:  
  - **Ridge Regression** (*Best Model*)  
  - **Random Forest**  
  - **XGBoost**  
- ✔ **Hyperparameter Tuning:** Optimized model performance using **Grid Search**.  

## Dataset  
- **Source:** [World Happiness Report 2019](https://www.kaggle.com/unsdsn/world-happiness)  
- **Exploratory Data Analysis (EDA):** Available in the [Exploration_Data_Analysis Repository](https://github.com/your_username/Exploration_Data_Analysis).  

## Best Performing Model: Ridge Regression  
- **Optimal α:** 17.48  
- **Final Performance Metrics:**  
  - **R² Score:** 0.8719 → Explains 87.19% of variance in happiness scores.  
  - **RMSE:** 0.4261 → Lowest error compared to other models.  
  - **MAE:** 0.3382 → Best in minimizing absolute errors.  

## Key Insights 📊  
- ✅ **Ridge Regression effectively handled multicollinearity**, outperforming tree-based models.  
- ✅ Economic, social, and health indicators collectively provide a **strong predictive foundation** for happiness levels.  
- ✅ Future enhancements include **residual analysis, time-series trends, and policy-based insights** to refine predictions.  

## Next Steps 🚀  
- 🔹 Expand predictive modeling to other datasets from the **Exploration_Data_Analysis** repository.  
- 🔹 Investigate **non-linear techniques** for improved generalization.  
- 🔹 Perform **residual analysis** and feature engineering to enhance model robustness.  

 
## Acknowledgments  
- **Data Source:** [Kaggle](https://www.kaggle.com/unsdsn/world-happiness)  
- Inspired by **data science and public policy** communities to derive meaningful insights.  

