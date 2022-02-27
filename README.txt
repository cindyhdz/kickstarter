# Fundraising Analysis

Analysis of fundraising outcomes based on the date of launch and fundraising goals for two categories, --theatre and plays. 

## Methods
 
*To analyze theatre fundraising outcomes a pivot table was created based on launch date and outcomes—successful, failed and canceled. 

countryUSCount of outcomesColumn LabelsRow LabelscanceledfailedlivesuccessfulGrand Totaltheater2634912525912Grand Total2634912525912

*Using data from the pivot table, a line chart named “Theatre Outcomes vs, Launch” was created to visually portray the relationship between outcomes and launch month. 



*To analyze outcomes for plays based on fundraising goals, raw data filtered by plays was used and placed in new worksheet. In the new worksheet, the following items were added across columns, goal, number successful, number failed, number canceled, total projects, percentage successful, percentage failed, and percentage canceled. Additionally, in the “goal” column, the following dollar amount ranges were used to group based on their goal amount.
       


*The COUNTIFS() function was used to populate the "number successful, "number failed," and "number canceled" columns based on the "goal" amount column in the plays worksheet and using the ranges created. 
*The SUM() function was used to populate the "Total Projects" column with the number of successful, failed, and canceled projects for each row.
*The percentage of successful, failed, and canceled projects for each row was then calculated.
*A line chart was created and named "Outcomes Based on Goal" to visualize the relationship between the goal amount ranges and the percentage of successful, failed, or canceled projects.

##Conclusions
The following will address trends and correlations presented in the data analysis.
*Based on launch date, successful and failed theatre productions occurred at higher rates between the months of June to August. Therefore, there is no correlation found between time and success in obtaining pledged amounts. 
*There was a consistency of successful and failed pledges throughout the year.
*Based on outcome goals (successful, failed and canceled), plays that were more successful in collecting pledge amounts resulted from pledges in the amount of $1000 and below. This accounted for a 90% success rate—for pledges in the amount of $1000 and below. The higher the pledge amount, the lower the percentage of successful pledges. 
*Another point of interest that was not explored in this analysis, would be to analyze of the plays that failed to meet their pledges—by how much. How close did they come to meet the goal and what amounts were close to meeting the goal. This could be displayed as a table. 
*Success in this dataset is defined as pledges met, however there are other financial factors that can be accounted for in terms of success like percentage attended and sales from tickets.  

