# python-api-challenge

### Project Description

This project consists of two Jupyter Notebook files: WeatherPy.ipynb and VacationPy.ipynb.

### WeatherPy.ipynb

The WeatherPy.ipynb notebook focuses on showcasing the relationship between weather variables and latitude. It utilizes the OpenWeatherMap API to retrieve weather data from a list of cities. The notebook includes the following requirements:

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude 

In this section, scatter plots are created to visualize the relationships between latitude and various weather variables. The following plots are generated and saved in the output_data folder:

Latitude vs. Temperature
![Fig1](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/388460d4-2058-459f-b741-3de696c68bd1)


Latitude vs. Humidity
![Fig2](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/508517be-b37c-484b-8523-a0fbd82211ad)


Latitude vs. Cloudiness
![Fig3](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/ee331217-4194-439d-bc28-28f522ac85bd)


Latitude vs. Wind Speed
![Fig4](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/2002b29b-9208-4a60-9267-e78bf2a5f909)


### Requirement 2: Compute Linear Regression for Each Relationship

This requirement involves computing linear regression for each relationship and creating scatter plots for the Northern Hemisphere and the Southern Hemisphere. The scatter plots include the linear regression line, the model's formula, and the r values. The following plots are generated:

Northern Hemisphere: Temperature vs. Latitude
![TvsL-n](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/7d341ce3-54d2-42ad-a1d9-99e617f5140a)

Southern Hemisphere: Temperature vs. Latitude
![TvsL-s](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/3e3ac31a-dff7-460c-8492-37e975c64af6)

The linear regression analysis on temperature versus latitude in the Northern Hemisphere shows a moderate negative correlation, with temperatures decreasing as latitude increases. In the Southern Hemisphere, there is a moderate positive correlation, indicating that temperatures tend to increase as latitude increases.

Northern Hemisphere: Humidity vs. Latitude
![HvsL-n](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/dbbd9f7a-bf24-4992-a478-2309e9416d12)

Southern Hemisphere: Humidity vs. Latitude
![HvsL-s](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/2b3dc3e5-8663-4464-813c-0b12f09e0ae0)

The linear regression analysis for humidity versus latitude in both the Northern and Southern Hemispheres reveals weak correlations. In the Northern Hemisphere, latitude shows a weak negative relationship with humidity, while in the Southern Hemisphere, it exhibits a weak positive relationship. These findings suggest that latitude alone is not a strong predictor of humidity, emphasizing the importance of considering other factors such as local climate patterns, proximity to water bodies, elevation, and seasonal variations to understand humidity variations accurately.

Northern Hemisphere: Cloudiness vs. Latitude
![CvsL-n](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/f763f0c2-9425-4be8-8f04-182c0ac982bc)

Southern Hemisphere: Cloudiness vs. Latitude
![CvsL-s](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/cfc5b9de-bd6b-46c1-83de-01c653855ebc)

The linear regression analysis of cloudiness versus latitude in both the Northern and Southern Hemispheres reveals weak correlations. In the Northern Hemisphere, there is a slight positive relationship between latitude and cloudiness, while in the Southern Hemisphere, there is a slight negative relationship. However, the low r-values indicate that latitude has minimal influence on cloudiness. Other factors such as local weather patterns and atmospheric conditions likely play a more significant role in determining cloudiness levels.

Northern Hemisphere: Wind Speed vs. Latitude
![WvsL-n](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/d87c9936-0e6e-4ade-b2b2-27d8cfd67daf)

Southern Hemisphere: Wind Speed vs. Latitude
![Wvsl-s](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/afe89c74-a0dd-4dc0-a14f-9875eb484b8c)

The linear regression analysis of wind speed and latitude in both the Northern and Southern Hemispheres reveals weak negative correlations. In the Northern Hemisphere, there is a slight decrease in wind speed as latitude increases, but the relationship is not significant. Similarly, in the Southern Hemisphere, as latitude increases, there is a small decrease in wind speed. However, latitude alone is not a strong predictor of wind speed in either hemisphere, suggesting that other factors play a more influential role.

After each pair of plots, explanations are provided to describe what the linear regression is modeling and any relationships or findings observed.

### VacationPy.ipynb

The VacationPy.ipynb notebook focuses on utilizing weather data skills to plan future vacations. It utilizes Jupyter notebooks, the GeoViews Python library, and the Geoapify API. The notebook includes the following tasks:


# Creating a map that displays a point for every city in the city_data_df DataFrame. The size of the point corresponds to the humidity value for each city.
![step1](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/5b1a1516-1a85-4e22-944f-30058645bffa)


# Narrowing down the city_data_df DataFrame to find cities that match specific weather conditions, such as maximum temperature, wind speed, and cloudiness.

# Creating a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

# Using the Geoapify API to find the first hotel located within 10,000 meters of the coordinates for each city in hotel_df.

# Adding the hotel name and country as additional information in the hover message for each city on the map.
![step5](https://github.com/ehsanshahrabi/python-api-challenge/assets/124327258/026f3bf6-17af-453e-937d-fd31c90a8459)
