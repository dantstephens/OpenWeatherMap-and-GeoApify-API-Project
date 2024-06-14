# OpenWeatherMap-and-GeoApify-API-Project

## About this project
This project consists of two different notebooks demonstrating the use of APIs to import data for analysis

### WeatherPy
This notebook demonstrates the use of the OpenWeatherMap API to import weather data for a randomly selected set of locations. With the data imported into a dataframe, Matplotlib is used to compare and plot multiple weather characteristics(humity, cloudiness,, etc) to latitutde. Finally linear regression models are used to see if latitude can be used to predict weather characteristics. 

### VacationPy
This book demonstrates the use of the Geoapify API to import hotel data for ideal vacation locations to be plotted on maps generated using hvPlot. The output CSV file with locations and weather charateristics from WeatherPY is imported and is narrowed down using my idea weather characteristics. The narrowed down list of locations is then used to obtain hotel information for each, which is then plotted on an interactive map. 

## Accessing resources for this project

Since this project was completed in Jupyter Notebook, it is not necessary to download and run the scripts to view the output and analysis as the notebook with outputs can be viewed in GitHub. The completed notebook can be accessed in the root folder of this repo. 

If planning to test the scripts please download the entire folder to retain the path to resource files. Additionally, a new document titled api_keys.py will need to be created in the root folder where the WeatherPy and VacationPy notebooks are located to store the API keys needed when running the scripts. 

in this docement, the API keys should be added in the following format, with "your_api_key" being replaced with a work API key for each API. 

```
# OpenWeatherMap API Key
weather_api_key = "your_api_key"

# Geoapify API Key
geoapify_key = "your_api_key"
```
Keys for each API can be found at:

OpenWeatherMap API: https://openweathermap.org/api

Geoapify API: https://www.geoapify.com/

