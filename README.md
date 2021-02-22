# Sales-Forecast
Using Facebook Prophet And Apache Spark- Data Bricks

FB Prophet : Forecast Procedure Library 

Open-source library
Automatic forecasting of time series data
Generalized additive model (GAM)
Works best with time series that have strong seasonal effects and several seasons of historical data.

Data scheme- Date ,Store ,Item ,Sale
Data Source - Kaggle (5-years of store-item unit sales data for 50 items across 10 different stores)

Workflow
Install FBProphet Library
Create schema for Training dataset and import file into Data Frame.
Examine annual , monthly and weekly in unit sale
Train the model FBPhorphet to fit and Assemble data frame in Pandas
Predict and plot the Forecast
Evaluate the forecast
Train the model and generate Store-Item forecast using Pandas user-defined function (UDF)
Create table using Delta and visualize the prediction result

