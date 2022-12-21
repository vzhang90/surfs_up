# Surfs Up
W. Avy would like more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Overview of statistical analysis
Using Python, Pandas functions and methods, and SQLAlchemy, I will filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June & December. The query will first convert those temperatures to a list. Then a DataFrame will be created from the list to generate the summary statistics.

## Results
The summary statistics for June's temperature can be seen below in comparison to December's
  
![june_temps](https://github.com/vzhang90/surfs_up/blob/main/june_temps.png)  ![dec_temps](https://github.com/vzhang90/surfs_up/blob/main/dec_temps.png)

- The month of June has significantly average higher temperatures than that of December
- The higher standard deviation of December indicates increased temperature variation despite the lower min & max temperature compared to June

## Summary
