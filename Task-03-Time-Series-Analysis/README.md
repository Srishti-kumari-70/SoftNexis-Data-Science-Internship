# Task 3: Time Series Analysis

## Objective
To analyze airline passenger data and forecast future passenger numbers using time series analysis techniques.

## Dataset
Air Passengers Dataset (1949–1960)

- Total Records: 144
- Frequency: Monthly
- Target Column: Passengers

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

## Tasks Performed
1. Data Loading and Inspection
2. Time Series Visualization
3. Trend and Seasonal Decomposition
4. Moving Average Analysis (6-month and 12-month)
5. Train-Test Split
6. SARIMA Model Building
7. Passenger Forecasting
8. Actual vs Predicted Comparison
9. RMSE Evaluation

## Model Performance
- Model: SARIMA
- Order: (2, 1, 1)
- Seasonal Order: (1, 1, 1, 12)
- RMSE: 21.17

## Conclusion
The analysis identified an increasing trend and yearly seasonal patterns in airline passenger numbers. The SARIMA model was used to forecast passenger demand for 1960 and achieved an RMSE of approximately 21.17.

