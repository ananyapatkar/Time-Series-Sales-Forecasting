#  Time Series Sales Forecasting

## Project Overview
This project performs time series forecasting on store item sales data using Python.
The objective is to analyze historical sales trends and predict future sales using statistical time series models.

## Dataset
Store Item Demand Forecasting Dataset
Columns:
- date
- store
- item
- sales

For modeling, Store 1 and Item 1 were selected.

## Tools & Libraries Used
- Python (Google Colab)
- pandas
- matplotlib
- statsmodels
- numpy
  
## Project Workflow

1. Data Loading & Preprocessing
2. Date Conversion & Indexing
3. Monthly Aggregation
4. Trend Visualization
5. Rolling Mean (Seasonality Check)
6. Train-Test Split
7. Exponential Smoothing Model
8. Forecast Prediction
9. Error Evaluation (MAE & MAPE)
10. Export Forecast Results

##  Model Used
Holt-Winters Exponential Smoothing
- Additive Trend
- Additive Seasonality
- Seasonal Period = 12
- 
## Performance Metrics
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)

Lower MAE and MAPE indicate better prediction accuracy.
