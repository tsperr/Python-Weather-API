![Screen Shot 2021-07-26 at 3 16 27 PM](https://user-images.githubusercontent.com/76749991/127045859-663180b3-cbf5-4744-b1a5-04d9aebd2fec.png)

# Python API Homework - What's the Weather Like?

## Part I - WeatherPy

A Python script was created to visualize the weather of 500+ cities across the world of varying distance from the equator. The [OpenWeatherMap API](https://openweathermap.org/api) was utilized to retrieve data to determine the following:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, a sentence or two explains what the code is analyzing. 

A linear regression is ran on each relationship:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, a sentence explains what the linear regression is modeling.

### Part II - VacationPy

Jupyter-gmaps and the Google Places API is used for this part. A heat map displays the humidity for every city from Part I. Then, the DataFrame is used to find your ideal weather condition. For example:

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

Google Places API is used to find the first hotel for each city located within 5000 meters of your coordinates, and plotted on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
