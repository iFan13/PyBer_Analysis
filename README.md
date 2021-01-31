# PyBer Analysis

## Overview

V. Isualize has requested a summary of information for PyBer. This is to be acomplished using Pandas and Matplotlib libraries in Python. The requested format of the results is a minimum of one DataFrame and at minimum one multiple-line graph. In the dataframe, of particular interest is the Total Rides, total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver separated by the type of trip (Rural, Suburban, Urban). With regards to the multiple-line graph, of interest is the total fares history per type of ride. 

## Results

![PyBer Summary](analysis/PyBer_Summary_df.png)

There is a lot of available information from the summary dataframe shown above.
It can be shown in a pie chart form that a majority of rides are urban in nature. It can also be seen that a majority of drivers are also urban (also in pie chart form).

![Ride&DriverDistribution](analysis/Ride_Type_and_Driver_Distribution.png)

Similarly, the total fares also has a heavier distribution towards urban cities. However, the average Fare per Ride favours Rural cities. This statistic aligns well with the description of a rural nature in that destinations are frequently further apart. The increased average fare per ride coincides with this as one could expect a ride to a farther location will imply more time to arrive. However, when comparing average fare per ride to average fare per driver, it is implied that the method of fare/pay distribution is imbalanced and favours the drivers in rural cities as depicted below.

![AverageFares](analysis/AverageFaresByRide&Driver.png)

The total rides being lower in the rural and suburban areas suggests that the population in those cities will more than likely have a personal means of transportation and will not use PyBer as frequently as it is statistically more expensive, perhaps not as available or perhaps not as necessary. 


## Summary

Using this data, we can approach a growth of PyBer in a couple different methods.

The first method involves accessibility via supply of drivers. Under the assumption that PyBer is not used because it is not available, one method to grow PyBer would be to increase accessibility in Rural and Suburban cities by increasing the number of drivers in rural and suburban cities. This would reduce the average fare per driver while keeping the average fare per ride the same but can ultimately raise the Total Fares if there is a greater supply assuming a demand exists. 

A second method to improve on PyBer's growth is to consider fares. We can consider investing in the existing Urban market as Urban rides has the highest distributions in ride types. This could mean potentially increasing fares for urban zones which would push the total fares up but also assumes that customers will continue to use PyBer at it's current rate. Piggybacking on the concept of accessibility for Rural areas as mentioned in the first method, decreasing the fares in rural cities may create additional demand as a result of more inexpensive fares. This can potentially lead to a greater overall use and profit. 

Finally, A third potential course of action that can be recommended is 

