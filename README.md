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

Weather description added to the markers.

![Weather_Database](https://user-images.githubusercontent.com/87085239/170166813-851079ca-7b15-48ca-b038-ac711bda7289.png)

### Deliverable 2:

Nearest Hotel added to the dataframe.
![Vacation Search 1](https://user-images.githubusercontent.com/87085239/170166862-85a122ec-8847-492b-a737-a7bce7f82a07.png)

Nearest hotel within 5000 meters added to the marker.
![Vacation Search 2](https://user-images.githubusercontent.com/87085239/170166893-6980b118-0223-4df7-a7cb-08dd2c2182e4.png)

### Deliverable 3:

Travel Itinerary for 4 cities within the min and max temperature that the user inputted. 
![WeatherPy_travel_map](https://user-images.githubusercontent.com/87085239/170166927-de7091d6-cfae-41a4-8a45-963bba2c0e48.png)

Marker created for the 4 cities identified in the itinerary. 
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/87085239/170166954-3c5609af-ffac-4d72-9a69-e09d11b9930e.png)

## Summary
The PlanMyTrip app is now designed to allow the user to input a range of tempatures to filter cities on, select cities to create a direction map, and then output a map filtered for those cities with markers showing key attributes. 
