# World_Weather_Analysis

## Overview of the project

The purpose of this project is to find the best cities aound the world to vacation based on the  weather criteria. Using CityPy module in Python, we find the nearest cities to randomly generated latitudes and longitudes. From Open weather API, we retrieve the weather data for these cities. Create scatter plots and perform linear regression to identify the correlation between weather parameters and latitudes. Finally, using Google Places API, we map the cities, weather metrics along with hotel/lodging details on map.

## Resources

Software: Python 3.7.3, Jupyter Notebook 6.0.0, Open Weather API, Google Places API, Google Directions API.

## Results

To find the best time of year for people to plan vacations and perform searches for ideal hotel anywhere in the world, we follow below steps:

1. Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap.
    
2. Add the City, Country, Latitude, Longitude, Weather Metrics to a data frame to continue with the analysis.
    
3. Using Google Places API, search for the hotel near the city in our data frame and add it to the DataFrame.
    
4. Create a marker with hotel, city and weather metrics to show on a map.

    <img src = "https://github.com/Nikhila999/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png" width="500" height="200">
    
5. Using the Google Directions API, we create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.
    
6. Add the markers on the cities and display on the map.

    <img src = "https://github.com/Nikhila999/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png" width="500" height="200">



## Summary

In this module, we learn how to collect data using APIs, navigate through JSON objects, clean the data, load it into Pytgon DataFrames and build Analysis. We also learned to display the data on gmaps and added heat map and markers with information of the search data on it.

