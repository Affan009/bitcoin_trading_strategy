# Bitcoin Trading Strategy: ML Model Comparison

## Overview

This project develops and compares **machine learning models to predict Bitcoin returns** using **Bitcoin price data and technical indicators**.

The workflow includes:

- **Feature Engineering**: Multi-timeframe Bitcoin lagged returns and technical indicators  
- **Model Comparison**: Linear Regression, Random Forest, MLP, SVR, etc.  
- **Feature Selection**: `SelectKBest` for feature importance analysis  
- **Model Optimization**: Random Forest hyperparameter tuning  
- **Backtesting Setup**: Generate trading signals from predictions

---

## Methods

- **Target**: Bitcoin log returns  
- **Features**: Bitcoin lagged returns + technical indicators (momentum, trend, etc.)  
- **Validation**: Sequential train-test split  
- **Tools**: `scikit-learn`, `numpy`, `pandas`, `matplotlib`

Credits: This project was made possible through the following resource: Machine Learning and Data Science Blueprints for Finance (Book)
