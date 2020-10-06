# City_Divider

## Description and Results
While official borders exist, often unofficial border are more important. In this project I am to identify these unofficial border by sub-dividing cities using clusters of businesses within a city.

![New Rochelle](/geovoronoi_new_ro_economic_zones_adjusted.png)

The city of focus is New Rochelle, New York, a suburban city of New York City. The business data comes from Foursquare. The businesses are grouped into meta-categories (e.g.: "recreation", "schools", etc.) and then the business in those categories are used to divide the city. K-means clustering is used to group these businesses into clusters based on their coordinates. Visually, we see that 6 clusters makes the most sense in terms of clear intra-meta-category separation for New Rochelle. Because of the relatively "skinny" shape of New Rochelle, all of the clusters run along a north-south axis. 

## Technologies Used
- Jupyter Notebook
- Python
    - Pandas
    - Matplotlib
    - geovoronoi
    - Folium
    - scikit-learn
    - GeoPandas
    - Shapely
    - json
    - requests
