# Task 2: Exploratory Data Analysis (EDA) Report

## 1. Dataset Overview

**Dataset Name:** Bike Sharing Dataset  
**Analysis Type:** Exploratory Data Analysis (EDA)  
**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn  
**Environment:** Google Colab

The Bike Sharing Dataset contains hourly bike rental records along with weather conditions, seasonal information, and time-related features.

- Total Records: 17,379
- Total Columns: 19 (after adding season_name and weather_name)
- Date Range: 2011–2012
- Missing Values: 0
- Target Variable: `cnt` (Total Bike Rentals)

## 2. Data Preparation

The following preprocessing steps were performed:

1. Loaded and inspected the dataset.
2. Checked data types and missing values.
3. Converted `dteday` into datetime format.
4. Converted categorical variables into category data types.
5. Added descriptive columns: `season_name` and `weather_name`.
6. Verified that no missing values remained.

## 3. Key Statistical Findings

| Feature | Mean | Standard Deviation |
|---|---:|---:|
| Temperature | 0.497 | 0.193 |
| Humidity | 0.627 | 0.193 |
| Windspeed | 0.190 | 0.122 |
| Casual Rentals | 35.68 | 49.31 |
| Registered Rentals | 153.79 | 151.36 |
| Total Rentals | 189.46 | 181.39 |

**Key Findings:**
- Average hourly bike rentals are approximately 189.
- Registered users contribute more rentals than casual users.
- Maximum hourly bike rentals recorded were 977.

## 4. Visualizations and Observations

### 4.1 Distribution of Total Bike Rentals

- Most observations have relatively low rental counts.
- The distribution is positively skewed.
- A smaller number of observations have very high rental counts.

### 4.2 Bike Rentals by Season

- Fall shows the highest median bike rental demand.
- Summer also has comparatively high rental demand.
- Spring has the lowest median rental demand.

### 4.3 Temperature Distribution

- Temperature values are distributed across a broad range.
- Most observations fall within the middle temperature range.
- The distribution is approximately balanced.

### 4.4 Bike Rentals by Weather

- Clear weather has the highest median rental demand.
- Cloudy conditions show comparatively lower demand.
- Rainy and snowy conditions generally have lower rental counts.

### 4.5 Correlation Heatmap

- Registered rentals have a very strong positive correlation with total rentals (0.972).
- Casual rentals also have a positive correlation with total rentals (0.695).
- Temperature has a moderate positive correlation with total rentals (0.405).
- Humidity has a negative correlation with total rentals (-0.323).
- Windspeed has a very weak positive correlation with total rentals (0.093).

### 4.6 Bike Rentals by Hour

- Rental demand is lowest during early morning hours.
- Demand increases during morning commuting hours.
- The highest average demand occurs around 5 PM (17:00).
- Rentals gradually decrease during late evening hours.

### 4.7 Working Day vs Non-Working Day

- The median rental count is slightly higher on working days.
- Both groups show considerable variation in rental demand.
- High-demand observations are present in both groups.

### 4.8 FacetGrid and Pairplot

- Hourly rental patterns show similar morning and evening peaks across seasons.
- Temperature generally has a positive relationship with bike rentals.
- Humidity tends to have a negative relationship with rental demand.
- Windspeed shows a relatively weak relationship with rental counts.

## 5. Hypotheses Tested

| Hypothesis | Observation | Result |
|---|---|---|
| Temperature affects bike rentals positively. | Positive correlation (0.405). | Supported |
| Humidity affects bike rentals negatively. | Negative correlation (-0.323). | Supported |
| Registered users contribute significantly to rentals. | Strong correlation (0.972). | Supported |
| Weather conditions influence rental demand. | Clear weather shows higher median rentals. | Supported |
| Rental demand changes throughout the day. | Morning and evening peaks are visible. | Supported |

*Note: These observations show associations, not proof of causation.*

## 6. Skewness and Kurtosis Analysis

- Casual rentals show high positive skewness (2.499).
- Registered rentals are also positively skewed (1.558).
- Total rentals have positive skewness (1.277).
- Temperature is nearly symmetric, with skewness close to zero.

This indicates that rental data contains many lower values and fewer very high values.

## 7. Outlier Detection

Two methods were used to identify outliers in total bike rentals.

| Method | Number of Outliers |
|---|---:|
| IQR Method | 505 |
| Z-Score Method | 244 |

Outliers were identified but not removed because high rental counts may represent genuine periods of high demand.

## 8. Recommendations

1. Increase bike availability during morning and evening peak hours.
2. Maintain higher bike availability during Fall and Summer.
3. Consider weather conditions when planning bike distribution.
4. Monitor high-demand locations and periods to avoid shortages.
5. Use historical rental patterns to improve demand forecasting.

## 9. Conclusion

The EDA revealed that bike rental demand varies with time, season, temperature, and weather conditions. Registered users contribute significantly to total rentals, while rental demand generally peaks during commuting hours. These insights can help improve bike availability, resource planning, and future demand prediction.

**Task 2: Exploratory Data Analysis completed successfully.**