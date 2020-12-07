# Whats-The-Weather-Like
# Part 1: WeatherPy
In this project, the OpenWeather API was used to collect real time weather data from cities around the world using their coodinates (latitude and longitude). Based off of this dataframe, scatter plots were created to determine relationships between variables such as cloudiness, maximum temperature, humidity, and wind speed. Linear regressions were performed to determine the line of best fit as well as the r value in order to analyze the significance of the relationship between variables. 

# Part 2: VacationPy
Using the csv file created from WeatherPy, a dataframe was created pulling only the data for cities that met "ideal conditions" such as: a max temperature lower than 80 degrees but higher than 70, wind speed less than 10 mph, and zero cloudiness. Based on the results, a heat map was created for the cities with ideal conditions using the Google Maps Javascript API. Then, a search was conducted using the Google Places API to identify nearby hotels and the locations of the cities were layed over the heat map for reference.
