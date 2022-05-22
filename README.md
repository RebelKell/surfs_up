# Surfs Up Analysis

## Overview
In order to determine the viability of a two-in-one surf and ice cream shop we ran a temperature analysis for the months of June and December to gauge if the business would be sustainable year-round.

## Analysis
We ran queries on the the Hawaii weather SQLite database to get temperature data and read that data into a Pandas dataframe for ease of analysis. Once in the DataFrame we were able to get summary statistics for the two months we were most interested in.

## Results

- Average temperatures difference between June and December is only 3 degrees.
- Maximum temperature only differs by 2 degrees between the two months.
- Minimum temperature shows a slightly larger swing between the two months (7 degrees), but one would imagine these readings are taken at night, when no one is surfing or eating ice cream.

## Summary
Overall, it is safe to say that the temperature in Hawaii is mostly constant throughout the year and that temperature should not have a huge impact on the success of the business.

While it's safe to assume that temperature will remain the same, it would be worth performing the same analyis for both precipitation and wind, as these two variables will also impact if potential customers are willing to go surfing and eat ice cream.