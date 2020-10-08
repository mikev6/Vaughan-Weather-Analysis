# Vaughan-Weather-Analysis
  Analyzing weather on the opposite side of the world
  
## Overview
This script displays current weather temperature in cities in North and South America, and compares that to the temperature on the exact opposite side of the world. I initially only included cities in the United States, but I wanted to get more diverse data, and observe wider data trends.
It uses the OpenWeatherMap.org API to gather this data. 

## Goals
The initial goal of this project was to implement the OpenWeatherMap API, as this is something I have not done before, to get current weather data. The API has a lot of other functionality, but I only needed two different calls to implement this. 
The second goal was to use the data gathered by the API to and  the tools learned in class, such as Pandas DataFrames and matplotlib, to provide quantitavive and visual analysis with this data.

## Motivation/Background
The data on this is interesting, because there is definitely variation, and some trends, in part becausse the Unite States has such diverse weather. The data would be more interesting if we were in the peak of either summer or winter, as that's when Earth has the biggest disparity in temperatures between the hemispheres. Because we're in fall (very close to the fall equinox, in fact), the differences in temperature between a given point and that on the other side of the world, while interesting, is less dramatic.

I'm not aware of anyone doing this specifically, but these two resources were helpful in implementing this:
  The first link is pretty straightforward, and allowed me to implement the API. Once I saw an example for this API in Python, it was very straightforward to implement other APIs, as the OpenWeatherMap API page displays their APIs and provides brief descriptions.
  https://knasmueller.net/using-the-open-weather-map-api-with-python
  Below is a link to the OpenWeatherMap API. It was very straightforward to register to get a Key ID to use in the API.
  https://openweathermap.org/current
  Once I could get the data from the API, I wanted to organize it. I wanted to have very modular code, so I made functions to simplify each API call, and I used a for loop to build a dataframe. The below link helped me create a Pandas DataFrame and add the data I was getting from the API.
  https://stackoverflow.com/questions/28056171/how-to-build-and-fill-pandas-dataframe-from-for-loop/42670389
  
  
## Table of Content
The code can be found at the following link:
  https://github.com/mikev6/mv6-Weather-Analysis/tree/main/code
The report is in the Jupyer notebook, below the code.
This code reaches out to OpenWeatherMao.org and organizes the data in a Pandas DataFrame. The graphs are written to this location:
  https://github.com/mikev6/mv6-Weather-Analysis/tree/main/plots


## Software Requirements
Packages that were used were the following:
  requests
  json
  pandas
  matplotlib
  
## Data 
The datafile can be found here:
  https://github.com/mikev6/mv6-Weather-Analysis/tree/main/data
Number of rows: 30 (not including header row)
Number of columns: 6 (not including indexing

The OpwnWeatherMap.org API is required to run the script. Here is the link to getting the OWM API:
  https://openweathermap.org/appid#get
  
This project promps the user for the API key, which is then used to gather the data.THere is a free version, which was used for this project.
  The limits on the free API are as follows:
    60 calls/minute
    1000 calls/hour
    1,000,000 calls/month

The jupyte notebook has two blocks; one that retrieves and organizes the data, and one that plots the data.

The Technical Report is located in a block below that.
  


