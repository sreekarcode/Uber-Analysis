# Uber-Analysis
﻿
## Challenge #1 (Data Preparation)

• During my data preparation, i noticed that not all the csv files have the same columns and have variable data, except for the file names beginning with uber-raw-data. Hence i segmented only the files consisiting like so and put them in one combined dataframe and used it to perform different analysis

• I then checked for any missing values

## Challenge #2(Temporal Analysis)

• Here, I used the 'Date/Time' column to get the date time stamps and used them to manipulate and get the three desired outputs, which were

• distribution of time pickup drivers spent in a week

    • distribution in hours
    
    • distribution in hour of the day
    
• They were displayed as bar-plots for convenience.

## Challenge #3(Spatial Analysis)

Here, i took the Longitude(Lon) and Latitude(Lan) columns to use for getting the clusters.

    • I sampled the data, and made sure to only use 10% of the data to get a better computational speed.
    
    • A K-Means clustering has been performed and according to the values, clusters were plotted.
    
        • What can be inferred is that, the frequency of demands are higher for longitudes between [-74.5 to -74.0] and latitude[40 to 41.2].
        
        • The minute demands are varying across latitude of [41.1 to 40.0] and longitude of [-74.5].

## Challenge #4(Customer Behavior Analysis)

• Here, I calculate the ride frequency of each user, using the unique ID(base) column.

    • I then use the latitude and longitude values to find out the common routes taken across the map.
    
    • It can be inferred that 'B02617' has the highest frequency of ride count and the least frequency is 'B02512'.
    
    • It can also be inferred that, all the uber's have the same common route, meaning they all have the same direction sense as per the app or street knowledge. This can show increase in familiarity between drivers and since there is a common route, there can be a high level of safety between passengers.
