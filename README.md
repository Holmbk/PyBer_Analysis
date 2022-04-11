# PyBer_Analysis
Creating DataFrames of Ride-Sharing Data by City Types

## Overview of Project

Using Pandas and Matplotlib multiple-line graphs are created showing the total weekly fares for each city type.

### Purpose

Technicla analysis of ride-sharing data by city types to create a summary DataFrame by data type and a multiple-line chart of the total fares for each city type.

## Analysis and Challenges

### Deliverable 1
The challenges of the first deliverable was using Pandas groupby() functionl with the count() and sum() methods on PyBer DataFrame columns.  Once you got the total number of rides, total number of drivers, and total fares for each city type, you calculate the average fare per ride and average fare per driver for each city type.  This is displayed in a summary.

![This is image of summary](/Summary%20by%20City%20Types.png)

The urban total fares are much higher that either of the other city type.  The average fare for the urban was the lowest, but the large amount of riders makes the total fares the highest.  the rural had the highest fares but the losest amount of riders to make up the lowest total of fares.

### Deliverable 2
The challenges of the second deliverable was using Pandas functions pivot() and resample() to create a multiple-line graph that shows the total fares for each week by city type.

![This is image of line chart](/PyBer_fare_summary.png)

The most amount of fares for each city type was in late February, and the urban travels was in late february and early March.  Urban definately had the most fares for the time shown.
