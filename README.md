# python-api-challenge
Includes WeatherPy and VacationPy challenges.

For WeatherPy we used a randomly generated list of latitude and longitudes to find the nearest city in a list using citipy. Once we had the list we did an API call to the Open Weather Map API to define our lists of weather data we'd like to find for each city. If the city did not have weather data we used try/except to skip it. The end result was a list of 578 cities with weather data down from 632.

To begin to analyze the data we created scatter plots for the City Latitude vs Max Temperature, vs Humidty, Cloudiness, and Wind Speed. We then calculated Linear Regression data for each of these split up between the Northern and Southern Hemispheres. 

For VacationPy we imported in the dataframe we created in WeatherPy and created a Humidity heatmap using gmaps. We then filtered down the list of cities to only those that fit our ideal weather conditions and used Google Places API to find a hotel within 5000 meteres of that city's coordinates on the map. We then overlayed location markers onto our heatmap with the name of the hotel, city, and country code showing on it's info box. I've now found some options for my next vacation!
