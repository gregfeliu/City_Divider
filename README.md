# City_Divider

Cities have borders, but how can we identify the regions within those borders? In this project, I use the business centers within a city to sub-divide it. 


![New Rochelle](/geovoronoi_new_ro_economic_zones.png)

The city of focus is New Rochelle, NY, a suburban city of New York City. The business data comes from Foursquare. The businesses are grouped into meta-categories (e.g.: "recreation", "schools", etc.) and then the business in those categories are used to divide the city. Kmeans clustering is used to group these businesses into clusters based on their coordinates. Visually, we see that 6 clusters makes the most sense in terms of clear intra-meta-category separation for New Rochelle. Because of the relatively "skinny" shape of New Rochelle, all of the clusters run along a north-south axis. 
