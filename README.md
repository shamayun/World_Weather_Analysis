# World WeatherAnalysis
Utilizing python modules and API's to retrieve and analyze data to provide suggestions based on criteria such as weather, city, country
# Resources
* Python, 
* JupyterNotebook
* Google Cloud Platform, 
* Google MapsAPIs
# Overview 
The goal of the project is to retrieve weather data from OpenWeatherMap API and build a heatmap on Google map showing suitable temperature for preferred vacation destinations. Users can define the range of desired temperatures, preferred minimum and maximum for the next vacation. Based on their chosen criteris heatmap and tags with available hotels are displayed. Also, there is a possibility to build a route on map for round trip by driving or walking. This project was tested with 4 destination and a round trip, many other combinations are posssible. Sunch as one-way trip with 10 different destinations.
# Results
Randomly generated coordinates (2,000 latitudes and longitudes) using numpy library, I retrieved city name. Which are nearest to the generated coordinates, with a citipy library. Once city names were recorded, I made API request to retrieve weather data from OpenWeatherMap and stored the result in WeatherPy_Database.csv for futher analysis.

In the next phase, I requested input from end-user, where they can provide their preferred temperature to stay within suitable weather zone. Results were filtered cities which are within the range and using Google API the users can choose hotels nearest to these cities. Also created the heat map with tags for selected hotels and cities for easy and simple visualization.
