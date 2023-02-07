# python-api-challenge
Penn Data Science Bootcamp Module 6 Challenge

* added a .gitignore file to store API key

# WeatherPy (Part 1)
Used the OpenWeatherMap API to retrieve weather data from  cities list. Next, created a series of scatter plots to showcase the following relationships:
* Latitude vs. Temperature

* Latitude vs. Humidity

* Latitude vs. Cloudiness

* Latitude vs. Wind Speed

Computed the linear regression for each relationship. Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). Then, created a series of scatter plots making sure to include the linear regression line, the model's formula, and the r values.

# VacationPy (Part 2)
Used the Geoapify API and the geoViews Python library to employ Python skills to create map visualizations.
Created a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
Narrowed down the city_data_df DataFrame to find an ideal weather condition
Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
For each city, used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates.
Add the hotel name and the country as additional information in the hover message.
