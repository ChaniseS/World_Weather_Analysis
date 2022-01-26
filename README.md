# World_Weather_Analysis
## Overview
Using the Google Maps Directions API, I created a travel route between four cities as well as a marker layer map. Travel and tourism offer individuals a glimpse of the world. Weather conditions influence travel behavior and impact overall travel experience. 

The purpose of this project is to collect, analyze and visualize weather data across cities worldwide and to provide travelers with a tool that will allow them to determine their travel destination based on weather conditions.

## Weather Database:
A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities.

### The following data was retrieved from the API call:
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Current Weather description

## Vacation Search:
I used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels.
Next, I showed those destinations on a marker layer map with pop-up markers.
<img width="1143" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/95304025/151084599-22b1426d-f65c-4e93-8b4e-776274402c0b.png">

## Vacation Itinerary:
I used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, created a marker layer map with a pop-up marker for each city on the itinerary.
<img width="1440" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/95304025/151084738-fa5a6109-492f-4694-a168-607bbed4ec6b.png">
<img width="1440" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/95304025/151084762-b1d748b3-e3d2-44b2-9a53-abce6bcbded5.png">
