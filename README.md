# sqlalchemy-challenge
Module 10 SQL Challenge for Laura Jordan

## Description
In this exercise, I pretended that I was scheduling a trip to Hawaii and in preparation for the trip, I decided to do a climate analysis about the area. This challenge had 2 parts to it:
* Part 1: Analyze and Explore the Climate Data
   - Precipitation Analysis
   - Station Analysis
* Part 2: Design a Climate App

## Part 1: Analyze and Explore the Climate Data
In this section, I used Python and SQLAlchemy to do basic climate analysis and data exploration of the climate database. Specifically, I used SQLAlchemy ORM queries, Pandas, and Matplotlib.
* Precipitation Analysis
   - Found the most recent date in the dataset 
   - Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data
   - Selected only the "date" and "prcp" values
   - Loaded the query results into a Pandas DataFrame, and set the index to the "date" column
   - Sorted the DataFrame values by "date"
   - Plotted the results --> Image: daily_precipitation_plot.png
* Station Analysis
   - Designed a query to calculate the total number of stations in the dataset
   - Designed a query to find the most-active stations, listing the stations and observations in descending order and answering which station id had the greatest number of obervations
   - Designed a query that calculates the lowest, highest, and average temperatures that filters on the most-active station id found in the previous query
   - Designed a query to get the previous 12 months of temperature observation (TOBS) data
   - Plotted the results --> Image: 12_mos_USC00519281.png
   
## Part 2: Design a Climate App
In this section, I designed a Flask API  based on the previous queries.

STILL WORKING ON THIS SECTION
   

## Support
I attended class, attended a tutoring session, watched class recordings and reviewed my notes for the support needed for this challenge assignment.

## Submission Includes
#### Part 1: Analyze and Explore the Climate Data:
* climate_LJordan.ipynb
* Image: daily_precipitation_plot.png
* Image: 12_mos_USC00519281.png
#### Part 2: Design a Climate App:
* app.py
* ANYTHING ELSE??
#### Resources Folder:
* hawaii.sqlite
* hawaii_measurements.csv
* hawaii_stations.csv
