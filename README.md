# python-api-challenge

## Python Libraries used:

matplotlib.pyplot

pandas

numpy

scipy.stats (linregress)

hvplot.pandas

requests

time


## API's Utilized:

GeoAPIfy

OpenWeather API

# WeatherPy
In this analysis weather data and location data was compared. A random list of 500+ cities was generated using GeoAPIfy. Real-Time weather data from OpenWeather API was merged into a cities.csv file. The cities were mapped. Size of the labels was determined by Humidity and color by Name. Then, scatter plots were generated comparing weather attributes like Humidity, Cloud cover, Wind Speeds, and Max Temperature against Latitudes in the Northern and Southern Hemispheres to identify any correlation. 

# VacationPy
Using the cities.csv file that was created for the WeatherPy analysis, I limited the cities list by Max Temps between 40 and 70 degrees Fahrenheit and 50% Cloudiness. I then used GeoAPYfy to locate the first Hotel within 10,000 metres of those cities. These cities were mapped and labeled with the Hotel Name and Country. Like in the previous map the size of the label was determined by Humidity and the color by Name. 
