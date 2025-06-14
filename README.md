# 🏦 Customer Churn Prediction

Predicting whether a bank customer is likely to churn using machine learning techniques. This project involves end-to-end development of a churn prediction pipeline — from Exploratory Data Analysis (EDA) to model evaluation.

---

## 📌 Project Overview

In this project, we build and evaluate a machine learning model to predict customer churn for a bank. Key steps include:

- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model selection from multiple ML algorithms  
- Hyperparameter tuning  
- Final evaluation on unseen test data

---

## 🧠 Model Summary

After testing various ML models, the **LightGBM Classifier** outperformed others in terms of predictive accuracy and ROC-AUC.

| Metric          | Score    |
|-----------------|----------|
| Accuracy        | **0.8670** |
| Precision       | 0.7571   |
| F1 Score        | 0.5844   |
| ROC-AUC         | **0.8741** |

### ✅ Best Model Configuration
- **Model:** LGBMClassifier  
- **Learning Rate:** 0.05  
- **Max Depth:** 5  
- **Estimators:** 100  

> The model shows good distinction capability between churned and retained customers. There is room for improvement — especially through ensemble stacking or boosting refinements.

---

## 🔍 Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- LightGBM  
- Matplotlib, Seaborn (for visualization)

---

## 📈 Future Work

- Ensemble learning with multiple base models  
- Feature importance optimization  
- A/B testing deployment on real user segments  
- Model interpretability (SHAP, LIME)

---

> 💡 *Churn prediction is more than just a model — it’s the first step in customer loyalty strategy.*
