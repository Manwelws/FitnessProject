# 🏋️ Fitness Classification Model

## Overview
A binary classification project to predict whether an individual is physically fit based on health and lifestyle indicators.

## Dataset
- **Features:** Age, Height, Weight, Heart Rate, Blood Pressure, Sleep Hours, Nutrition Quality, Activity Index, Smoking Status, Gender
- **Target:** `is_fit` (1 = Fit, 0 = Not Fit)
- **Challenge:** Class imbalance addressed using SMOTE + TomekLinks

## Approach
1. **EDA** — distribution analysis, class balance check
2. **Preprocessing** — missing value handling, encoding, feature selection (SelectKBest)
3. **Modeling** — benchmarked 8 classifiers: Logistic Regression, Naive Bayes, Decision Tree, KNN, SVC, Random Forest, Gradient Boosting, and a Stacking Classifier
4. **Tuning** — GridSearchCV / RandomizedSearchCV for hyperparameter optimization

## Results
| Model | Accuracy |
|---|---|
| Stacking Classifier | **83.2%** |
| Naive Bayes | **82.7%** |
| SVC | **82.2%** |
| Logistic Regression | **82.2%** |
| GradientBoostingClassifier | **78.1%** |
| KNN | **77.9%**|
| Random Forest | **74.8%** |
| Decision Tree | **73.0&%** | 

> Fill in the accuracy column from your model comparison bar chart

## Tools
`Python` `Scikit-learn` `Imbalanced-learn` `Pandas` `Matplotlib` `Seaborn`
