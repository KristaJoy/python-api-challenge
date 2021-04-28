# python-api-challenge
Includes WeatherPy and VacationPy challenges.

For WeatherPy we used a randomly generated list of latitude and longitudes to find the nearest city in a list using citipy. Once we had the list we did an API call to the Open Weather Map API to define our lists of weather data we'd like to find for each city. If the city did not have weather data we used try/except to skip it. The end result was a list of 578 cities. 
