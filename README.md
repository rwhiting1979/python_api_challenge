# WeatherPy and VacationPy Data Analysis

### Overview
This data analysis assignment consists of two parts: WeatherPy and VacationPy, where we explore weather data, perform visualizations, and plan future vacations. Here's a brief breakdown of each part:
### Part 1: WeatherPy
##### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
In this part, we retrieve weather data for a list of cities using the OpenWeatherMap API and create scatter plots to visualize the relationships between latitude and various weather variables. The relationships explored include:
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

##### Requirement 2: Compute Linear Regression for Each Relationship
We compute linear regressions for each of the above relationships, separating the data into Northern Hemisphere and Southern Hemisphere datasets. The linear regression plots display the regression lines, formulas, and r-values.

### Part 2: VacationPy
In this part, we plan future vacations based on weather data and utilize Jupyter notebooks, the geoViews Python library, and the Geoapify API.
##### Task 1: Create a Map with City Points
Create an interactive map using geoViews that displays city points, with point size indicating humidity levels. This map helps visualize humidity across different cities.
##### Task 2: Narrow Down Ideal Weather Conditions
Narrow down the list of cities to find ideal weather conditions, considering factors such as temperature, wind speed, and cloudiness. This step involves filtering the city data.
##### Task 3: Retrieve Hotel Information
Create a new DataFrame called hotel_df to store information about hotels near each city. We use the Geoapify API to find the first hotel located within 10,000 meters of each city's coordinates.
##### Task 4: Enhance Map Visualization
Enhance the map visualization by adding hotel names and countries to the hover message for each city point. This additional information provides valuable insights for vacation planning.

### Notes
* Replace API keys and credentials with your own where necessary to access external services.
* This assignment demonstrates skills in data retrieval, analysis, visualization, and geographic information system (GIS) for practical applications such as vacation planning.
