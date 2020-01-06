# Spatio-Temporal-Data-Analysis

In this project, I have performed spatio temporal analysis of all the ports in Canada based on the movements of vessels visiting the ports.
Densities are analyzed and displayed on color coded map including overall vessel movements data and hourly movements of vessel data.
Ports information is found in the shape file and vessel movements are found in the csv file attached to the repository.

Steps followed for this project:

1. Finding all the vessels that visited ports in Canada. For this part, I will create a buffer
with a 5 km radius around the center of each all Canadian ports. Second, I will find
all the AIS data that intersect with these ports. 
2. Showing the density (i.e., density is the number of vessels in that port), of each port on a map by
using a color-coded map. 
3. Now dividing the AIS data into data frames with one-hour interval. Repeat steps 1 and 2 for all
of the sub-dataframes. Here each data frame has only information of one hour. 
4. Selecting any port I like. Create a temporal chart for the density of that port. The x is the time
and each snapshot of the time has the density of port at a specific hour. 
5. Using concept drift methods on step 4 and finding out if there is any drift in the data can be
detected. I will try to play with the input parameters and justify the one I chose. Trying to explain why
the drift was detected, what characteristics changed? 
6. Clustering the ports based on their density using DBSCAN and categorize the Canadian ports
based on traffic (density). Repeating this procedure for both dataframes created in steps 2 and 3.
