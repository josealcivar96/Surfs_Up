# Surf's Up weather analysis

## Overview

The purpose of the following analysis is to uncover trends in weather during the peak of summer (June) and winter (December) at the island of Oahu, with the purpose of measuring the sustainability of a surf and ice cream shop year-round. For this analysis we used a SQLite Database and a Pandas DataFrame to showcase a statistical summary of the temperatures of the island.  

## Results

In our results we can observe three main points of contrast among the statistical information between the two months:

- The *mean* temperature for June is **75** degrees, whereas the mean temperature for December is **71** degrees. Which is not a big difference in average temperature overall. Depending on the sunshine hours, it may be insignificant in the influence that it has on people's desires for cold refreshments during the day.
- Another metric of note is the *minimum* temperature that is present on the two months, as that could be a big deterrent for the public when looking to buy ice cream. The month of June has a minimum temperature of **64** degrees, whereas December has a minimum temperature of **56** degrees. Both of these temperatures should be considered outliers, as they fall outside **1.5** times the interquartile range for both months. As a consequence, really cold days are rare on both months.
- Finally, the *maximum* temperature for June and December are **85** and **83** degrees respectively. While these temperatures can still be considered as outliers and rare, it is to note that the upper limit of temperatures are fairly consistent between months, getting to the conclusion that the climate is temperate and largely constant across the year.

## Summary

We can see through these results that the temperatures throughout the year remain fairly consistent regardless of the season the residents of Oahu find themselves in. Any day would be as desirable to surf and have cold ice cream as any other. It shows a sustainable business model for this particular market.

However, temperate is merely a component in the larger scope of climate and desirability for cold refreshments. It is suggested we must deepen our queries to expand the information that we have available to analyze the reach and limits of our industry. These queries to perform would largely be focused on analyzing the other metric we have available on our database, *precipitation*:

- We need to obtain average precipitation and compare among the months alongside temperature.  
- We may also expand our search to include other months of the year, specially if we're looking at precipitation, as it can help plan accordingly with sudden, but recognizable patterns of adverse weather conditions.
