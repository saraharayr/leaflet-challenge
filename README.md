# Leaflet Homework: Visualizing Data with Leaflet

# Before You Begin


Create a new repository for this project called leaflet-challenge. Do not add this homework to an existing repository.


Clone the new repository to your computer.


Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: Leaflet-Step-1 and Leaflet-Step-2.


This homework uses both html and JavaScript so be sure to add all the necessary files. These will be the main files to run for analysis.


Push the above changes to GitHub or GitLab.



# Your Task

Level 1: Basic Visualization

Your first task is to visualize an earthquake data set.


## Get your data set

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick a data set to visualize. When you click on a data set, for example "All Earthquakes from the Past 7 Days", you will be given a JSON representation of that data. You will use the URL of this JSON to pull in the data for our visualization.



## Import & Visualize the Data
Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.


Your data markers should reflect the magnitude of the earthquake by their size and and depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.


## HINT: The depth of the earth can be found as the third coordinate for each earthquake.


Include popups that provide additional information about the earthquake when a marker is clicked.


Create a legend that will provide context for your map data.


Your visualization should look something like the map above.
