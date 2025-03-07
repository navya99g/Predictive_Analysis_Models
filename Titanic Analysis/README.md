# 🚢 Titanic Survival Prediction  

## Introduction  
This repository contains a machine learning pipeline for predicting passenger survival on the Titanic using the Titanic dataset from Kaggle. The model is built using **scikit-learn** and employs a **RandomForestClassifier** with hyperparameter tuning.

## Dataset 📊  
- **Source**: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)  
- **Exploratory Data Analysis (EDA):** Available in the [Exploration_Data_Analysis Repository](https://github.com/navya99g/Exploration_Data_Analysis/tree/main/Titanic_EDA)

## 🎯 Objectives  
	✅ Data Cleaning & Preprocessing: Handling missing values effectively.
	✅ Exploratory Data Analysis (EDA): VUnderstanding key survival trends.
	✅ Feature Engineering: Extracting meaningful features (e.g., Family Size).
	✅ Model Training & Evaluation: Building a robust prediction pipeline.
	✅ Submission: Generating predictions for Kaggle leaderboard evaluation.

## 🏗️ Model Pipeline
1️⃣ **Data Preprocessing**:
* Handling Missing Data:
  > Categorical features are imputed and one-hot encoded.
  > Numerical features are imputed with mean values and scaled.
* Feature Engineering: **FamilySize** = SibSp + Parch (indicates group survival influence).
* Scaling: Standardization of numeric features like **Age**, **Fare**, and **FamilySize**.
	
2️⃣ **Model Training**:
- **RandomForestClassifier** is used within a Pipeline.
- **Hyperparameter tuning** is performed using **GridSearchCV** for optimal performance.
	
3️⃣ **Model Evaluation**:
- Performance Metrics: Accuracy, Precision, Recall, F1-score.
- Cross-validation for model robustness.

## 📌 Best Performing Model: Tuned Random Forest
- Accuracy: 81.2%
- Feature Importance: Pclass, Sex, Age, and FamilySize had the highest predictive value.

## 📌 Future Improvements  
- Try different models like **XGBoost** or **GradientBoostingClassifier**.
- Experiment with feature engineering (e.g., name titles, ticket numbers).
- Use ensemble techniques for further improvements.Try different models (XGBoost, LightGBM)
 
## Acknowledgments  
- Dataset: [Kaggle](https://www.kaggle.com)  
- Inspired by the application of **machine learning in hospitality analytics**.  
