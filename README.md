# python-api-challenge
#Part1 - WeatherPy

In this section, python script was created to visualize the weather for more than 500+ cities across the world of varying distance from the equator. To complete this task. I have used a python library and OpenWeatherMap API to create a model of weather across the world cities.

I created a various scattor plots to showcase the following relationships:
 * Temperature (F) vs. Latitude
 * Humidity (%) vs. Latitude
 * Cloudiness (%) vs. Latitude
 * Wind Speed (mph) vs. Latitude

For each plot I have given the summary about the code and the results.  

I also applied a linear regression on each relationship. It was separated by Northern and Southern hemisphere. Northern Hemishere has greater than or equal to 0 degrees latitude and Souther Hemisphere has less than 0 degrees latitude.

 * Northern Hemisphere - Temperature (F) vs. Latitude
 * Southern Hemisphere - Temperature (F) vs. Latitude
 * Northern Hemisphere - Humidity (%) vs. Latitude
 * Southern Hemisphere - Humidity (%) vs. Latitude
 * Northern Hemisphere - Cloudiness (%) vs. Latitude
 * Southern Hemisphere - Cloudiness (%) vs. Latitude
 * Northern Hemisphere - Wind Speed (mph) vs. Latitude
 * Southern Hemisphere - Wind Speed (mph) vs. Latitude

I have included my analysis for each plot. I have also saved the images of my analysis in the image folder.

#Part2 - VacationPy
I used the weather data gathered from part one to help plan for future vacations. I used jupyter-gmaps and the Google Places API to create a heatmap that displays the humidity for every city from part one. I narrow down the dataframe to find the ideal weather condition, including:

 * A max temperature lower than 80 degrees but higher than 70.
 * Wind speed less than 10 mph.
 * Zero cloudiness.

I used the Google Places API to find the first hotel for each city located within 5000 meters of the coordinates. Finally, I plotted the hotels on top of the humidity heatmap with each pin containing the hotel name, city, and country.

## Observations and Insights

From Part1 (WeatherPy), below are my obeservations and insights:
 * The temparatures correlates with the lattitude. As latitude moves away from equator, temperature also decreases.
 * There is no correlation between humidity and latitude.
 * The both hemispheres, latitude has a small influence on wind speed but not very much. The wind speed tends to be higher near arctic and antarctic. 
