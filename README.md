# School District Analysis

## Deliverables for analysis of school district

* Snapshot of the District's key metrics

* Overview of the key metrics for each school

* Tables presenting each of the follwing metrics

* Top 5 and bottom 5 performing schools, based on the overall passing rate
  * The average math score received by students for each grade level in each school
  * The average reading score received by students for each grade level in each school
  * School performance based on budget per student
  * School performance based on school size
  * School performance based on type of school

## Overview of the School District Analysis

### There is a potential issue with the 9th grade data from Thomas High, possibly tampered with so we remove the data from our dataframe and recalculate the results to compare the data.

## Results

### After we removed the 9th Grade data we determined the following changes to the analysis:

* District Summary - Slight drop in all passing percentage at or less than 0.5%

* School Summary - Slight increase in math by less than 0.1% and slight drop in others by 0.1%

* School Standing - Still second place with a max change of 0.3%

* Detailed stats:
* Math & Reading by grade - all 9th Grade data removed, same scores for other Grades.
* Scores by school spending - the "$630-644" range looks exactly the same after formating since all data was less than 1% in change
* Scores by school size - Since the overall change was less than 0.1% again we have no change once data is formatted
* Scores by school type - The change for charter schools is 0.04%, so small that when formatted we see no change

## Summary

### We needed to remove all of the grades for 9th Graders at Thomas High. To do this we used a new method called the ".loc" method. With this, we could locate specific data within a data frame and make specific changes.

### The changes we noticed in all of the data was incredibly small, almost insignificant. Even removing grades had practically no change once formatted. When we look deeper we see that the highest percentage change was for the District summary and was less than 0.5%
