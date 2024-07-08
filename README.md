# Time Series and Forecasting

## School: Computer Science
## Academic Year: 2023-24

## Project Title
**Time Series and Forecasting**

### Module Code
MATH4022

## Project Overview
This project involves a comprehensive analysis of two distinct datasets: the annual mean temperatures from 1900 to 2021 for the Midlands region of England, and monthly average house prices from January 2010 to December 2019 in the East Midlands. The objective is to model these time series datasets to identify trends and predict future values using ARIMA models and other statistical techniques.

### Key Analyses
1. **Temperature Time Series Analysis**
   - **Objective**: Model the historical time series of annual mean temperatures to identify trends and forecast future temperatures.
   - **Methodology**: Utilized ARIMA modeling techniques, conducting exploratory data analysis and stationarity testing using the Augmented Dickey-Fuller (ADF) test.
   - **Key Findings**: Revealed a clear upward trend in temperatures over the last century, with the ARIMA model showing high predictive accuracy.

2. **House Price Forecasting**
   - **Objective**: Forecast the monthly average house prices for the first half of 2020 using historical data.
   - **Methodology**: Applied ARIMA and SARIMA models after preliminary data decomposition to identify trends and seasonality.
   - **Key Findings**: Successfully captured seasonal patterns and trends, predicting a moderate increase in house prices for the first six months of 2020.

## Data Description
### Temperature Dataset
- **Source**: UK Meteorological Office Hadley Climate Centre
- **Variables**: 
  - `year`: Years from 1900 to 2021
  - `avg_annual_temp_C`: Annual mean temperatures in °C

### House Price Dataset
- **Variables**:
  - `date`: Monthly records from January 2010 to December 2019
  - `avg_house_price`: Monthly average house prices in GBP

## Methodology
### Temperature Time Series Analysis
1. **Data Loading and Structure**
   - Loaded and structured the dataset using R.
   - Visualized the time series data to identify trends.

2. **Stationarity Test and Transformation**
   - Conducted the ADF test to check for stationarity.
   - Applied necessary transformations to achieve stationarity.

3. **Model Selection**
   - Utilized ACF and PACF plots to guide the selection of ARIMA model parameters.
   - Compared AR and ARIMA models using AIC, BIC, MAPE, and RMSE.

4. **Model Diagnostics and Forecasting**
   - Conducted residual analysis to ensure model adequacy.
   - Forecasted future temperatures using the ARIMA model.

### House Price Forecasting
1. **Data Loading and Structure**
   - Loaded and structured the house price dataset.
   - Performed exploratory data analysis to identify trends and seasonality.

2. **Model Selection**
   - Tested various ARIMA and SARIMA models.
   - Selected the best model based on AIC and BIC values.

3. **Validation and Forecasting**
   - Validated the model using residual diagnostics and prediction intervals.
   - Forecasted house prices for the first half of 2020.

## Key Findings
- **Temperature Analysis**: The ARIMA model indicated a statistically significant upward trend in temperatures over the century.
- **House Price Forecasting**: The SARIMA model effectively forecasted short-term house price trends, providing valuable insights for economic planning.

## Conclusion
The analyses demonstrate the robustness of statistical modeling in predicting future trends based on historical data. The findings have significant implications for environmental policy and economic planning.

## Future Work
- **Temperature Analysis**: Incorporate additional climatic factors and explore seasonal ARIMA models for improved accuracy.
- **House Price Forecasting**: Include exogenous variables such as interest rates and employment data to enhance model predictions.

## References
1. Wickham, H. (2016). ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York.
2. Hyndman, R.J., & Khandakar, Y. (2008). Automatic time series forecasting: the forecast package for R. Journal of Statistical Software.
3. Trapletti, A., & Hornik, K. (2020). tseries: Time Series Analysis and Computational Finance. R package version 0.10-47.
4. Hyndman, R.J., & Athanasopoulos, G. (2018). Forecasting: principles and practice. OTexts: Melbourne, Australia.
5. Kuznetsova, A., Brockhoff, P. B., & Christensen, R. H. B. (2017). lmerTest Package: Tests in Linear Mixed Effects Models. Journal of Statistical Software.
6. Zeileis, A., & Grothendieck, G. (2005). zoo: S3 Infrastructure for Regular and Irregular Time Series. Journal of Statistical Software.
7. UK Meteorological Office Hadley Climate Centre. (2023). UK regional climates data set.

## Appendices
- **Appendix A**: R Code for Temperature Analysis
- **Appendix B**: R Code for House Price Forecasting

---

Feel free to contribute to this project by creating issues or submitting pull requests.
