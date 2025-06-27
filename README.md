# Housing Price Prediction

This notebook walks through a simple baseline Ridge Regression model to predict housing prices.

## Dataset

Linked here: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

The target variable is `price`, which is log-transformed for modeling.

## Project Overview

- Performs EDA to understand feature distributions and relationships.
- A Ridge Regression model was chosen to handle multicollinearity and preserve all feature contributions.
- Numeric features are scaled and categorical features are one-hot encoded in a pipeline.
- The model is evaluated using cross-validation and a holdout test set.

## Files

- `housing_model.ipynb`: Main notebook with EDA, model training, and evaluation
- `figures/`: Folder with EDA & performance visualizations

## Limitations of Baseline Model
- No hyperparamter tuning, default Ridge settings used
- May not generalize well due to small dataset size
- Minimal feature engineering