# Telecom Customer Churn Prediction

End-to-end machine learning project that predicts which telecom customers are likely to churn, following the 10-stage ML lifecycle.

## Highlights
- Data: Telco Customer Churn dataset (7,043 customers) — [Kaggle link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Models compared: Logistic Regression, Random Forest, Gradient Boosting, XGBoost
- Best model: Logistic Regression, ROC-AUC about 0.84, 92% recall at the recall-first threshold
- Explainability: SHAP and permutation importance
- Monitoring: PSI drift checks and retraining plan

## Pipeline
![Pipeline](images/pipeline.png)

## How to run
1. Download the dataset from Kaggle and place it next to the notebook (or upload it in Colab).
2. `pip install -r requirements.txt`
3. Open `Telco_Churn_ML_Lifecycle.ipynb` and run all cells.

## Key findings
Short tenure, month-to-month contracts and fiber-optic internet are the strongest churn drivers.

## Tools
Python, pandas, scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn
