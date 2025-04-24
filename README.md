# InsureLead
Predicting Customer Responses to Insurance Offers Using ML

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![ROC AUC Optimized](https://img.shields.io/badge/Optimized--for-ROC%20AUC-yellowgreen?style=for-the-badge)
![Optuna](https://img.shields.io/badge/Optuna-Tuning-blueviolet?style=for-the-badge)
![AUC Score](https://img.shields.io/badge/Best%20AUC-0.89690-2ECC71?style=for-the-badge)
![Rank](https://img.shields.io/badge/Rank-70%20of%202425-brightgreen?style=for-the-badge)
![Solo](https://img.shields.io/badge/Submission-Type%3A%20Solo-orange?style=for-the-badge)

### Project Duration: Feb 1, 2025 - Mar 1, 2025
---

## 🌟 Introduction

The objective is to predict which customers will respond positively to a vehicle insurance offer. This project is part of a binary classification challenge which was hosted on Kaggle. Submissions were evaluated using **Area Under the ROC Curve (AUC)**.

---

## 🥉 Top Approach

Explore full implementation here: 🔗 [PS4E7 - Stacking Boosters with ANN](https://github.com/krishnaura45/InsureLead/blob/main/ps4e7-stacking-boosters-and-ann.ipynb)

- 📊 **Data Integration & Inspection**
  - Combined official training dataset with original insurance dataset for feature enrichment.
    
- 🛠️ **Preprocessing Pipelines**
  - Utilized Scikit-learn pipelines and transformers with encoders: `StandardScaler`, `PowerTransformer`, `OneHotEncoder`, `OrdinalEncoder`.
    
- 🔍 **Feature Engineering & Selection**
  - Applied mutual information filtering to retain informative features.
    
- 🧰 **Modeling with Ensembles**
  - Trained and validated XGBoost, CatBoost, LightGBM classifiers using Stratified K-Fold CV.
  - Hyperparameter tuning with Optuna and visual exploration tools.
    
- 🏋️ **Submission Strategy**
  - Ensemble predictions via model averaging on test data.

---

## 📊 Results / Outcomes

- ✅ Public Leaderboard Scores: ranging from *0.50060* to *0.89727*

- 🏁 Best Private Score: ***0.89690**

- 🥇 Rank Achieved: Ranked 70 / 2425 participants and 2234 teams as a solo participant

![Score Progression Plot](https://github.com/user-attachments/assets/989ab79b-db3e-40ae-a7fb-ed3a040bba09)

---

## 🔗 References

- 📁 Kaggle Competition: <a href="https://www.kaggle.com/competitions/playground-series-s4e7" target="_blank">Binary Classification of Insurance Cross Selling</a><br>

- 📂 Original Dataset: <a href="https://www.kaggle.com/datasets/annantkumarsingh/health-insurance-cross-sell-prediction-data" target="_blank">Health Insurance Cross Sell Prediction Data</a>

---

## 🛠️ Tech Stack

- Language: Python 🐍

- Libraries:

  - `pandas`, `polars`, `numpy` for data handling

  - `matplotlib`, `seaborn` for EDA and plotting

  - `scikit-learn`, `xgboost`, `catboost`, `lightgbm` for modeling

  - `optuna` for hyperparameter tuning

- Tools:

  - Jupyter Notebook / Kaggle Notebooks for experimentation

  - Custom pipelines and scoring functions for AUC optimization

 ---
