# McDonald's Nutrition Facts Analysis

This project explores the McDonald's Nutrition Facts dataset from Kaggle. The goal is to clean, preprocess, and analyze the nutritional information of McDonald's menu items, applying various machine learning techniques to predict and interpret data. The analysis includes handling missing data, performing imputation, evaluating model performance, and explaining model predictions using SHAP values.

## Project Overview

This repository contains the code and analysis for predicting nutritional values such as calories, fat content, and other dietary metrics of McDonald's menu items. The notebook includes various steps including:
- **Data Cleaning**: Handling missing values and removing outliers.
- **Imputation**: Applying methods like mean, median, and KNN to impute missing values.
- **Model Training**: Training regression models such as Random Forest and H2O AutoML for predicting nutritional values.
- **Model Evaluation**: Evaluating model performance with metrics like RMSE, MAE, and R^2.
- **SHAP Analysis**: Using SHAP (SHapley Additive exPlanations) to interpret model predictions and understand feature importance.

## Dataset

The dataset used for this project can be found on Kaggle:  
[McDonald's Nutrition Facts Dataset](https://www.kaggle.com/datasets/mcdonalds/nutrition-facts)

It contains nutritional data on various items from McDonald's menu, including details like:
- **Calories**
- **Total Fat**
- **Sodium**
- **Carbohydrates**
- **Protein**
- **Sugar**
- **Serving Size**

## Requirements

To run the notebook and recreate the analysis, make sure to install the following Python packages:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `shap`
- `h2o`

You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap h2o
