# World Weather Analysis Challenge 6

## Overview of Project

The purpose of this project was to provide PlanMyTrip the ability to recommend ideal hotels based on clients' weather preferences. This task was achieved by collecting data on weather and analyzing it to find 500 unique cities worldwide using the Pandas DataFrame method and related API's. The culmination of all this work resulted in the PlanMyTrip app being able to provide visualizations of potential travel destinations, current real time weather information, and nearby hotels. See below for more details about the analysis. 

Deliverable 1: Retrieve Weather Data
 - Retrieve all of the information from the API Call:
   - Latitude and longitude
   - Maximum temperature
   - Percent Humidity
   - Percent Cloudiness
   - Wind Speed
   - Weather Description 
 - Add the weather data to a new DataFrame
 - Export the DataFrame as CSV file

Deliverable 2: Create a Customer Travel Destinations Map
 - Input statements are written to prompt the customer for their minimum and maximum temperature preferences.
 - A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.
 - The hotel name is retrieved and added to the DataFrame, and the rows that don't have a hotel name are dropped.
 - The DataFrame is exported as a CSV
 - A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information: 
   - Hotel Name
   - City
   - Country
   - Current weather description with the maximum temperature

Deliverable 3: Create a Travel Itinerary Map
 - Four DataFrames are created, one for each city on the itinerary.
 - The latitude and longitude pairs for each of the four cities are retrieved.
 - A direction layer map between the cities and the travel map is created and uploaded as a PNG.
 - A DataFrame that contains the four cities on the itinerary is created.
 - A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as a PNG. Each marker has the following information:
   - Hotel Name
   - City
   - Country
   - Current weather description with the maximum temperature

