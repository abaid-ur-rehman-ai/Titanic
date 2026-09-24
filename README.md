# Titanic Survival Prediction – Multi Model Comparison

This project predicts passenger survival on the Titanic using multiple Machine Learning models.  
The goal was to compare different algorithms and find the best performing model after hyperparameter tuning.

## Project Overview

- Dataset: Titanic (Kaggle)
- Problem Type: Binary Classification (Survived = 1 / 0)
- Approach: Train multiple models → Compare accuracy → Apply Hyperparameter Tuning

## Models Used

| Model                       | Accuracy (Before Tuning) | Accuracy (After Tuning) | 
|-----------------------------|--------------------------|-------------------------|
| Logistic Regression         | 60.0                     | 0.82                    | 
| Decision Tree               | 0.79                     | 0.82                    |
| Random Forest               | 0.82                     | 0.83                    |
| AdaBoost                    | 0.81                     | 0.80                    |
| Gradient Boosting           | 0.80                     | 0.83                    |
| XGBoost                     | 0.79                     | 0.83                    |
| Perceptron                  | 60.89%                   | --%                     |

> **Best Model:** (Random Forest)  
> **Best Accuracy:** (0.82 on Test data)

## What I Did

- Exploratory Data Analysis (EDA)
- Handled missing values
- Feature Engineering
- Train-Test Split
- Trained multiple classification models
- Compared model performance
- Applied Hyperparameter Tuning (GridSearchCV )

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

## How to Run

1. Clone the repository
2. Install requirements:
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
