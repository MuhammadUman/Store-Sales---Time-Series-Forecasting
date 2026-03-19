Store Sales - Time Series Forecasting

A machine learning project to predict product family sales across Favorita grocery stores in Ecuador using time series forecasting techniques.
Problem Statement
Predict sales for thousands of product families sold at Favorita stores in Ecuador. Accurate forecasting helps reduce food waste, optimize inventory, and improve customer satisfaction.
Dataset
Data sourced from the Kaggle Store Sales Forecasting Competition, containing six files:

train.csv — Historical sales data with store number, product family, promotions, and target sales values
test.csv — 15 days of data following the training period, used for final predictions
stores.csv — Store metadata including city, state, type, and cluster grouping
oil.csv — Daily oil prices covering both train and test periods (Ecuador's economy is highly oil-dependent)
holidays_events.csv — National holidays and events with transfer and bridge day information
transactions.csv — Daily transaction counts per store

Key Observations

Public sector wages are paid on the 15th and last day of each month, influencing supermarket traffic
A 7.8 magnitude earthquake hit Ecuador on April 16, 2016, significantly disrupting sales for weeks
Transferred holidays behave more like normal days and require careful handling
Oil prices serve as a macroeconomic indicator affecting consumer spending patterns
