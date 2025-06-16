# Titanic Survival Prediction – Kaggle Competition

This repository contains two end-to-end machine learning projects based on the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic). The goal is to predict which passengers survived the Titanic disaster.

---

## 🔍 Project Overview

This project showcases my growth in data science and machine learning. It includes:

- A **baseline model** using basic preprocessing and Random Forest
- An **improved model** with full feature engineering and exploratory data analysis
- Evaluation using accuracy, confusion matrix, and classification report
- Kaggle submission for both versions

---

## 📁 Files

| File Name                             | Description                                  |
|--------------------------------------|----------------------------------------------|
| `baseline_model.ipynb`               | Simple model with minimal preprocessing      |
| `feature_engineered_model.ipynb`     | Enhanced model with feature engineering      |
| `titanic_baseline_submission.csv`    | Kaggle submission from baseline model        |
| `titanic_feature_engineered_submission.csv` | Kaggle submission from advanced model         |

---

## ✅ Results Summary

| Model Version            | Local Validation Accuracy | Kaggle Public Score |
|-------------------------|---------------------------|---------------------|
| Baseline Model          | ~82%                      | **0.77751**         |
| Feature Engineered Model| ~88%                      | **0.73684**         |

---

## 📊 What I Learned

- The importance of avoiding data leakage during preprocessing
- How overfitting shows up when validation accuracy doesn't reflect public test scores
- Trade-offs between model complexity and generalization
- How feature engineering can both help and hurt performance
- Real-world evaluation with metrics like confusion matrix and F1-score

---

## 🔧 Tools Used

- Python, Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📬 Next Steps

- Try hyperparameter tuning (GridSearchCV)
- Experiment with XGBoost or Gradient Boosting
- Learn about cross-validation for better validation splits

---

## 💼 Portfolio Value

This project is part of my ongoing journey into data science and machine learning. It demonstrates my ability to:
- Handle end-to-end ML workflows
- Identify and avoid pitfalls like data leakage
- Interpret results beyond accuracy
- Continuously improve models through iteration

