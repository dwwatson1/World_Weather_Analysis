# Norway Spring Skiing Adventure: A World Weather Analysis 

## Overview of the Analysis

The purpose of this analysis was to analyze and visualize city weather data using an API to plan and map (also using a Google Maps API) a vacation. The data from the APIs helped me plan the perfect spring skiing intinerary in Norway!

## Results of the Analysis

### Analysis Resources
* Data Sources: [WeatherPy_Database](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv) & [WeatherPy_vacation](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)
* Software: Jupyter Notebook 6.1.4 
* Notebooks: [Weather_Database](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), [Vacation_Search](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb), & [Vacation_Itinerary](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)
 
### Overview of Results 

To begin planning my vacation, I needed to create a [Weather_Database](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb) to allow me to parse through the current weather conditions. Because I wanted to take a spring skiing vacation, I was looking for a location on the colder side. 

I began my [Vacation_Search](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb) by narrowing down max and min temperatures between 55 and 20, which are ideal for spring skiing. The vacation search yielded many cities and hotels in countries that typically see cold weather conditions, like Canada, as seen below.

![WeatherPy_vacation_map](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)

The Canadian locations, which display the nearest hotel  however, did not pique (peak, get it?!) my interest, I opted for something more adventurous and settled on Norway. I was strategic with my hotel picks as I wanted to stay as close to the mountains as possible. After settling on my preferences, I began building my [Vacation_Itinerary](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb). I was interested in exploring the entire country from South to North and my Google Maps driving itinerary reflects that below.

![WeatherPy_travel_map](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

Adding weather, city, country, and hotel data to the Google Maps markers made it easy for me to plan my stays at each hotel while also assessing ski conditions across Norway.

![WeatherPy_travel_map_markers](https://github.com/dwwatson1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG) 
