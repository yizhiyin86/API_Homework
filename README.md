# API_Homework
Homework for API

In this homework, I use numpy to randomly generate two number as geo-coordinate and use these randomly generated geo-coordinates to search for the nearby city by using the citipy module, as well as to extract the nearby city's country code and geo-coordinates. Then I use each city's geo-coordinates and extract its weather information from openweathermap.org API. In this way, I extracted weather information for >500 unique cities. Then I made a pandas data frame from the extracted weather information, used matplotlib to plot the value of maximum temperature, humidity %, cloudiness % and wind speed of each of these >500 cities against its latitude and draw some interesting observations.

1.The observed trends are saved in the file observed_trend.txt

2.The following files are saved in the output directory
    a. log.txt (a record of city name and number API calls and API urls)
    b. weather_response.txt (a record in the form of dictionary {city_name:API_response,......}, can be loaded as json file for further manipulation)
    c.weather.csv (a record of extracted weather information for each city)
    d.all_plots.png (a png with all the scatter plots)

![scatter plots of weather information](https://raw.githubusercontent.com/yizhiyin86/API_Homework/master/output/all_plots.png)
