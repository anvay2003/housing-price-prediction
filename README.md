# Housing Price Prediction

Predicting house prices using **Linear Regression, Ridge Regression, and Random Forest Regression** with preprocessing and hyperparameter tuning.

---

## 🏗️ Project Overview

This project demonstrates how to build a **predictive modeling pipeline** for regression tasks on the Kaggle Housing Dataset. The workflow includes:

- Data preprocessing (handling missing values, scaling, encoding categorical variables)
- Training multiple regression models
- Hyperparameter tuning using GridSearchCV
- Model evaluation using RMSE and R² metrics

---

## 📊 Tech Stack

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn (for visualization)

---

## 🔧 Features

- **Pipeline implementation** to streamline preprocessing and model training
- **ColumnTransformer** to apply different preprocessing for numeric and categorical features
- **Hyperparameter tuning** for Random Forest to optimize performance
- **Performance metrics:** RMSE and R²

---

## 💻 Model Performance

| Model | RMSE | R² |
|-------|------|----|
| Linear Regression | 29,476 | 0.89 |
| Ridge Regression  | 29,844 | 0.88 |
| Random Forest     | 28,528 | 0.89 |

**Random Forest Best Hyperparameters:**
```python
{'max_depth': 10, 'min_samples_split': 2, 'n_estimators': 100}
