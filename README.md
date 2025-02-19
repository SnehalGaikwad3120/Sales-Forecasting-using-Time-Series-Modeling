# Sales-Forecasting-using-Time-Series-Modeling
This project focuses on time-series forecasting of beer sales using the SARIMA (Seasonal ARIMA) model. The objective is to analyze historical sales trends and 
predict demand for 2019 and 2020, helping businesses optimize inventory management and supply chain planning.
 Analyze historical sales trends & seasonality

* Objectives
  
- Identify stationarity in data using ADF Test
- Build a robust SARIMA model for forecasting
- Evaluate model performance using MSE, RMSE, and MAPE
- Provide actionable insights for demand planning

* Dataset Information
  
- The dataset contains monthly beer sales data from 1992 to 2018.
- It includes a date column and corresponding beer sales values.
- The goal is to predict 24 months (2019-2020) of future sales.

* Exploratory Data Analysis (EDA)

The time series shows a consistent upward trend 
There is a clear seasonal pattern (peaks and dips at regular intervals)

* Data Preprocessing:
  
-  Converted the date column to a datetime index
-Applied log transformation & seasonal differencing to handle trends

* Model Building & Evaluation
  
- Model Training:
Used Auto-ARIMA to identify optimal parameters
Trained a SARIMA model with seasonal components

* conclusion
  
  successfully developed a time-series forecasting model to predict beer sales for 2019-2020 using SARIMA.
 By analyzing historical trends and seasonality (1992-2018), the model achieved a 96.61% accuracy,with a low MAPE of 3.38%, ensuring reliable demand forecasting.
