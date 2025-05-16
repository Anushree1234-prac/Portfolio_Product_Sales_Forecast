# Portfolio_Product_Sales_Forecast
# Product Sales Forecasting Project

This project forecasts product sales using a Random Forest Regression model.

## Files

* `product_sales_forecast.ipynb`: Google Colab notebook containing the data preprocessing, model training, and evaluation code.

## How to Use

Open and run the `product_sales_forecast.ipynb` notebook in Google Colab.

## Libraries Used

* pandas
* numpy
* scikit-learn

## Data Preprocessing

* Handled missing values (none found).
* Extracted date features (Year, Month, Day, DayOfWeek).
* Encoded the 'Discount' column.
* One-hot encoded categorical features ('Store_Type', 'Region_Code', 'Location_Type').
* Dropped non-categorical object columns ('ID', 'Year').

## Model

* Random Forest Regressor (`n_estimators=100`, `random_state=42`).

## Evaluation

* **Train RMSE:** 1062.96

This project demonstrates a basic sales forecasting workflow. Further improvements could involve feature engineering, hyperparameter tuning, and exploring other models.
