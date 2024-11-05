# Diabetes Blood Glucose Prediction

## Project Overview

This project aims to predict blood glucose levels in patients based on various medical predictor variables using linear regression. The dataset used for this analysis is derived from the National Institute of Diabetes and Digestive and Kidney Diseases, focusing on female patients of Pima Indian heritage.

## Objectives

- **Predict blood glucose levels** using medical predictor variables.
- **Clean and preprocess the data** to ensure valid inputs.
- **Train a linear regression model** and evaluate its performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).

## Dataset

The dataset consists of the following features:
- **Pregnancies**: Number of times pregnant.
- **Glucose**: Blood glucose level (target variable).
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skin fold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body Mass Index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: Diabetes pedigree function.
- **Age**: Age (years).

### Data Cleaning Steps

1. Replaced zero values in certain columns with `NaN`.
2. Set realistic ranges for each variable and replaced out-of-range values with `NaN`.
3. Filled missing values with the median of their respective columns.

## Installation

To run this project, ensure you have the following libraries installed:

```bash
pip install pandas numpy scikit-learn

Usage
Clone this repository or download the files.
Place the diabetes dataset CSV file in the project directory.
Update the path to the dataset in the code.
Run the Python script using:
python3  diabetes_prediction.py

The performance of the model is evaluated using the following metrics:

Mean Absolute Error (MAE): Average of the absolute differences between predicted and actual values.
Mean Squared Error (MSE): Average of the squared differences between predicted and actual values.
Root Mean Squared Error (RMSE): Square root of the MSE, giving a measure of the average error in the same units as the target variable.
R-squared (R²): Proportion of variance in the dependent variable that can be explained by the independent variables.

NB: This project is for my Y2T2 final term project , l am not yet a pro! and l am open to corrections- Thank you!
