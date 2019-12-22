# Spatio-Temporal-Data-Analysis

In this prject, we have spatio temporal analysis of all the ports in Canada based on the movements of vessels visiting the ports.
Densities are analyzed and displayed on color coded map including overall vessel movements data and hourly movements of vessel data.
Ports information is found in the shape file and vessel movements are found in the csv file attached to the repository.

Steps followed for this project:

1. Finding all the vessels that visited ports in Canada. For this part, you are going to create a buffer
with a 5 km radius around the center of each all Canadian ports. Second, you are going to find
all the AIS data that intersect with these ports. ( 20 points )
2. Showing the density (i.e., density is the number of vessels in that port), of each port on a map by
using a colour-coded map. ( 20 points )
3. Now dividing the AIS data into data frames with one-hour interval. Repeat steps 1 and 2 for all
of the sub-dataframes. Here each data frame has only information of one hour. ( 20 points )
4. Selecting any port you like. Create a temporal chart for the density of that port. Your x is the time
and each snapshot of the time has the density of port at a specific hour. ( 20 points )
5. Using concept drift methods on step 4 and finding out if there is any drift in the data can be
detected. Try to play with the input parameters and justify the one you chose. Trying to explain why
the drift was detected, what characteristics changed? ( 25 points )
6. Clustering the ports based on their density using DBSCAN and categorize the Canadian ports
based on traffic (density). Repeating this procedure for both dataframes created in steps 2 and 3.
