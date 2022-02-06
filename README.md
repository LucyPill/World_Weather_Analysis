# World_Weather_Analysis
# Purpose:

The purpose of the challenge was to help collect and present data for customer via the search page of PLANMYTRIP, a top travel company technoly that especilizes in internet related services in the hotel lodging industry. The data collected was filtered based on the customer travel criteria in other to help them find their ideal hotel anywhere in the world.

I used Jupyter Notebook and the citypy module to get the cities from 2000 random latitudes and longitudes. I performed requests in the OpenWeather map API and retrived the JSON weather data from these cities. The weather data was added to a pandas DataFrame; then, I used matplotlib to create a series of scatterplots to show the relationship between latitude and a variaty of weather parameters for over 2000 cities around the world. I performed statistical calculations on the data, using linear regreassion on the weather parameters in the Northen and Southern hemisphere. This data will be helpful in predicting the best time of year for people to plan their vacation.

I exported the data, cleaned it and used it to choose the best cities for vacation based on certain weather criteria. Finally, I mapped these cities using Jupyter gmaps and the Google places API.

# Deliverable 1: Retrieve Weather Data from the API call
* Latitude and longitude

* Maximum temperature

* Percent humidity

* Percent cloudiness

 * Wind speed


* Weather description (for example, clouds, fog, light rain, clear sky)

### Add the weather data to a new DataFrame
Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder

### See Weather_Database folder for the following files:
* The Weather_Database.ipynb file
* The WeatherPy_Database.csv fileSee Weather_Database folder

# Deliverable 2: Create a Customer Travel Destinations Map
### A marker layer map with pop-up markers for the cities in the vacation DataFrame is created. Each marker has the following information:
* Hotel name
* City
* Country
* Current weather description with the maximum temperature![WeatherPy_vacation_map.png](https://github.com/LucyPill/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

# Deliverable 3: Create a Travel Itinerary Map

### A directions layer map between the cities and the travel map is created
![WeatherPy_travel_map.png](https://github.com/LucyPill/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

### A marker layer map with a pop-up marker for the cities on the itinerary is created.
Each marker has the following information:
* Hotel name
* City
* Country
* Current weather description with the maximum temperature

![WeatherPy_travel_map_markers.png](https://github.com/LucyPill/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

# Summary:
I successfully used Jupyter Notebook and the citypy module to get the cities from 2000 random latitudes and longitudes. I performed requests in the OpenWeather map API and retrived the JSON weather data from these cities. I exported the data, cleaned it and used it to choose the best cities for vacation based on certain weather criteria. Finally, I mapped these cities using Jupyter gmaps and the Google places API and generated figures.
