# Predicting-AQI-level of Delhi

The aim of this project is to predict the AQI levels of Delhi ,India which is one of the most polluted cities in the World.
Several Machine Learning models such as Linear Regression, Decision trees, Random Forests, Ridge Regression, Lasso Regression, Elastci net models were trained and hyperparemter tuning was performed using Gridsearch.

## Reproducibility 
The Jupyter notebook contains the exploratory data analysis, data cleaning, and algorithm testing. Notebook is written in Python 3.6. Requirements.txt lists all dependencies to run the code. This is a combination of weather data and pollution data.The weather data is included in weather_data file and the AQI data for three years are present in separate files which are merged with the weather data to get the complete dataset. 

## Training and Evaluation
The Data was split into training and testing and different models were trained and RMSE scores were used to evaluate the performance of the models. Random forest produced the least RMSE scores of 4.93 .
