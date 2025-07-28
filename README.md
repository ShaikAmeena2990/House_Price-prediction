# Data-Driven Real Estate Price Prediction Using ML Models

This repository contains two Jupyter Notebooks demonstrating house price prediction using various machine learning techniques, including ensemble models.


## Files Included

- `house.ipynb`: Exploratory Data Analysis (EDA) and baseline models for predicting house prices.
- `house ensemble.ipynb`: Advanced ensemble learning techniques (e.g., Voting, Stacking, Bagging, Boosting) applied to improve prediction accuracy.


## Project Overview

The goal is to predict housing prices based on multiple features like number of bedrooms, location, square footage, etc., using supervised regression algorithms. The project is split into two stages:

1. **Basic Model Training** – Linear Regression, Decision Trees, Random Forests.
2. **Ensemble Modeling** – Combining multiple models to boost performance and reduce overfitting.

## Workflow

### `house.ipynb`:
- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Training simple regression models
- Evaluation with metrics like RMSE and R²

### `house ensemble.ipynb`:
- Training ensemble models:
  - Linear Regression
  - DecosionTree Regressor
  - Random Forest Regressor
- Comparing model performance
- Final prediction and model selection


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


##  Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Key Learnings

- Handling missing values and categorical features
- Feature scaling and transformation
- Model training and hyperparameter tuning
- Ensemble learning for better generalization

