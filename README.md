# World_Weather_Analysis

## Purpose 

The purpose of this project was to create a map that displays potential vacation spots for users by filtering data based on the preferred weather temperatures. 

## Methods
The data for this project was gathered by making an API call to OpenWeatherMap API. The call returned a data structure in JSON format, and this structure was parsed through to collect weather data for several locations. 
The data was organized into Pandas DataFrames, and GoogleMaps and Directions API were used to create maps. 

In this example, the data was filtered by preferred temperatures in the range of 75-90 degrees Fahrenheit. 

## Results 

Finally, an itinerary map was created for a vacation to four cities in Mexico: 

1. Acapulco
2. Tecoanapa 
3. Puerto Escondido
4. Pochutla

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/90593897/139756470-0c5e7c47-7196-46d3-8845-058f44a91ef5.PNG)
