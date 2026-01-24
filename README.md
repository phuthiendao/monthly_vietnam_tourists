# Monthly Vietnam Tourists Analysis and Forecasting

This project focuses on the analysis and forecasting of monthly time series data on the number of international tourists arriving in Vietnam from 2013 to 2024. The dataset spans from January 2013 to December 2024 and includes four main columns representing different modes of entry. The data is sourced from the Vietnam National Authority of Tourism website: [Vietnam National Authority of Tourism](https://vietnamtourism.gov.vn/statistic/international).

### Result Forecast

| Category | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Cruise | 35,980 | 45,519 | 37,150 | 23,661 | 15,872 | 5,822 | 1,556 | 5,418 | 4,685 | 12,352 | 13,296 | 52,545 |
| Road | 209,122 | 241,728 | 208,624 | 245,873 | 258,564 | 198,332 | 225,048 | 106,637 | 240,188 | 260,548 | 120,800 | 319,164 |
| Aviation | 1,848,221 | 1,794,729 | 1,769,647 | 1,482,531 | 1,345,973 | 1,203,876 | 1,370,295 | 1,597,402 | 1,433,248 | 1,493,216 | 1,703,247 | 1,766,018 |
| Total | 2,093,322 | 2,081,976 | 2,015,421 | 1,752,065 | 1,620,408 | 1,408,030 | 1,596,898 | 1,843,719 | 1,678,122 | 1,766,117 | 2,054,859 | 2,137,727 |


### Data Description:
The dataset includes the following columns:

- **Cruise**: Number of tourists arriving by cruise ships.
- **Road**: Number of tourists entering via land borders.
- **Aviation**: Number of tourists arriving by air.
- **All**: Total number of tourists (sum of all modes).

### Objective:
The primary objective of this project is to gain deeper insights into tourism trends over time. The project employs both descriptive and inferential statistical analyses to examine the data and draw meaningful conclusions.

### Data Preprocessing:
To ensure data quality and model performance, several preprocessing techniques are applied:

- **Handling Missing Values**: Appropriate imputation techniques are used to handle missing data points.
- **Seasonality and Trends**: Time series analysis is conducted to identify seasonal patterns and long-term trends.
- **Outliers Detection**: Outliers are identified and addressed to avoid skewed results.

### Time Series Forecasting:
Various time series forecasting models, such as ARIMA, Exponential Smoothing are implemented to predict monthly tourist arrivals for the year 2025. The predictions are segmented by each mode of entry (Cruise, Road, Aviation).

### Insights and Applications:
The results of this analysis can provide valuable insights for stakeholders in the tourism industry, including:

- **Tourism Planning**: Helping policymakers and businesses plan for fluctuations in tourist numbers.
- **Tourism Development**: Identifying high-demand months and regions to focus development efforts.
- **Marketing Strategies**: Assisting in the design of targeted marketing campaigns based on predicted trends.

By forecasting tourism trends for 2025, this project can contribute to better decision-making in tourism planning and development in Vietnam.

### Tools and Libraries Used:
- **Python**: For data analysis and model implementation.
- **Pandas, Numpy**: For data manipulation and cleaning.
- **Matplotlib, Seaborn**: For data visualization.
- **Statsmodels**: For time series analysis and forecasting.

### Conclusion:
This project provides a comprehensive analysis of international tourist arrivals to Vietnam and forecasts future trends, offering essential insights for the tourism industry.

