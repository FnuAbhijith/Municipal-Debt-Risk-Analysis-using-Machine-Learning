# Municipal-Debt-Risk-Analysis-using-Machine-Learning

This project predicts bad debt in South African municipalities using machine learning models like CatBoost, MLP, and Random Forest.

## 🎯 Goal

To help municipalities identify customers likely to default on payments using billing and receipting history data, enabling early intervention.

## 🧠 Key Features

- Models used: CatBoost, Random Forest, MLPClassifier
- Best model: CatBoost (AUC = 1.0)
- End-to-end pipeline: Preprocessing → Modeling → Evaluation
- Visualizations: ROC Curve, Confusion Matrix, Debt Analysis

## 📂 Dataset

- Source: Kaggle  
- 2 years of financial records from 8 South African municipalities  
- [Kaggle Dataset](https://www.kaggle.com/datasets/thedevastator/unpaid-debts-in-municipalities)

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- CatBoost, SHAP, Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Results Summary

| Model         | AUC Score | False Positives | False Negatives |
|---------------|-----------|------------------|------------------|
| CatBoost      | 1.0       | 0                | 56               |
| MLP Classifier| 0.99      | 2                | 847              |
| Random Forest | ~1.0      | Higher than CatBoost|


## 🚀 How to Run

```bash
git clone https://github.com/YOURUSERNAME/municipal-debt-risk-analysis.git
cd municipal-debt-risk-analysis
pip install -r requirements.txt
jupyter notebook



