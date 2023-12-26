# python-api-challenge  

## Part 1: WeatherPy  

In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library
Links to an external site., the OpenWeatherMap API  

Links to an external site., and your problem-solving skills to create a representative model of weather across cities.  

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
