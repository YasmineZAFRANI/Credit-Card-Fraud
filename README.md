# 💳 Credit Card Fraud Detection Project

## 📌 Objective

Classify fraudulent transactions from anonymized credit card dataset.

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) 2013

## 📅 Project Timeline

| Task | Duration | Status |
| --- | --- | --- |
| Data Collection & EDA | 1/2 days | Done  |
| Data Preprocessing | 1/2 day | Done⏳ |
| Model Development | 1 days | Done ⏳ |
| Model Evaluation | 1/2 day | Done ⏳ |
| Documentation | 1/2 day | Done ⏳ |

## 🧪 Steps

- **EDA**: Imbalance check, time analysis
- **Preprocessing**: Normalize, create time-based features
- **Modeling**:
    - Logistic Regression
    - Random Forest
    - XGBoost
    - SMOTE + undersampling
- **Evaluation**:
    - AUC
    - Recall
    - Confusion Matrix
- **Visuals**:
    - ROC Curve
    - Precision-Recall Curve
    - SHAP values (optional)

Anomaly detection: use one class data in order to predict fraudulent transactions 

## 📄 README Template

```markdown
### Fraud Detection
Built a model using XGBoost with SMOTE to detect rare fraud cases. Focused on recall and AUC for performance. Visualized model results with ROC & PR curves.
```
