# Predictive-Analysis-Forecasting

Forecasting is a crucial aspect of data analysis that involves using historical data and statistical models to make predictions about future values or trends. In the context of this project, forecasting aims to predict future mobility patterns in King County based on past data points. The project employs two main forecasting techniques: Exponential Smoothing (ES) and Autoregressive Integrated Moving Average (ARIMA).

### Overview

This repository contains the code implementation for a forecasting project using mobility data provided by Google, specifically focusing on the King County region. The dataset spans the period from 2020 to 2022 and includes information on residential, work, and grocery/pharmacy mobility. The project involves time series analysis, decomposition, and forecasting using Exponential Smoothing (ES) and Autoregressive Integrated Moving Average (ARIMA) models.

### Project Tasks

1. Data Compilation:
Combine all data from 2020 to 2022 into one dataframe, focusing on King County.
2. Time Series Trimming:
Remove months before April 2020 to exclude early pandemic and pre-pandemic conditions.
3. Time Series Decomposition:
Perform an additive Time Series Decomposition for each of the three time series (Residential, Work, Grocery/Pharmacy).
Plot the results, showcasing trend, seasonality, and remainder components.
4. Exponential Smoothing (ES) Modeling:
Build forecasting models using Exponential Smoothing (ES) for each time series.
Test at least two different ES models.
Use forecast evaluation metrics (e.g., MAE, RMSE) to justify the choice of the best ES model.
5. ARIMA Modeling:
Build forecasting models using Autoregressive Integrated Moving Average (ARIMA) for each time series.
Demonstrate the reasoning behind the selection of the ARIMA model.
6. Model Comparison:
Compare the best ES and ARIMA models for each time series using forecast evaluation metrics.
Determine and show which model performs better in each case.
7. Future Forecasting:
Using the best model for each time series, forecast the rest of 2022.
Display these forecasts by plotting past data points in one color and future data points in a second color.

### Dependencies

Python

Required libraries: NumPy, Pandas, Matplotlib, Statsmodels, Scikit-learn, Sklearn

Feel free to explore the code files for detailed implementation and results. If you encounter any issues or have questions, please refer to the documentation or contact me.

