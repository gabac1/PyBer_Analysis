# PyBer Analysis
## Overview of the analysis:
This analysis aims to reveal the different nature of PyBer operation among 3 different area types, namely urban, suburban and rural, in terms of factors such as total number of drivers, total fare, average fare per ride by each area type, etc.

## Results:
The results are summarized in the table below:
|             | Total Rides	| Total Drivers	| Total Fares	| Average Fare per Ride	| Average Fare per Driver |
|-------------|-------------|---------------|-------------|-----------------------|-------------------------|
| Rural	      |         125	|         78	  |     4327.93	|           34.623440	  |        55.486282        |
| Suburban	  |         625	|         490   |   	19356.33|         	30.970128	  |        39.502714        |
|  Urban	    |        1625 |       	2405	|     39854.38|          	24.525772	  |        16.571468        |

As can be seen, in total rides, total number of drivers and total fares, the three areas types ranks in the order of urban, suburban, and rural in terms of value from high to low. The Urban area takes up the majority portion of the revenue, whereas the contribution of rural area is the smallest among the three. However, for the average fare per ride and average fare per driver, the above-mentioned ranking is reversed. The urban area has the least per ride and per driver fare. The difference is most significant for the per driver fare, as the urban area is the only one with more drivers than rides in the timeframe of the data.

![alt text](https://github.com/gabac1/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
The above figure demonstrates the time series of the weekly total fare of the three types between Jan 1, 2019 to Apr 29, 2019. No obvious trend can be observed from the revenue of any of the three types.

## Summary:
Based on the above analysis, it seems that the drivers in urban area is at or even over the saturation level, whereas the situation is unclear for the other 2 areas. Several possible actions could be helpful in the current scenario:
1. Advertising more in the urban area to increase the ride. Although contributing the majority of the revenue, the performance in urban area is not necessarily efficient. The urban area has lower rides per driver ratio than both of the other two, thus the driver in the urban area is at a great extent idle.
2. Halting the recruitment of new drivers in the urban area. Although the urban area is the biggest market, the future profitability under the current situation is unclear. Further expansion may lead to negative results.
3. Doing more research on the profit margin of all three areas. The current available data only contains revenues, but without the information of costs in different regions, it is hard to draw further conclusion.
