# Surfs Up
W. Avy would like more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Overview of statistical analysis
Using Python, Pandas functions and methods, and SQLAlchemy, I will filter the date column of the Measurements table in the [hawaii.sqlite](https://github.com/vzhang90/surfs_up/blob/main/hawaii.sqlite) database to retrieve all the temperatures for the month of June & December. The query will first convert those temperatures to a list. Then a DataFrame will be created from the list to generate the summary statistics.

## Results
The summary statistics for June's temperature can be seen below in comparison to December's
  
![june_temps](https://github.com/vzhang90/surfs_up/blob/main/june_temps.png)  ![dec_temps](https://github.com/vzhang90/surfs_up/blob/main/dec_temps.png)

- The month of June has significantly average higher temperatures than that of December
- The higher standard deviation of December indicates increased temperature variation
- December's max temperature is only 2&deg;F lower despite December's min temperature is 7&deg;F lower compared to June's 

## Summary
From this statistical analysis, June can be seen to average 4 degrees warmer temperatures than December. This will overall lead to increased surf and ice cream shop business. The higher temperature variance in the month of December will slow business; but the max temperature being similar to June's indicates sales could stay solid during days when temperatures are within June's standard deviation of the mean (71.7&deg;F to 78.2&deg;F)

There could be additional queries to obtain data for more months of the year to compare as well as precipitation data.
