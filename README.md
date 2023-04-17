<!-- # leaflet-challenge
Challenge 15


Our first task is to visualize an earthquake dataset. Complete the following steps:

Get your dataset. To do so, follow these steps:

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

Import and visualize the data by doing the following:

Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

Hint: The depth of the earth can be found as the third coordinate for each earthquake.

Include popups that provide additional information about the earthquake when its associated marker is clicked.

Create a legend that will provide context for your map data.


Map (60 points)
  TileLayer loads without error (20 points)
  Connects to geojson API using D3 without error (20 points)
  Markers with size corresponding to earthquake magnitude (10 points)
  A legend showing the depth and their corresponding color (10 points)

Data Points (40 points)
  Data points scale with magnitude level (10 points)
  Data points colors change with depth level (10 points)
  Each point has a tooltip with the Magnitude, the location and depth (10 points)
  All data points load in the correct locations (10 points) -->
