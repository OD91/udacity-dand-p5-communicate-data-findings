## Dataset

The data consists of information regarding 5,202,096 entries of flight data of the US, including among others
delays, airlines, and airports. The dataset can be found [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7),with feature documentation available [here](http://stat-computing.org/dataexpo/2009/the-data.html).

## Summary of Findings

In the exploration, I examined several aspects:

1. Airlines and their delays:
   In total the data set contains 14 airlines with DL airline the top one with almost 8000 flights. The CO airline has the longest average departure delay time of almost 9min. The PA(1) airline has the longest average arrival delay time of slighlty over 9min.

2. The relationship between arrival and departure delays:
   On average, the arrival delay's (6.62 Minutes) differ from the departure delay's (6.73 Minutes) just a few seconds. Therefore one could assume that there is a relationship between both variables. One could assume that there is a medium strong, positive, linear relationship between Departure Delay and Arrival Delay but there are too many data points overlapping so that a proper conclusion can't be stated.

3. Day of the week and delays
   Most flights are on a Wednesday, least flights are on a Saturday. We see that the worst day to travel is Thursday. The least delays and thus the best day to travel is on Saturday. We couldn't find any clear conclusion that the "Day of the Week" has a relationship with the length of Departure Delay and Arrival Delay. Also, too many points are overlapping each other.

4. Top 10 "Origin" airports and their average delay times.
   Airport ATL is the top Origin airport regarding value_counts in the data set. From the top 10 airports (regarding value_counts) airport EWR has the highest average Departure Delay (ca. 10min) and airport PIT has the highest average Arrival Delay (ca. 10min).

## Key Insights for Presentation

I examine the the relationships between departure delays and arrival delays as well as the variables airlines, day of the week, top airports as well as . I always try to start by first appying an univariate anlysis, followed by a bivariate analysis and subsequently, when applicable a multivariate analysis to examine the different relationships. I mainly use bar plots and scatter plots for showing my results (summarized in the above summary section).
