# python-api-challenge

This two part assignment takes a list of random cities, showcases the relationship between weather and latitude, and based on this data, plots the locations of ideal vacation cities on a map.

The first Jupyter Notebook file, WeatherPy.ipynb, does the following:
    
    -Generates a cities list using citipy library
    -Retrieves weather data for the cities using OpenWeatherAPI
    -Places the data into dataframes based on location
    -Outputs a .csv with city data
    -Generates scatter plots and calculates linear regression based on the 
     relationship between latitude and different variables
    -Outputs .png files of the scatter plots

The second Jupyter Notebook file, VacationPy.ipynb, does the following:
    
    -Reads the .csv file created in WeatherPy.ipynb and applies it to a dataframe
    -Creates a map plot of the cities
    -Narrows down list of cities to those with ideal weather conditions
    -Uses dataframe data to retrieve nearest hotels using the Geoapify API
    -Creates a map plot with ideal weather cities and hotels names

Documentation found at the following locations:
    
    https://openweathermap.org/current
    https://apidocs.geoapify.com/docs/places/#about
