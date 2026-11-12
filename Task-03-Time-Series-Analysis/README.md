# Task 3: Time Series Analysis

## Objective
To analyze airline passenger data, identify trends and seasonal patterns, and forecast passenger numbers using time series analysis techniques.

## Dataset
**Air Passengers Dataset (1949–1960)**

- Total Records: 144
- Frequency: Monthly
- Target Column: Passengers
- Time Period: January 1949 – December 1960

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

## Model Details
- Model: Seasonal ARIMA (SARIMA)
- Order: (2, 1, 1)
- Seasonal Order: (1, 1, 1, 12)
- Training Period: 1949–1959
- Testing Period: 1960
- RMSE: Approximately 21.17

**Note:** The model generated a convergence warning during fitting. Therefore, its forecasting performance should be interpreted with caution.

## Key Findings
- Passenger numbers showed an increasing trend.
- Yearly seasonal patterns were observed.
- Moving averages helped identify the long-term trend.
- The model generated forecasts for all 12 months of 1960.

## Conclusion
This project demonstrates how time series analysis can identify trends and seasonal patterns and help forecast airline passenger demand. These insights can support better planning and resource management in the airline industry.

