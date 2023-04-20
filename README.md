# Python-API-Challenge
## This repository contains two challenges (folders): WeatherPy and VacationPy.

### Challenge 1
>### The WeatherPy folder houses the WeatherPy.ipynb notebook, which contains the code, as well as a sub-folder called [output_data] where the results of the code execution are stored.
>
> WeatherPy: Analysis of Weather Variables vs. Latitude
>
>This challenge aims to analyze the relationships between various weather variables and latitude by generating scatter plots and linear regression models. Data was collected from the OpenWeatherMap API for randomly selected cities around the world.
>
>### Dependencies Used
>The following Python libraries are required to run the code:
>
>>Pandas: A powerful library for data manipulation and analysis.
>
>>NumPy: A library for numerical computations and handling arrays.
>
>>Matplotlib: A plotting library for creating static, animated, and interactive visualizations.
>
>>Requests: A library for making HTTP requests in Python.
>
>>Scipy: A library for scientific and technical computing.
>
>>OpenWeatherMap API: An API to access weather data for any location on Earth.
>
>### Instructions to Use the Code
>Ensure that you have all the required dependencies installed in your Python environment. You can install them using pip:
>
>>pip install pandas numpy matplotlib requests scipy
>
>Sign up for a free API key on the OpenWeatherMap website (https://openweathermap.org/api).
>
>Replace YOUR_API_KEY in the code with the actual API key you received.
>
>Run the code in a Jupyter Notebook or any other Python environment. The code will generate scatter plots and linear regression models for the relationships between latitude and various weather variables.
>
>Analyze the generated plots and regression models to draw conclusions about the relationships between the weather variables and latitude.
>
>Save the generated plots as images in the output folder by uncommenting the plt.savefig() lines in the code.
>
>Combine the results and analysis from each part of the code to create a comprehensive report on the relationships between latitude and the weather variables.
>
>### Scatter Plots and Linear Regression Models
>
>Part 1: Scatter Plots
>
>The scatter plots showcase the relationships between latitude and the following weather variables:
>
>>Maximum Temperature
>
>>Humidity
>
>>Cloudiness
>
>>Wind Speed
>
>Part 2: Compute Linear Regression for Each Relationship
>
>To better understand the relationships observed in the scatter plots, the data was divided into two DataFrames, one for the Northern Hemisphere (latitude >= 0) and one for the Southern Hemisphere (latitude < 0). Linear regression models were then computed for each relationship.
>
>### Limitations: 
>
>These plots provide insights into the relationships between the variables and latitude, but they do not account for other factors that may affect these variables, such as local geography, climate patterns, and human activity.

### Challenge 2
>### The VacationPy folder houses the VacationPy.ipynb notebook, which contains the code, and uses the csv file generated in the first challenge as its input from the folder [output_data]. 
>
>VacationPy: In this challenge, we'll use weather data skills to plan future vacations by using Jupyter notebooks, the geoViews Python library, and the Geoapify API.
>
>### Dependencies
>
>This code uses the following Python libraries:
>
>>hvplot for data visualization
>
>>pandas for data manipulation
>
>>requests for making API requests
>
>>It also requires an API key from Geoapify to access the hotel data.
>
>### Instructions
>
>Ensure that all the required dependencies are installed.
>
>Import the required libraries and API key.
>
>Load the CSV file containing the weather data into a Pandas DataFrame.
>
>Create a map that displays a point for every city in the DataFrame, with the size of the point representing the humidity in each city.
>
>Narrow down the DataFrame to find cities that meet certain weather criteria.
>
>Create a new DataFrame to store the city, country, coordinates, and humidity of each city.
>
>Use the Geoapify API to find the first hotel located within 10,000 metres of each city's coordinates.
>
>Add the hotel name and country as additional information in the hover message for each city in the map.
>
Contact
>
>If you have any questions or feedback about this script, please feel free to contact me at param.birdi@utoronto.ca.
>
Acknowledgments
>
>This code was written by Paramdeep Singh Birdi as part of a project for a data analysis course. Most of the data used in this project was provided by the course instructors. 
