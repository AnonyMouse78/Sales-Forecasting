# Product Sales Forecasting using Quantitative Methods

This project aims to forecast product sales utilizing various quantitative methods and time series analysis techniques. The implemented models predict sales for a given dataset obtained from Kaggle. The methods covered include Seasonal Naive, Holt-Winters Triple Exponential Smoothing, ARIMA, Seasonal ARIMA, and Linear Regression.

## Datasets Used:
1. **`train.csv`**
   - Contains historical sales data including date, store, item, and sales information.
  
2. **`test.csv`**
   - Includes sales data for a specific period, consisting of date, store, and item details.

3. **`sample_submission.csv`**
   - Submission format template for predicted sales with columns: date, store, item, predicted sales.

## Notebook Contents:
- **Data Exploration:**
  - Visualizations illustrating weekly, monthly, and yearly sales distributions.
  - Identification of trends and patterns in sales data.

- **Modeling Techniques:**
  - Implementation and evaluation of various quantitative forecasting models:
    - Seasonal Naive Model
    - Holt-Winters Model
    - ARIMA and Seasonal ARIMA Models
    - Linear Regression Model

- **Model Evaluation:**
  - Evaluation metrics used: MAE, RMSE, MAPE to assess forecast accuracy.
  - Comparison of model performance against baseline methods.

- **Supervised Machine Learning:**
  - Feature engineering and selection for Linear Regression model.
