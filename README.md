# World Weather Analysis

## Overview of Project

### Original Project
Jack is the head of analysis for the user interface team. He works for PlanMyTrip, a leading 
travel technology company. Jack asked me to help him collect and present data for customers 
via the search page, which they will then filter based on their preferred travel criteria in order to 
find their ideal hotel anywhere. To perform this task. I used Python, Jupyter Notebook and the
city PI module to get the cities for more than 700 random latitudes and longitudes then I performed 
requests on the open weather map API and retrieve the JSON weather data from these cities. I 
then added the weather data to the Panda’s dataframe. From there I used Matplotlib to create a 
series of scatter plots to show the relationship between the latitude and a variety of weather 
parameters for over 700 cities around the world. As part of the analysis I completed a series 
of statistical calculations on the data using linear regression on the weather parameters in the 
Northern and Southern hemispheres. This data helped my team predict the best time of the year 
for people to plan their vacation. Finally, I exported the data, cleaned it and used the weather 
data to choose the best cities for a vacation based on certain weather criteria and then mapped 
these cities using Jupyter G Maps and the Google Places API. </p>

### Revision of the Project
Jack and beta testers provided recommendations for a few changes. They recommended adding the 
weather description to the weather data I already retrieved in the original project. Then, I added 
input statements for the best testers to filter the data for their weather preferences, which 
will be used to identify potential travel destinations and nearby hotels. From the list of 
potential travel destinations, the beta tester will choose four cities to create a travel itinerary. 
Finally, using the Google Maps Directions API, I will create a travel route between the four 
cities as well as a marker layer map. </p>

## Key Deliverables for Revised Project

### Deliverable 1: Retrieve Weather Data
For this deliverable I had to Generate a set of 2,000 random latitudes and longitudes, retrieve 
the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather
data you gathered in this module, use your API skills to retrieve the current weather description
for each city. Then, create a new DataFrame containing the updated weather data.

Below is a snippet of Python code used for performing an **API** call with the **OpenWeatherMap**:
![Python_code_API_request.png](https://github.com/Robertfnicholson/World_Weather_Analysis/blob/862513256d05338fbec82927ad37f1c69cdfbcc6/Weather_Database/Python_code_API_request.png)

The below is a city_data dataframe that I created.
![city_data_df.png](https://github.com/Robertfnicholson/World_Weather_Analysis/blob/862513256d05338fbec82927ad37f1c69cdfbcc6/Weather_Database/city_data_df.png)

I also generated a csv output file containing the weatherPy_database.csv.</p>

### Deliverable 2: Create a Customer Travel Destinations Map
For this deliverable I created input statements allow beta testers to retrieve customer weather 
preferences, then I used those preferences to identify potential travel destinations and nearby 
hotels. Then, I showed those destinations on a marker layer map with pop-up markers.

Below is the hotel dataframe that I developed.
![hotel_df.png](https://github.com/Robertfnicholson/World_Weather_Analysis/blob/e078c65beed79a0bad6c12a5adc5106ac789b3e3/Vacation_Search/hotel_df.png)

Below is the WeatherPy vacation map that I developed.
![WeatherPy_vacation_map.png](https://github.com/Robertfnicholson/World_Weather_Analysis/blob/e078c65beed79a0bad6c12a5adc5106ac789b3e3/Vacation_Search/WeatherPy_vacation_map.png)
</p>

### Deliverable 3: Create a Travel Itinerary Map
For this deliverable I used the **Google Directions API** to create a travel itinerary that 
shows the route between four cities chosen from the customer’s possible travel destinations. 
Then, create a marker layer map with a pop-up marker for each city on the itinerary.

Below is the itinerary travel map that I developed.
![WeatherPy_travel_map.png](https://github.com/Robertfnicholson/World_Weather_Analysis/blob/e078c65beed79a0bad6c12a5adc5106ac789b3e3/Vacation_Itinerary/WeatherPy_travel_map.png)

Below is the itinerary travel map with markers that I developed.
![WeatherPy_travel_map_markers.png](https://github.com/Robertfnicholson/World_Weather_Analysis/blob/e078c65beed79a0bad6c12a5adc5106ac789b3e3/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
</p>



