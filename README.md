# World_Weather_Analysis

## Project Overview
Changes have been requested to the PlanMyTrip app including; adding weather description to the weather data, allowing the user to filter the data for their weather preferences, selecting four cities to create an itinerary and use Google Maps Directions API to create a travel route between the four cities as well as a marker layer map.

## Resources
- Data Source: https://openweathermap.org, Google Cloud Platform
- Software: Python 3.7.6, Visual Studio Code, 1.66.2, Jupyter Notebook

## Challenge Overview
Challenge consists of three deliverable:

### Deliverable 1: 
Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.
 

### Deliverable 2: 
Create a Customer Travel Destinations Map. Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

### Deliverable 3: 
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

## Results

### Deliverable 1:

Wweather description added to the markers.

Weather_Database.png

### Deliverable 2:

Nearest Hotel added to the dataframe.
Vacation Search 1.png

Nearest hotel within 5000 meters added to the marker.
Vacation Search 2.png

### Deliverable 3:

Travel Itinerary for 4 cities within the min and max temperature that the user inputted. 
WeatherPy_travel_map.png

Marker created for the 4 cities identified in the itinerary. 
WeatherPy_travel_map_markers.png



## Summary
The PlanMyTrip app is now designed to allow the user to input a range of tempatures to filter cities on, select cities to create a direction map, and then output a map filtered for those cities with markers showing key attributes. 
