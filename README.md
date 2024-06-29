# WeatherPy and VacationPy

## Overview

This project consists of two main parts: WeatherPy and VacationPy. These tools are designed to help visualize weather data and recommend vacation destinations based on specific weather criteria.

## WeatherPy

WeatherPy is a Python-based tool that visualizes the relationship between various weather variables and latitude. By analyzing weather data from over 500 cities around the world, this tool aims to identify patterns and trends in temperature, humidity, cloudiness, and wind speed relative to their distance from the equator. The project leverages the OpenWeatherMap API, Citipy library, and various data analysis libraries in Python to gather, process, and visualize the data.

### Features

- **Data Collection:** Utilizes the OpenWeatherMap API to fetch current weather data for a list of cities generated using random geographic coordinates.
- **Data Visualization:** Creates scatter plots to showcase the relationships between latitude and weather variables such as temperature, humidity, cloudiness, and wind speed.
- **Linear Regression Analysis:** Computes and visualizes linear regression models to further analyze the relationships between weather variables and latitude for both the Northern and Southern Hemispheres.
- **Comprehensive Plots:** Generates plots that include regression lines, equations, and r-values to help interpret the data effectively.

## VacationPy

VacationPy is a Python-based tool that leverages the weather data collected in WeatherPy to recommend ideal vacation destinations based on user-specified weather criteria. By filtering cities based on temperature and humidity preferences, VacationPy identifies potential vacation spots and highlights nearby hotels using the Geoapify API.

### Features

- **Weather-based Filtering:** Filters cities based on user-defined temperature and humidity ranges to find ideal vacation spots.
- **Hotel Search:** Uses the Geoapify API to find and highlight hotels near the recommended vacation destinations.
- **Interactive Map Visualization:** Visualizes the filtered cities and nearby hotels on an interactive map using the `hvplot` and `geoviews` libraries.

## Project Structure
- WeatherPy.ipynb: The Jupyter notebook containing the code and analysis for weather data visualization.
- VacationPy.ipynb: The Jupyter notebook containing the code for vacation destination recommendations.
- README.md: Project description and instructions.
- requirements.txt: List of required Python libraries.
### Requirements
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Requests
- SciPy
- Citipy
- GeoViews
- hvPlot