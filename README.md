# An Analysis of Kickstarter Campaigns
# Overview
An excel data analysis of fundraising outcomes based on the date of launch and fundraising goals for two categories, theatre and plays. 

## Analysis and Challenges 
 
To analyze theatre fundraising outcomes a pivot table was created based on launch date and outcomes—successful, failed and canceled. 
Using data from the pivot table, a line chart named “Theatre Outcomes vs Launch” was created to visually portray the relationship between outcomes and launch month. 

To analyze outcomes for plays based on fundraising goals, raw data filtered by plays.The COUNTIFS() function was used to populate the "number successful, "number failed," and "number canceled" columns based on the "goal" amount column in the plays worksheet and using the ranges created. The SUM() function was used to populate the "Total Projects" column with the number of successful, failed, and canceled projects for each row. The percentage of successful, failed, and canceled projects for each row was then calculated.

A line chart was created and named "Outcomes Based on Goal" to visualize the relationship between the goal amount ranges and the percentage of successful, failed, or canceled projects.

### Challenges
There was some limitations in relation to deviations. This was not accounted for in the analysis, which can skew the data. 

## Results

May and June both have a greater success rate, which is helpful to know fow future fundraising efforts. 
![image](https://user-images.githubusercontent.com/99698846/169663227-6a912249-39a6-40b2-9f5c-f3ff4bfc853d.png)

Some of the most successful plays were funded at lower amounts than least successful. 
![image](https://user-images.githubusercontent.com/99698846/169663244-b172dad6-f0a9-462f-be5f-c9c515c44a96.png)

