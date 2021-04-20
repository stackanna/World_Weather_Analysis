# World_Weather_Analysis

## Analysis & Summary Overview 

In this analysis, we developed an application called “PlanMyTrip” (“PMT”)  for our client, Jack. The PMT app was developed using the Citypy Module in Jupyter Notebook with Python, allowing us to correlate thousands of random coordinates of latitude and longitude, to a city and it’s current weather, using the Open Weather API to retrieve JSON weather data from the nearest city to each coordinate. The purpose of this application is to provide a platform for PlanMyTrip and it’s customers to plan their trips based on “the best time of year,” or best weather conditions, for their destination of choice.

By performing an API call with the OpenWeatherMap, we were able to create multiple Pandas DataFrames that allow us to retrieve the current weather description from each city’s JSON weather data. We then utilized MatPlotLib to show the relationships between latitude and weather with several scatter plots, in order to better provide a visual descriptor of the weather data. However, in order to truly understand the data in the scatter plot to make a better prediction of the weather, linear regression techniques of statistical analysis were used to compare the Northern/Southern Hemispheres and their correlating weather parameters. 

To further develop the PlanMyTrip application and its capabilities, I integrated Jupyter Gmaps, Google Places and Directions API’s to map and filter the cities based on preferred weather conditions, and suggest nearby lodging and hotels to those locations. With the help of a few beta testers, we are able to instruct them to use input statements for their preferences, and chose four cities to create a travel itinerary, which then were then used in coordinating a bicycle travel route between four cities, and a marker layer map (with the following data: Hotel name, City, Country and Current weather description with the maximum temperature), using Google Maps Directions API.

## Results 

In retrospect, this exercise was a very intriguing use of API’s to learn and understand how Python and Jupyter notebook can be coupled with open source API’s for the purposes of creating unique applications. Creating random coordinates and analyzing weather data with the WeatherPy & CityPy Python Modules, and OpenWeatherMap API tools opens to the doors to hundreds of applicable uses, and was a great learning experience for API integration in general. 

We are happy that Jack and his beta testers love the PlanMyTrip app, and we look forward to developing similar applications like this in the future.
