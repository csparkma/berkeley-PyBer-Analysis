# berkeley_PyBer_Analysis
Module 5 in Berkeley Data Analytics Bootcamp

# Challenge Analysis
## Summary
The findings from our initial analysis into PyBer's ride sharing data necessitated further investigation. Based on feedback we received, we dug in to Pyber's Fare data to uncover any trends based on City Type (i.e. Urban, Suburban, and Rural). Using the merged data from the initial analysis (City and Ride data), we summarized the data set and plotted the `Sum of Fares for Each City Type`. We found that while overall volume of rides is greater in Urban cities, the average fare is higher in Rural areas leading to a higher average fare per driver. Unfortunately, it appears there are more drivers than there are rides in Urban cities, which means that there aren't enough Rides to support the amount of Drivers:
![Fare Summary](https://github.com/csparkma/berkeley_PyBer_Analysis/blob/master/analysis/Fare%20Summary.png)
We also found that Fares have been sporadic Week-over-week, but has been steadily increasing on average in Urban cities. It is hard to tell with so little data if this trend will hold. I would also be weary of drawing any conclusiosn regarding any upticks as we do not have a lot of time to work with. I would advise that we continue to monitor Fares and Rides by week to see if we start to see any seasonal trends:

![Fare Summary](https://github.com/csparkma/berkeley_PyBer_Analysis/blob/master/analysis/Total%20Fare%20by%20City%20Type.png)

## Challenges
I did not run into any challenges that are worth noting throughout this analysis. The data was clean and easy to work with. However, the reason why the data was so easy to work with was also the reason why it was hard to draw meaningful conclusions about time-based trends. The amount of data. With more data, we will be able to understand more about our business, but currently, we should refrain from jumping to any conclusions. 

## Conclusion
Based on the little data we did have, it is apparent that we need to put more effort into increasing our rider-base across all city types. Seeing as the lowest hanging fruit would be Urban cities, we should start there to uncover why we have more Drivers than we do riders. That is unsustainable and considering that the other city types have less in total fares combined compared to Urban cities, we cannot rely on the other cities to make this up. I would advise that we dig into rider and driver data to understand how the growth of drivers outperformed the growth of rides. The analysis should be fairly straightforward, but will require user-level data, or at least an aggregate level across time. 

This should be a top focus as our fares do not appear to be consistently increasing Week-over-Week.
