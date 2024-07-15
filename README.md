# TSA-of-All-India-Commodities-Price-index
Time Series Analysis of All India Price Index up till January 2019.

#### Data Source: 
https://www.data.gov.in/resource/all-india-consumer-price-index-ruralurban-upto-january-2019

- Data from Department Ministry of Statistics and Programme Implementation.
- Price Index of various commodities present in data.
- For my study, I used Fuel and Light Index, any other commodity can be used from the data.

Models Used:
- Average
- Naive
- Seasonal
- Naive
- Drift
- AutoARIMA
- Prophet

#### Based on the error metrics provided for different forecasting models, the Prophet model demonstrates the best performance across all error metrics.

- MAE (Mean Absolute Error): Prophet has the lowest MAE at 3.2, indicating it has the smallest average absolute errors among the models.
- MAPE (Mean Absolute Percentage Error): Prophet also has the lowest MAPE at 2.45%, showing its superior accuracy in terms of percentage errors.
- MSE (Mean Squared Error): With the lowest MSE of 15.17, Prophet indicates that it has the smallest squared errors, making it the most precise model.
- In comparison to other models, Prophet consistently outperforms, making it the most reliable choice for forecasting in this context.

### Libraries Needed:

```text
pandas
numpy
matplotlib
seaborn
warnings
datetime
statsforecast
statsmodels
tabulate
prophet
scikit-learn
```


