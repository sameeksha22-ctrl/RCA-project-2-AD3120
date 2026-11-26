# Multiple Linear Regression – House Price Prediction

## Project Overview
This project uses Multiple Linear Regression to predict house prices using several input features. It also compares a multiple-feature model with a simple linear regression model that uses house area alone.

## Dataset
The dataset is a small, illustrative dataset created for this educational project. It is not real market data.

- **Area_sqft**: House area in square feet
- **Bedrooms**: Number of bedrooms
- **Age_years**: Age of the house in years
- **Price**: House price (target variable)

## Project Objectives
- Demonstrate a manual calculation of regression coefficients on a small sample.
- Train a Multiple Linear Regression model using scikit-learn.
- Compare the multiple-feature model with a single-feature model.
- Interpret coefficients while holding other features constant.
- Check multicollinearity using Variance Inflation Factor (VIF).
- Analyze residuals.
- Evaluate models using MAE, RMSE, R², and Adjusted R².
- Predict the price of a new house.

## Tools and Libraries
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## How to Run
1. Download `house_price_dataset.csv` and place it in the project folder if you want to use the CSV version of the data.
2. Open the notebook in Jupyter Notebook.
3. Run the cells in order.

The notebook version shown in the activity creates the dataset directly in code, so the CSV is provided separately for submission and optional loading.

## Model Features
- Area_sqft
- Bedrooms
- Age_years

## Target
- Price

## Disclaimer
The dataset is synthetic and intended only for learning and demonstrating regression techniques. The predictions should not be used as real property valuation estimates.
