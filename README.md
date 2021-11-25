# World_Weather_Analysis
WeatherPy with Python APIs

## Main Objective
1. Perform tasks using new Python libraries and modules.
2. Retrieve and use data from an API "get" request to a server.
3. Retrieve and store values from a JSON array.
4. Use try and except blocks to resolve errors.
5. Write Python functions.
6. Create scatter plots using the Matplotlib library, and apply styles and features to a plot.
7. Perform linear regression, and add regression lines to scatter plots.
8. Create heatmaps, and add markers using the Google Maps API.

## Overview
After working on an app, beta testers requested a new feature, weather description, be added to the markers that pop up after clicking on a pin.  The beta testers also wanted to be able to pick their minimum and maximum temperatures for a trip.  From there, four cities were chosen to create an itinerary map with pins and markers.

# Process

## Retrieve the Weather Data
An API was established with OpenWeatherMap and a DataFrame was created to get the initial list of potential cities. 
![Pic 1](https://github.com/Baylex/World_Weather_Analysis/blob/main/Weather_Database/Resources/City_DF.PNG)

## Create a Customer Travel Destinations Map
After prompting the beta testers for their minimum and maximum temperature preferences, the data frame was cleaned for null hotel entries and empty rows.  Markers and pins were created for the remainder of the hotels. 
![Pic 2](https://github.com/Baylex/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)

## Create an Itinerary Map
The list was narrowed down to 4 cities in the same country and a travel map was created. 
![Pic 3](https://github.com/Baylex/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

Makers were added to the map of four cities. 
![Pic 4](https://github.com/Baylex/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
