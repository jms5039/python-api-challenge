# python-api-challenge  

***I uploaded images of maps to show working maps and updated leged with hotel name and country. Maps are not showing in notebook when viewing github preview***  
![Map of City Data](https://github.com/jms5039/python-api-challenge/blob/main/city_data_df%20map.png)  
![alt text](image.jpg)  
![alt text](image.jpg)

## Part 1: WeatherPy  

In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library, the OpenWeatherMap API, and your problem-solving skills to create a representative model of weather across cities.  

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.  

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.  

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude  

To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:  

    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed  
    
### Requirement 2: Compute Linear Regression for Each Relationship  

To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.  

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values.
You should create the following plots:  

    - Northern Hemisphere: Temperature vs. Latitude
    - Southern Hemisphere: Temperature vs. Latitude
    - Northern Hemisphere: Humidity vs. Latitude
    - Southern Hemisphere: Humidity vs. Latitude
    - Northern Hemisphere: Cloudiness vs. Latitude
    - Southern Hemisphere: Cloudiness vs. Latitude
    - Northern Hemisphere: Wind Speed vs. Latitude
    - Southern Hemisphere: Wind Speed vs. Latitude  
    
After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.  


## Part 2: VacationPy

In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.  

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.  

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.  

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:  

    - Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.  
    - Narrow down the city_data_df DataFrame to find your ideal weather condition.  
    - Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
    - For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
    - Add the hotel name and the country as additional information in the hover message for each city on the map.
