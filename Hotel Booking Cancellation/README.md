# Hotel Booking Cancellation Prediction 🏨❌  

## Introduction  
Predicting hotel booking cancellations is crucial for revenue management and operational efficiency in the hospitality industry. This project applies **machine learning models** to analyze key factors influencing cancellations and build a predictive model to assist hotels in managing their bookings effectively.  

## Dataset 📊  
- **Source**: [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand?select=hotel_bookings.csv)  
- **Exploratory Data Analysis (EDA):** Available in the [Exploration_Data_Analysis Repository](https://github.com/navya99g/Exploration_Data_Analysis/tree/main/Hotel_Booking_EDA).  

## Objectives  
- ✅ Clean and preprocess hotel booking data.
- ✅ Identify factors affecting cancellation rates.
- ✅ Build and compare multiple ML models.
- ✅ Optimize predictions using hyperparameter tuning.
- 
## 🏗️ Model Pipeline
- 1️⃣ Feature Engineering & Data Processing:
  - One-hot encoding for categorical variables.
  - Handled missing values.
- 2️⃣ Model Training & Optimization:
  - Models Used: Logistic Regression, Decision Tree, Random Forest.
  - Tuned Random Forest showed the best performance.
  - Feature Importance: Lead Time, Deposit Type, Booking Agent.
- 3️⃣ Model Evaluation:
  - Best Model: Tuned Random Forest.
  - Accuracy: 78.47%.
  - ROC AUC Score: 0.86.

## Key Insights 🔍  
✅ **High lead times and non-refundable deposits are strong cancellation predictors.**  
✅ **Feature selection had a negative impact on performance**, suggesting all features contribute to predictive power.  
✅ **The tuned Random Forest model performed well, but recall for cancellations can be improved.**  

## 📌 Future Enhancements:
- Experiment with XGBoost, LightGBM.
- Improve recall for cancellations using class balancing techniques (SMOTE, cost-sensitive learning).
- Deploy the model for real-world applications.

## Acknowledgments  
- Dataset: [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand)  
- Inspired by the application of **machine learning in hospitality analytics**.  

