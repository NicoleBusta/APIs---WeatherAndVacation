# APIs---WeatherAndVacation


Python-API-challenge_WeatherPy_VacationPy

This is the Module 6 Challenge and includes two parts:

Part I - WeatherPy

Create a Python script to visualize the weather of 500+ cities across the world and of varying distances from the equator by using citipy and the OpenWeatherMap API.

Requirement 1: Create a series of scatter plots to showcase the following 

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed


Requirement 2: Compute linear regression for each scatter plot created in Requirement I (separated hemisphere sets)

Northern Hemisphere - Temperature (F) vs. Latitude

Southern Hemisphere - Temperature (F) vs. Latitude

Northern Hemisphere - Humidity (%) vs. Latitude

Southern Hemisphere - Humidity (%) vs. Latitude

Northern Hemisphere - Cloudiness (%) vs. Latitude

Southern Hemisphere - Cloudiness (%) vs. Latitude

Northern Hemisphere - Wind Speed (mph) vs. Latitude

Southern Hemisphere - Wind Speed (mph) vs. Latitude

* Please note, at the end of each pair of plots, an analysis has been included.



Part II - VacationPy

Create a Python script to analyze weather data across a set of cities by creating map visualizations (via Geoapify API and the geoViews Python library).

Requirements:
1. Create a map that displays a weighted humidity point for every city in the city_data_df DataFrame
2. Create a new DataFrame based on my preferred weather conditions
3. Create a new hotel-df based on the preferred cities generated in the step above
4. Locate hotels using the Geoapify API
5. Create a map with the cities and hotels in a hover message for each point on the map