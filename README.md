# Python-APIs

## WeatherPy

Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 
To accomplish this, you'll be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), 
the [OpenWeatherMap API](https://openweathermap.org/api) 

The objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The final notebook must:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

As final considerations:

* Complete analysis using a Jupyter notebook.
* Use the Matplotlib or Pandas plotting libraries.
* Include a written description of three observable trends based on the data.
* Use proper labeling of your plots, including aspects like: Plot Titles (with date of analysis) and Axes Labels.



