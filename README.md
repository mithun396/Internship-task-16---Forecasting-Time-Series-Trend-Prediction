# Internship-task-16---Forecasting-Time-Series-Trend-Prediction

## Objective
To perform time-series forecasting on historical sales data to predict future sales and support business planning decisions.

## Tools & Libraries Used
- Python Jupyter Notebook
- pandas
- numpy
- matplotlib
- statsmodels (Exponential Smoothing)
- scikit-learn (MAE)

## Dataset
File Used:
stores_sales_forecasting.csv

## Project Steps
- Loaded dataset using pandas.
- Converted date column into datetime format.
- Sorted data chronologically.
- Aggregated sales monthly using groupby.
- Visualized sales trend over time.
- Applied rolling mean to analyze trend smoothing.
- Split data into training (80%) and testing (20%) sets.
- Built forecasting model using Exponential Smoothing.
- Generated predictions for the test period.
- Evaluated performance using:
--  MAE (Mean Absolute Error)
-- MAPE (Mean Absolute Percentage Error)
- Exported forecast results to CSV.

## Conclusion
This project demonstrates practical implementation of time-series forecasting used in real-world business planning.
The forecasting model can be further improved by adding seasonal components or advanced models like ARIMA for better accuracy.

MAE (Mean Absolute Error)

MAPE (Mean Absolute Perce
