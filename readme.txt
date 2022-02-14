What our program does is it used 2 external libraries 
1 . unfolding maps(api)
2. processing.io

now using unfolding maps we get all the map functionalitites

We use a us goverment official site to get the data for earthQuake
We use Microsoft.HybridProvider to get the map object
We have two data files - city-data.json and country.json which provide us with
the data of city and country and also their properties.Each object is of type Feature
which we parse using inbuilt libraries GeoJsonReader 

Also we after parsing earthquake data we use print the top 10 earthquake locations of the world

For marking cities I used a red triangular marker and when you hover over it 
it shows the country you belong to and the size of the city

For marking landQuakes I have used yellow circular markers and to mark oceanQuakes
I have used the yellow Square Marker

Now when you click on a city it shows what are the earthquakes that can affect it and
and hide all other quakes

When we click on a earthquake it shows what are the cities which are in its range
and hides all the cities


We also created the keys for the users to understand.Also larger the earthquake larger will be the
marker size

We also give different colors to different quakes based on depth
We add a X on the marker if it is in past day or so

We also print number of quakes that has occured in a country and also the number of ocean quakes


Main File - EarthQuakeCityMap
