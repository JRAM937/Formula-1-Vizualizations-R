Final Project: Formula 1 Visualizations
================
Adrian Ortiz, Juan Ramirez JR

## Introduction

For this project we are analyzing the Formula One data set from Tidy
Tuesday’s github. The data set contains information such as: formula one
drivers, constructors, race results, qualifying times, etc.  
Our two questions are:  
Question 1: Of the fastest drivers in Qualifying Round \#3, who has the
most wins in Abu Dhabi?  
Question 2: Which team had the most wins in the 2021 season?

## Graphic 1 - Of the fastest drivers in Qualifying Round \#3, who has the most wins in Abu Dhabi?

For this problem, we are trying to find out which of the fastest drivers
in Qualifying round \#3 had the most wins in a specific course: Abu
Dhabi. We chose Abu Dhabi because it is one of the more complex and
iconic circuits in F1, not to mention the final circuit in most F1
seasons.  
We take some data from the Q3 times for each driver. We decided to skip
Q1 and Q2 because we were ONLY interested in drivers who were fast
enough to survive the first two rounds of qualifying and move on the the
third and final round.  
We started by removing any values which were marked NULL which usually
indicate some sort of mechanical failure or other issue that took a
driver out of Q3. We then take a look at the number of total wins these
drivers had.

The end result is graphic for the fastest Q3 drivers compared by total
wins.

![](Final-Project-Template_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->
The fastest driver from Q3 with the most wins in Abu Dhabi is driverId
\#18, which is Jenson Button.

## Graphic 2 - Which team has the most all-time wins?

For this graphic, we wanted to see which F1 team currently has the most
wins all-time. In order to do this, we needed to look at the provided
“constructor\_standings” data set to determine who has the most wins.  
We did notice that there are some teams without wins, so we had to
remove those first before we could sort the data in order.  
The end result is a nice depiction of the top three teams in F1 to-date:
The top team is Mercedes, followed by Ferrari, and finally McLaren.

    Warning: One or more parsing issues, see `problems()` for details

![](Final-Project-Template_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->
