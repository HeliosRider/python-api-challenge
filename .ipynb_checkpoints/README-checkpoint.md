
**WEATHER ANALYSIS**

*Background*

This analysis contains a directory titled WeatherPy that consist of two deliverables, WeatherPy and VacationPy.
This WeatherPy file contains 2 Jupyter Source Files: WeatherPy.ipynb and VacationPy.ipynb.
The WeatherPy deliverables request relevant data from 2 API providers, OpenWeatherMap and Geoapify, for over 500 cities within the desired coordinates.

The two Jupyter Source Files utilize Pandas library to create DataFrame for each dataset. Matplotlib library was imported to create series of scatter plots based on different variables. 
Scipy and linregress were also imported to help with statistical computation and generate linear regresssion line for the data points. Citipy was imported to generate list of cities with the coordinates,
hvplot was imported for interactive data visualization, and geoviews is imported to explore and visualize geographic data.

*Objectives*

Deliverable #1 (WeatherPy)

1. Create Plots to Showcase the Relationship Between Weather Variables and Latitude
2. Compute Linear Regression for Each Relationship

Deliverable #2 (VacationPy)

1. Create a map that displays a point for every city in the provided dataset into a DataFrame
2. Narrow down the DataFrame to find your ideal weather
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map

*Note*
All figures and plots are located in the output_data file.