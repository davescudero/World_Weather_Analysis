# World_Weather_Analysis
## Overview of the analysis
With this challenge we can apply analysis, visualization and statistical skills by retrieving specific data through Google Maps APIs
## Results
1. First we need to retreive the information needed to make the analysis, so we decided to use  np.random.uniform function in order to create the coordenates for the analysis
```
#Create a set of random lats y lngs combinations

lats=np.random.uniform(low=-90.000, high=90.000, size=2000)
lngs=np.random.uniform(low=-180.000, high=180.000, size=2000)
lat_lngs=zip(lats,lngs)
lat_lngs
```
2. Then we need to filter the data with the preferred characteristics of the desired destinations
![Preferred_cities.png](https://github.com/davescudero/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Itinerary/Preferred_cities.png)
3. After we had our filter data we have to add marker layer to the desired map with gmaps
![WeatherPy_vacation_map.png](https://github.com/davescudero/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Search/WeatherPy_vacation_map.png)
4. Finally, we selected four random cities to plan a vacation and randomly selected four Brazil's cities. Below is the itinerary which starts and end in Ontario.

Start at: Ontario, US
-Visit Cabo San Lucas, Mx
-VIsit Xaltianguis, Mx
-Visit Puerto Escondido, Mx
-Finish with Nata, Pa
With the use of waypoints we were able to map the driving route to visit these four cities
![WeatherPy_travel_map.png](https://github.com/davescudero/World_Weather_Analysis/blob/main/World_Weather_Analysis/Vacation_Itinerary/WeatherPy_travel_map.png)

WE CAN ENJOY OUR VACATIONS IN MEXICO
