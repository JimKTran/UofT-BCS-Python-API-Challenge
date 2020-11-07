# WeatherPy Homework
### _Submitted November 04, 2020_
#### _By: Jim Tran_

![equatorsign](Final_Outputs/equatorsign.png)
==============================================

*The main objective of the WeatherPy homework assignment is to develop pandas scripts and matplotlib plots along with API call data to analyze the weather data from OpenWeatherMap API using Citipy random city calls.  Citipy must be installed and OpenWeatherMap API must be obtained first before starting the the assignment.  A script is provided to randomly generate 500 cities for weather lookup for analysis.*  

*Initially, API calls are performed to check the weather of each random city from Citipy.  The results are printed out in a log that identifies each city found and cities that are not found.  The data is then dumped into a dataframe for analyis and plotting/graphing.*

*The first plot produced is the [Latitude_vs_Temperature](Final_Outputs/Latitude_Temperature.png) graph.  The data show city temperatures are highest/hottest with cities located closer to 0 latitude or the equator.  Additionally, city temperatures are lowest/coldest with cities in the northern hemisphere 
(latitudes greater than 0); and conversely, city temperatures are higher/hotter with cities in the southern hemisphere (latitudes less than 0).* 

 *The [Latitude_vs_Humidity](Final_Outputs/Latitude_Humidity.png) graph show higher humidity in more northern hemisphere cities.  Furthermore, the [Latitude_vs_Cloudiness](Final_Outputs/Latitude_Cloudiness.png) graph and the [Latitude_vs_WindSpeed](Final_Outputs/Latitude_WindSpeed.png) graph show data that is scattered across the latitude.*
  
*The City Weather DataFrame is further categorized by cities in the northern and southern hemispheres and then graphed against temperatures for analysis. Correlation coefficient and linear regressions are calculated to see how closely fitted the data is between the metrics.  The correlation coefficient for temperatures and latitude for cities in the [northern_hemisphere](Final_Outputs/Temperature_Latitude_NorthHem.png) is -0.8605, and the regression show there is strong negative correlation between the metrics for cities in the northern hemisphere.  Temperatures are higher as we move closer to the 0 latitude or the equator and colder as latitudes increase.*

*Alternatively, there is an opposite effect with cities in the [southern_hemisphere](Final_Outputs/Temperature_Latitude_SouthHem.png). The correlation coefficient is about 0.7275 and the regression a decent positive correlation between the metrics for cities in the southern hemisphere.  Temperatures are higher with cities located closer to the equator.* 

*This analyis was built using this work and [code](https://github.com/JimKTran/UofT-BCS-Python-API-Challenge/blob/master/WeatherPy/WeatherPy_Final.ipynb)*
