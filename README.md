# APIs---WeatherAndVacation


Python API Challenge = WeatherPy and VacationPy


PART I

WeatherPy: created a Python script to visualize the weather of 500+ cities across the world and of varying distances from the equator using citipy and the OpenWeatherMap API.

Requirement 1: Created the following scatter plots to showcase relationships between cities and various weather measurements 
-  Latitude vs. Temperature
-  Latitude vs. Humidity
-  Latitude vs. Cloudiness
-  Latitude vs. Wind Speed

Requirement 2: computed the linear regression for each scatter plot created above (paired in hemisphere sets)
-  Northern Hemisphere - Temperature (F) vs. Latitude
-  Southern Hemisphere - Temperature (F) vs. Latitude
-  Northern Hemisphere - Humidity (%) vs. Latitude
-  Southern Hemisphere - Humidity (%) vs. Latitude
-  Northern Hemisphere - Cloudiness (%) vs. Latitude
-  Southern Hemisphere - Cloudiness (%) vs. Latitude
-  Northern Hemisphere - Wind Speed (mph) vs. Latitude
-  Southern Hemisphere - Wind Speed (mph) vs. Latitude
* Please note, analysis included at the end of each paired set


PART II

VacationPy: created a Python script to analyze weather data across a set of cities by creating maps using Geoapify API and the geoViews.

Requirements:
1. Create a map that displays a weighted humidity point for every city in the city_data_df DataFrame
2. Create a new DataFrame based on my preferred weather conditions
3. Create a new hotel-df based on the preferred cities generated in the step above
4. Locate hotels using the Geoapify API
5. Create a map with the cities and hotels in a hover message for each point on the map