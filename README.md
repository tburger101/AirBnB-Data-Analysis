# AirBnB-Data-Analysis
This project analyzes Seattle AirBnB data.  In particular I am looking to see what attributes, time of year, and neighborhoods have the greatest impact on price.

## Required Libraries
* sklearn
* numpy
* pandas
* matplotlib
* seaborn

## Files

* AirBnB.ipynb - This is jupyter notebook where the data analysis is done.
* listing.csv - listing attribute data.
* calendar.csv This file was not included due to it's size.  Download from https://www.kaggle.com/airbnb/seattle/data

## Data
The data being analyzed comes from a kaggle competition.  
https://www.kaggle.com/airbnb/seattle/data

We focused on two specific files:

* calendar.csv - This shows what listings are available each day throughout the year and how much the listings are cost on that date.
* listing.csv   - This file provides attributes that describe each listing i.e. bedrooms, neighborhood, property type etc.



## Acknowledgements
https://pbpython.com/currency-cleanup.html - Used as a resource to clean some data

## Summary of Findings
After reviewing the data there are couple of interesting points.  Neighborhood and property type look to be the two biggest drivers
of the price of AirBnB rentals in Seattle.  In addtion the most popular months to visit Seattle look to be in July and August.
As well as being the most popular they also tend to be the most expensive.  However, while most properties do change their prices for
the summer months there are around 40% of units which never vary their price.  These are probably the AirBnBs that offer the best
deals.

