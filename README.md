# python-api-challenge

**WeatherPy**
- Created a Python script to visualize the weather of 596 cities of varying distances from the equator.
- Generated random Geographic coordinates and a list of cities using citipy library
- Used the OpenWeatherMap API to retrieve weather data for the generated city list
- Created scatter plots showcase the relationship between Weather Variables and Latitude:
    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed
- Computed Linear Regression for Each Relationship
    - Northern Hemisphere: Temperature vs. Latitude
    - Southern Hemisphere: Temperature vs. Latitude
    - Northern Hemisphere: Humidity vs. Latitude
    - Southern Hemisphere: Humidity vs. Latitude
    - Northern Hemisphere: Cloudiness vs. Latitude
    - Southern Hemisphere: Cloudiness vs. Latitude
    - Northern Hemisphere: Wind Speed vs. Latitude
    - Southern Hemisphere: Wind Speed vs. Latitude
- Summarized my observation from the Linear regression analysis for each of the plots above

**VacationPy**
- Created map visualizations with hotel information for selected cities (based on select criteria) using Geoapify API and the geoViews Python library
- Create a map that displays a point for every city in the city_data_df DataFrame with the size of the point representing humidity in each city.
- Narrow down the city_data_df DataFrame based on the criteria below:
    - A max temperature lower than 27 degrees but higher than 21
    - Wind speed less than 4.5 m/s
    - Zero cloudiness
- Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
- For each city, used the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
- Customized the hover message for each city on the map to show coordinates, city, humidity, hotel name and country information
