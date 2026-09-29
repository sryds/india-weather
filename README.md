Analysis of weather data from 10 Indian cities between 2000 and 2024.

This project analyzes daily weather data taken from 10 major Indian cities between 1 January 2000 and 31 December 2024. 
The data contains metrics such as temperature, apparent temperature ("feels like"), wind and wind gust speeds, wind direction and precipitation levels. There is also a column containing the WMO weather code representing weather conditions for each day.
Through exploratory analysis, this project aims to identify typical weather patterns across the country, by region and by individual city, as well as any changes in weather conditions between 2000 and 2025. 
Using time-series analysis and machine-learning applications, this project will try to predict climate-related developments in the near future and identify specific factors influencing these changes.

The first part of this project involves assessing the scope and nature of the dataset, creating a comprehensive data dictionary and performing exploratory and descriptive analysis on selected variables at both a national and city level. 
The complete analysis, along with accompanying visuals and a summary of insights, can be viewed in the interim report: https://github.com/sryds/india-weather/blob/main/reports/Interim%20Report.pdf

For the second part of the project, the weather data will be used for time-series forecasting and in supervised and unsupervised machine-learning. The exact model to use for time-series forecasting will be determined by certain characteristics of the data, such as stationarity and seasonality. Based on the nature of weather data (seasonal and relatively predictable), a SARIMA (seasonal autoregressive integrated moving average) model may be the most appropriate choice for this dataset.  
The data for this project was retrieved from the following sources:

https://www.kaggle.com/datasets/developerghost/climate-in-india-daily-weather-data-2000-2024/data

https://www.nodc.noaa.gov/archive/arc0021/0002199/1.1/data/0-data/HTML/WMO-CODE/WMO4677.HTM

Code written in Python and executed in Jupyter Notebook.
