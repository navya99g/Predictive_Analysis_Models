# 🔍 Predictive Analysis & Modeling 🚀

## 📌 Introduction  
This repository focuses on building and evaluating machine learning models for various datasets, utilizing insights from [**Exploratory Data Analysis (EDA)**](https://github.com/navya99g/Exploration_Data_Analysis/tree/main). The goal is to develop predictive models that can accurately forecast outcomes based on key features identified in EDA.  

## 📊 Datasets and Modeling Approach  

| Dataset                  | Problem Type           | Models Used                           | Key Features from EDA |
|--------------------------|-----------------------|--------------------------------------|-----------------------|
| [**Titanic Survival**](https://github.com/navya99g/Predictive_Analysis_Models/tree/main/Titanic%20Analysis)  | Classification (Survival Prediction) | Logistic Regression, Random Forest, XGBoost | Pclass, Age, Sex, Fare, Embarked |
| [**World Happiness**](https://github.com/navya99g/Predictive_Analysis_Models/tree/main/World%20Happines%20Report)    | Regression (Happiness Score Prediction) | Linear Regression, Random Forest, XGBoost | GDP per Capita, Social Support, Life Expectancy |
| [**Hotel Booking**](https://github.com/navya99g/Predictive_Analysis_Models/blob/main/Hotel%20Booking%20Cancellation/README.md)      | Classification (Cancellation Prediction) | Logistic Regression, Decision Trees, XGBoost | Lead Time, Deposit Type, Customer Type |

---

## 📌 Methodology  
1. **Data Preprocessing:**  
   - Handle missing values, encode categorical variables, and scale numerical features.  
2. **Feature Engineering:**  
   - Select features based on **EDA insights** (e.g., correlation heatmaps, statistical tests).  

3. **Model Selection & Training:**  
   - Train multiple models for comparison.  
   - Use **GridSearchCV/RandomizedSearchCV** for hyperparameter tuning.  

4. **Model Evaluation:**  
   - Classification: **Accuracy, Precision-Recall, F1-score, ROC-AUC**.  
   - Regression: **RMSE, R²-score, MAE**.  

---

## 📈 Results & Insights  
✅ **Titanic:** Logistic Regression performed well, but Random Forest improved accuracy using key categorical features.  
✅ **World Happiness:** GDP, Social Support, and Life Expectancy strongly influence happiness scores. Random Forest showed the best predictive performance.  
✅ **Hotel Bookings:** Decision Trees helped identify cancellation patterns, with lead time and deposit type as strong predictors.  

---

## 🔥 Next Steps  
- **Feature Engineering**: Use domain-specific knowledge to create better features.  
- **Deep Learning Models**: Experiment with neural networks for more complex datasets.  
- **Automated ML Pipelines**: Deploy models using APIs or cloud services.

---

## 📌 Acknowledgments
- Data Sources: **Kaggle**
- Inspired by real-world applications of ML in business, policy, and competition settings.


