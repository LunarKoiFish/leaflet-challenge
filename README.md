# leaflet-challenge

The goal of this challenge is to help the USGS develop a way to visualize earthquake data that can potentially allow the scientists to help better educate the public on issues on our planet.

There are two parts to this challenge, with the second part being optional. The first part and main goal is creating the earthquake visualization.

First, we use data given by the USGS website in the form of a JSON. We can use that URL of the JSON to pull data into our script to visualize the data. Though in the starter code, the URL is already provided within our script and it is the URL to providing all earthquake data from the past week or 7 days.

Once we pulled the data, we then use Leaflet to create a map that plots where the earthquakes are. Those data markers are then coded to reflect the magnitude of the earthquake by the size and the depth of the earthquake by the color. So in our leaflet map plot. The bigger the data marker means the stronger the magnitude. And then the color ranges from red to green, with red representing depth of 90+ km and green being -10km to 10km depth. To view the exact info, you can click on each data marker and a info popup will display the exact magnitude value, location and depth, which is the 3rd coordinate for each earthquake.

Though I did not complete the optional 2nd part. I was playing around with the help of Xpert Learning assisant to additionally add tectonic plate data. Which basically shows where the fault lines are on our map. 

This challenge was completed with the help of past activities and Xpert Learning Assistant. There are parts of my code that was authored by Xpert Learning Assistant that I used in difficult parts of the challenge such as setting up the loop for the legend.
