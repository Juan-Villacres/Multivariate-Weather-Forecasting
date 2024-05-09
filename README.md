# Multivariate-Weather-Forecasting
I have developed three models for forecasting variables such as precipitation or temperature using LSTM and convolutional neural networks.
The script is based on Greg Hogg Python notebook on Forecasting Temporal Series.

The data corresponds to weather variables obtained from meterological sensor from the comunity Atillo in Ecuador. The data comprise: precipitation, wind velocity, temperature, and cloud cover.

The imput layer of the neural networks takes groups of 6 hours of the mentioned data. Whilst the output layer correponds to the average temperature, and precipitation for the hour that follows the first 6 that were considered in the input. The models also predict precipitation and temperature within 6 hours after.   
