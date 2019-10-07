# Python_API_Challenge


This repository contains two parts: WeatherPy and VacationPy.


## WeatherPy


In WeatherPy, there is a script that visualizes the weather of 500+ unique cities across the world of varying distance from the equator. Weather data is collected by API calls from OpenWeatherMap.org.


There are a series of scatter plots to showcase the following relationships:


- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude


There is an analysis included for each graph.


In addition to the above visualizations, scatter plots and linear regressions are run on the following relationships:


- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude


For each plot, there is an explain about what the linear regression is analyzing along with further analysis of the data.


The output_data file will include:


- A CSV of the clean weather data
- All plots saved as PNG images



## VacationPy


This file includes a heat map that displays the humidity for every city found in WeatherPy.


Google Places API will be used to acquire café, restaurant, and museum data for Seoul, Korea. The data collected will be displaced on a map for visualization. 


The output_data file will include:


- All maps created


Along with what we learned in class, I also used the following resources to complete this assignment:


- https://medium.com/@kasiarachuta/dealing-with-duplicates-in-pandas-dataframe-789894a28911  
- https://jupyter-gmaps.readthedocs.io/en/v0.3.3/gmaps.html  
- https://jupyter-gmaps.readthedocs.io/en/latest/api.html#figures-and-layers  
- https://www.dataquest.io/blog/tutorial-advanced-for-loops-python-pandas/  
- https://jupyter-gmaps.readthedocs.io/en/latest/tutorial.html 
- https://jupyter-gmaps.readthedocs.io/en/latest/api.html 
- https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed  
- https://sciencing.com/info-8686864-latitude-altitude-affect-temperature.html 
- https://www.statsdirect.com/help/basics/p_values.htm 
- https://www.epochconverter.com/timezones?q=1569304051&tz=America%2FLos_Angeles  
- https://python-visualization.github.io/folium/quickstart.html 
- https://alysivji.github.io/getting-started-with-folium.html
- https://github.com/python-visualization/folium
- https://try.dominodatalab.com/u/joshpoduska/crimemaps/view/examples.ipynb
- https://blog.dominodatalab.com/creating-interactive-crime-maps-with-folium/
- https://www.machinelearningplus.com/plots/matplotlib-tutorial-complete-guide-python-plot-examples/  
- https://openweathermap.org/weather-data
- https://developers.google.com/places/web-service/search#nearby-search-and-text-search-responses
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html
- www.stackoverflow.com
- https://en.wikipedia.org/wiki/Coefficient_of_determination

