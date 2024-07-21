# Retail Store Product Demand Forecasting

This project focuses on developing a forecasting model to predict product demand in a retail store using statistical methods such as ARIMA, SARIMAX and FACEBOOK PROPHET. The models are evaluated based on their performance using the Root Mean Square Error (RMSE) metric. The dataset used for this project is the global superstore dataset spanning 4 years, and the predictions are made for the subsequent 6 months.

## Project Overview

- **Exploratory Data Analysis (EDA):** Conducted initial analysis to understand the dataset, identify trends, and detect seasonality.
- **Stationarity Testing:** Performed the Augmented Dickey-Fuller (ADF) test to check for stationarity in the time series data.
- **Model Development:** Built forecasting models using ARIMA and SARIMAX methods.
- **Parameter Optimization:** Utilized the `auto_arima` library to automatically select the optimal parameters for the models.
- **Model Evaluation:** Compared the performance of the models using the RMSE metric, with SARIMAX showing better performance in the 6-month predictions.

## Dataset

The dataset used in this project is the global superstore dataset, which contains 6 years of retail sales data. The data includes various attributes such as order date, sales, and product category.

## Results

The SARIMAX model demonstrated superior performance compared to the PROPHET and ARIMA model, achieving a lower RMSE in the 6-month forecast period. This indicates that incorporating seasonal components enhances the prediction accuracy.

## Usage

1. **Exploratory Data Analysis (EDA):**
   - Visualize the time series data to identify trends and seasonality.
   - Check for missing values and outliers.

2. **Stationarity Testing:**
   - Apply the Augmented Dickey-Fuller (ADF) test to determine if the time series data is stationary.

3. **Model Development:**
   - Develop ARIMA and SARIMAX models to forecast product demand.
   - Fit the models to the training data.

4. **Parameter Optimization:**
   - Use the `auto_arima` function to find the optimal parameters for the ARIMA and SARIMAX models.

5. **Model Evaluation:**
   - Evaluate the models using the RMSE metric.
   - Compare the performance of the ARIMA and SARIMAX models.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

