# Surfs Up
Module 9 Challenge

## Overview
We have been providing W. Avy, a potential investor, with weather analysis data from Oahu, HI to support his decision to invest in our ice cream & surf shop. One of his last requests was an analysis of the temperatures during the more extreme months of the year, June and December. We used SQLite and SQLalchemy to load the weather data and query it specifically for the months of June and December. Then we imported that data into Pandas dataframes so we could receive the summary statistics which will give us a good idea about the weather during those months.

## Results
https://github.com/rharazim/surfs_up/blob/main/Resources/june_results.png
- The average temperature for June is about 75 degrees Fahrenheit, which is perfect surfing weather, and the highest temperature recorded was 85 degrees, which would be great weather to sell ice cream.
https://github.com/rharazim/surfs_up/blob/main/Resources/december_results.png
- December was a little colder with the average temperature being around 71 degrees and the lowest recorded temperature being 56. Surfing and ice cream are both still possible with this weather, especially if the sky is clear and the sun is out.
- With these extreme months still being viable for our surf and ice cream business, it also tells us that all months inbetween will also be great for our business.

## Summary
After this analysis, the biggest concern is that it would sometimes be too cold to surf and sell ice cream in the month of December. A business plan to counter this unfavorable weather would be to stock up on wet suits to sell during the winter months so that surfers can still enjoy their sport even when the water is cold. Even though the low temperature during December is 56 degrees, the average temperature was still close to that of June, meaning there isn't too much of a difference month to month and that our business will be viable all year round. We could also look at the percipitation data to see if it affects the average temperature. Too much rain and we might not be able to do enough business. 
### Additional Queries
- We could query June and December total precipitation to see if there is a correlation between rainfall and the average temperature.
- Additionally, we could query June and December for the total number of observations above 70 degrees which is considered good surfing weather.


