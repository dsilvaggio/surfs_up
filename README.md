# surfs_up
## Overview
  An analysis of weather data from the island of Oahu was performed to determine if a new surfboard and ice cream shop will be successful year-round. Investors specifically requested temperature data from June and December to help make this decision. The analysis will help investors determine if this new shop will be a successful investment. 
## Results
After filtering the data for both June and then December, I queried the data to retrieve all past temperatures for those months. I then generate the summary statistics for the temperatures of both June and December. The summary statistics for both months can be seen below:

![This is an image](https://github.com/dsilvaggio/surfs_up/blob/main/Resources/Screen%20Shot%202022-04-18%20at%205.40.49%20PM.png)
![This is an image](https://github.com/dsilvaggio/surfs_up/blob/main/Resources/Screen%20Shot%202022-04-18%20at%205.40.59%20PM.png)

From the above information, we can see that:
  - There are almost 200 more records for June data than there are for December
  - The average temperature for these months only differs by about 4 degrees (74.94 - 71.04)
  - The coldest recorded temperature from these 2 months was in December and was 56 degrees. 
  - The hottest recorded temperature from there 2 months was in June and was 85 degrees.
  - The max temperatures from these 2 months only differ by 2 degrees (85 - 83)
 
 ## Summary
 As far as the temperatures go for these two months, there isn't much of a difference between June and December. The weather only seems to fluctuate by a few degrees when comparing the winter and summer months. However, the above analysis does not tell us anything about precipitation levels. I ran a new query to retrieve the minimum, maximum, and mean precipitation levels for June and December to compare this data as well. The data I retrieved for June and December were (min = 0.0, max = 4.43, mean = 0.13635959339263018) and (min = 0.0, max = 6.42, mean = 0.21681850533807792) respectively. Based on this information, we can see that it is very possible to get higher levels of precipitation in December. However, the average precipitation levels are less than 0.1 inches apart which could tell us that there is not a large fluctuation in precipitation levels between the summer and winter months. One more follow-up query that I would suggest running is the temperature data and precipitation data filtered for both June and December but also grouped by the different weather stations. It is quite possible that different parts of the island experience different temperatures or precipitation levels. This could help both investors and the owner of this new shop determine the best place to build. 
