# Bike-sharing-demand

Seoul city provides rental bikes to the people for certain amount of time but the demand for these bikes fluctuates constantly so they are facing a difficulty to keep up with this. Here machine learning was used to predict the future and make use of big-picture details to understand how to manage rentals according to the demands.

## About the dataset

• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc (Non Functional Hours), Fun(Functional hours)


Major factors affecting bike demand are temperature, rainfall, snowfall, working day or not, traffic


## Approach to solve the problem

* performing exploratory data analysis
* data cleaning
* encoding of categorical columns
* feature scaling
* fitting different models (Regression, Decision tree regressor, Gradient boost)
* evaluation of models using R-squared, RMSE, RSE, MAE metrics

## conclusion

An R-squared value of 0.86 was acheived using Decision tree regressor with minimum number of leaf nodes
