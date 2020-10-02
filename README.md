# python-api-challenge

WeatherPy, an analysis of cities across the globe, selected at random to determine if there is a relationship between latitude and various weather related metrics. Powered by Open Weather API.


### Latitude vs Max Temperature
* By simply looking at the plot generated, it appears that there is a correlation between latitude and max temperature
* The max temperature tends to reach it's maximum as latitude approaches 0 (the equator) which we would expect

![alt text](https://github.com/MATaylor0/python-api-challenge/blob/master/WeatherPy/output/Fig1.png)

### Latitude vs Humidity
* There does not appear to be a relationship between latitude and humidity
* We are plotting relative humidity, which normalises the effect temperature has on absolute humidity, therefore it makes sense to see no relationship in the plot

![alt text](https://github.com/MATaylor0/python-api-challenge/blob/master/WeatherPy/output/Fig2.png)

### Latitude vs Cloudiness
* There does not appear to be a relationship between latitude and cloudiness in this dataset
* According to the Wikipedia page for cloud cover (cloudiness), there shoud be a weak relationship showing that cloudiness is lower around the equator
* However, it is also true that cloudiness is highly variable, it could be true that there was no observable relationship at the timepoint selected
https://en.wikipedia.org/wiki/Cloud_cover

![alt text](https://github.com/MATaylor0/python-api-challenge/blob/master/WeatherPy/output/Fig3.png)

### Latitude vs Wind Speed
* There does not appear to be a relationship between latitude and wind speed
* According to the Wikipedia page for wind speed, there are significantly more factors than simply latitude (or temperature) in determining wind speed, therefore it makes sense that we see little to no relationship
https://en.wikipedia.org/wiki/Wind_speed

![alt text](https://github.com/MATaylor0/python-api-challenge/blob/master/WeatherPy/output/Fig4.png)