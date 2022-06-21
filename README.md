# surfs_up
## Overview 

On a vacation in Hawaii,last year I discovered a new passion for surfing.This passion for surfing come with a new bussiness plan for opening a surf n' shake shop in Hawaii.The bussiness concept is a combination of surf board and ice cream shop for locals and tourists.After reaching with a strong investment plan,i need funds from W. Avy,who is known for his love of surfing.W. Avy,wants some more insights into the weather patterns,temperature on Oahu island to prove the feasibility and potentiality of the plan.W. Avy have the data on temparature and precipitation of the island of Oahu that he wants me to analyze and present the findings.

## Data Source

-Data Source: hawaii.sqlite database
-Query Tool: SQLAlchemy

-Softwares:
-Python 3.9.7, 
-Jupyter Notebook, 
-VSCode

## Purpose

The main purpose of this analysis to create a statistical analysis of the temperatures on Oahu island for the months of June and December,by using Python, Pandas functions and methods, and SQLAlchemy.Using the hawaii.sqlite database,we are able to find the min,max,avg temperatures for both months.

## Results

Using Python, Pandas functions and methods, and SQLAlchemy, we filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Then we convert this temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Key differences:

-There are 1,700 counts for the month of June and 1,517 counts for the month of December.The mean temperature for both of the months are within 70° F.June month is slightly warmer with 75° F than the month of december which is rounded to 71° F.

![](https://github.com/akthersr/surfs_up/blob/main/june%20temps.png)  ![](https://github.com/akthersr/surfs_up/blob/main/december%20temps.png)

-From the above table, we can determine that maximum temperature for December is 83° F and for June is 85° F.Although the max temperature are within the same range,but min temperature for December can go as low as 56° F.The minimum temperature for month June is 64° F.

-Low standerd deviation for both months tells us that Oahu weather does not change much over peroid.The maximum temperature for both months are not excessive either,but June has consistent warmer weather than December.

## Summary

Both months June and December has relatively favourable temperature for surfing conditions and a steady demand of ice cream.


