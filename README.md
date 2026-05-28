# Customer Churn Prediction — ML Model Comparison 📊

> **Comparative analysis of Logistic Regression, Random Forest, 
> and XGBoost for customer churn prediction in the 
> telecommunications industry**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Research](https://img.shields.io/badge/Research-SSRN-orange)](https://ssrn.com)

---

## 📌 Overview

This repository contains the complete code and analysis for the 
research paper:

**"A Comparative Analysis of Machine Learning Models for Customer 
Churn Prediction in the Telecommunications Industry: A Business 
Analytics Perspective"**

> Submitted to SSRN and IARIA DATA ANALYTICS 2026 International 
> Conference, Barcelona, Spain

Customer churn — when customers stop using a service — costs 
telecommunications companies billions annually. This study 
systematically compares three machine learning models to identify 
the most effective approach for enterprise churn prediction.

---

## 🔑 Key Finding

**Logistic Regression outperformed more complex ensemble methods** 
across four of five evaluation metrics — challenging the assumption 
that algorithmic complexity always leads to better performance on 
structured business datasets.

---

## 📊 Results

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---|---|---|---|---|
| **Logistic Regression** | **79.91%** | **0.6426** | 0.5481 | **0.5916** | **0.8403** |
| Random Forest | 79.21% | 0.6373 | 0.5027 | 0.5620 | 0.8225 |
| XGBoost | 77.86% | 0.5957 | **0.5160** | 0.5530 | 0.8185 |

---

## 📁 Repository Structure

customer-churn-prediction-ml/
├── churn_prediction.ipynb      # Full analysis notebook
├── churn_model_comparison.png  # Model performance charts
├── feature_importance.png      # Feature importance analysis
└── README.md

---

## 🗂️ Dataset

**IBM Telco Customer Churn Dataset**
- 7,043 customer records
- 20 predictor features
- Binary target: churned or not
- Available on Kaggle: kaggle.com/datasets/blastchar/telco-customer-churn

---

## 🛠️ How To Run

1. Open `churn_prediction.ipynb` in Google Colab or Jupyter
2. Install dependencies:
```python
!pip install xgboost
```
3. Run all cells in order
4. Results and charts generate automatically

---

## 🧠 Models Compared

**Logistic Regression** — interpretable baseline model using 
logistic sigmoid function for binary classification

**Random Forest** — ensemble of 100 decision trees using 
bagging and random feature selection

**XGBoost** — gradient boosting framework building trees 
sequentially to minimize prediction error

---

## 📈 Visualizations

### Model Performance Comparison
![Model Comparison](churn_model_comparison.png)

### Feature Importance (XGBoost)
![Feature Importance](feature_importance.png)

---

## 🔬 Research Paper

This code accompanies the research paper submitted to:
- **SSRN** — Social Science Research Network (May 2026)
- **IARIA DATA ANALYTICS 2026** — Barcelona, Spain (Under Review)

---

## 👩‍💻 Author

**Vishakha FNU**
MBA Candidate, Business Analytics | BS, Computer Engineering
California State University, Fullerton

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/fnuVishakha)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/fnuVishakha)

---

## 📄 License

MIT License — free to use with attribution

---

*If this research was helpful please give it a ⭐ — 
it supports ongoing research in business analytics!*
