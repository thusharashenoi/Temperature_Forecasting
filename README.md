# Temperature_Forecasting_using Prophet_model
Problem Statement:-
Abhay wants to know what the temperature will be for the future 1 year as he needs to plan his trip according to the weather of his city help him by predicting or forecasting the weather of his city.
Data Visualization required.
You can use Prophet Model or XGBOOST for ML Part.
Features of training dataset:-
-time : DESCRIBING THE TIME/DAY OF THAT PERIOD(YEAR)
-tavg : AVERAGE TEMPERATURE OF THAT DAY
-tmin : MINIMUM TEMPERATURE OF THAT DAY
-tmax : MAXIMUM TEMPERATURE OF THAT DAY
-prcp : PRECIPITATION ON THAT DAY
As a team of 4, we were given the task of developing a model that would be able to predict the average day temperature based on data available for every day in the last 32 years (From 01-01-1990 to 27-07-2022). The predictive model could be based on the Prophet model from Fbprophet library developed by Facebook or using XGBOOST. The dataset given to us was from Mumbai.
The process of developing a Temperature Forecasting model can be categorised into the following steps:
1. Collection of data: Seasonla data was available and given to us for the project to be completed.
2. Cleaning the data: This waws an important process where we got rid of the null values (NaN) present in the dataset. This was done using the bfill and ffill methods. These are methods used for backwardfill and forward fill respectively, which can be used to fill the succeding value into current cell or preceeding value into present cell respectively.
3. Data visualization: The plotly library was used for this process. Line graphs were plotted for understanding the trends in the  variation of maxtemp vs time, mintemp vs time, avgtemp vs time.
4. Prophet forecasting model development: The model was developed which whowed us the predicted temperatures for all days for one year hence the lst date mentioned.
5. Checking accuracy of model: Using the diagnostics of the prophet model, we figure out how accurately the model was able to make predictions.
