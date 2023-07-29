# DA-DelhiCrimeStats

A. For the data:
1. Processed Crime on Women Statistics district wise from Govt Census website.
2. Used mean and avg pop. growth to calculate 2020 est. population of Delhi district wise.
3. Used Excel formulae with Manipulations through pandas and get common index, parts per lakh.

B. For the map:
1. Created the name/node/relationship Mapping of Delhi Districts using OverpassTurbo.eu and OpenStreetMap(Will put the shapefile with the district order to make it easier for anyone who wants to use it)
2. Converted .kml and .geojson to extraxt .shp(shapefile) and .shx
3. Used Geopandas and Matplotlib.pyplo to show 2D choropleth map of Crime Stats.
4. Used annotation methods from plt(took some time)
5. Deduced cordinates from Polygon geometric shapes of the shapefile
