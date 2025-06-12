## 🔌 Electricity Demand Forecasting – Project Overview
#### 📍 Business Context
A leading electricity distribution company seeks to forecast monthly electricity consumption for the next 2 years to support strategic planning, optimize electricity procurement, and manage generation capacities efficiently. Reliable demand estimation is crucial for balancing supply with demand and minimizing operational costs.

-------------------
#### 🎯 Objective
Forecast monthly electricity demand (in Trillion Watts) for the years 2020 and 2021, based on historical consumption data from January 1973 to December 2019.

Evaluate and compare multiple time series forecasting models.

Identify the most accurate and reliable model for long-term forecasting.

Provide interpretable metrics and visualizations to justify model selection.

------------------------
#### 🗃️ Dataset
Source: Internal company records

Timeframe: January 1973 – December 2019 (Monthly frequency)

Variables:

Date: Month & Year

Consumption: Monthly electricity usage in Trillion Watts

-----------------
#### 🧠 Approach
Exploratory Data Analysis (EDA) to understand consumption patterns and seasonality.

Data Preprocessing, including frequency standardization and checking for missing values.

Time Series Decomposition to isolate trend and seasonal components.

Model Development & Comparison using:

ETS (Exponential Smoothing)

SARIMA (Seasonal ARIMA)

Naive & baseline models for benchmarking

Model Evaluation using RMSE, MAPE, and RMSPE.

Forecasting for 2020–2021 using the best-performing model.

Final model justification with performance metrics and residual diagnostics.

--------------------
#### ✅ Key Findings
SARIMA model outperformed other models with the lowest forecasting errors.

Demonstrated strong capability in modeling both trend and seasonal cycles.

Residual analysis confirmed a good fit with no significant autocorrelation.

--------------
#### 📈 Outcome
Forecasts provided for each month from Jan 2020 to Dec 2021.

SARIMA model selected for deployment due to its accuracy, interpretability, and robustness.
