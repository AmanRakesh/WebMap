# WebMap
Webmap is a map of any place or region which has some custom layers included in it. 
In this file I have included a layer for:
1. Population density of different countries as of year 2005
2. Top 20 Waterfalls in India
3. Top 30 Temples in India

As the name suggest this Script makes one WebMap based on details provided.
The layers can be switched on and off as per your wish. Each marked point in the layer (either a circle mark or normal mark) wil show you the name of the place and will also let you search about the place in one click in google.
This Script makes use of Folium and Pandas library of python to generate the layers.
Folium makes use of map objects and traces the position of the marked points in World map with the help of Lattitude and longitude  of the given place.
For adding details of lattitude and longitude of places I have used txt files, and to draw population density polygon i have used world.json file which consist lat. and long. of countries  and their population.

Folium will save all the layers in a HTML file. So we need to check HTML file and see the details.
