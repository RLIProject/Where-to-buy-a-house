### Where to buy a house in Scarborough, Toronto
#### My master data which has the main components Postcode, Borough, Neighborhood, Latitude and Longitude information of the neighborhood.
#### Then I used folium package in Python to visualize geographic details of Scarborough and its neighborhoods. I created a map and used latitude and longitude values to get the visual.
#### Methodology
1. Foursquare: By using Foursquare API, I explored the neighborhoods and segmented them. I set the limit as 100 venue and the radius 500 meter for each neighborhoods from their given latitude and longitude information. Here is a head of the list Venues name, category, latitude and longitude information from Forsquare.
2. There are 52 unique categories were returned by Foursquare, then I created a table which shows list of top 5 venue category for each neighborhoods in below table.
Methodology- Modeling
3. In order to identify where is the perfect location to buy a house, I need to group similar groups together. In this case, I tried clustering method: K-means algorithm to cluster the neighborhoods. K-Means algorithm is one of the most common cluster method of unsupervised learning.
