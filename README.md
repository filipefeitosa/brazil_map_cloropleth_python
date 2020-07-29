# brazil_map_cloropleth_python
Data visualisation is an important skill when searching and presenting important insights. There are many visuals that can be used to present your data. One of the most interesting data visual is the cloropleth map.

Why is this such an interesting visual? a) it is pretty, b) it tells us the data that we are interested in exactly the location of where it is associated in, and c) it is pretty!
With the introductions done, let’s get down to the code (and the preparations for it).

## Get the data
There are two kinds of data that we will need for this exercise:

1. The data that will be mapped to locations/regions/areas/etc. There are plenty of open data that we can use freely, one if it is from Wikipedia (data accuracy and validity not guaranteed, but for this learning exercise, no problem!). For this exercise, we will use the data for each state in Brazil.

2. The second data is a shapefile of the map that we want to make. It is basically a list of geometric locations (either in points, lines, or polygons). Since we want to map Brazil’s states, we will download Brazil’s Administration area [here](http://www.diva-gis.org/datadown)
