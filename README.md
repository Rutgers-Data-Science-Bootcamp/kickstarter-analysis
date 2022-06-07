# Kickstarting with Excel

## Overview of Project
Performing analysis on kickstarter data to help Louise 
### Purpose
Try to uncover hidden trends in the dataset to see how successful were her compaigns so far   
## Analysis and Challenges
Using pivot table to chart theater outcomes beased on the launch date and Goals. 
### Analysis of Outcomes Based on Launch Date
This analysis has been done by following steps:
1. In the Kickstarter_Challenge.xlsx workbook, I have created a new column labeled "Years."
2. In the "Years" column, extracted the year from the “Date Created Conversion” column by using   the YEAR() function.
3. Created a pivot table from the KickStarter worksheet, and place the pivot table in a new sheet.
4. Labeled the sheet "Theater Outcomes by Launch Date."
5. Filtered the pivot table based on "Parent Category" and "Years."
6. Filtered the column labels to show only "successful," "failed," and "canceled."
7. the pivot tables looks like in this screenshot below:
![Screen Shot 2022-06-06 at 11 42 38 PM](https://user-images.githubusercontent.com/65901034/172291206-a0d65fb8-2d3f-4cfa-ac3c-9e502febc773.png)
8. Filtered the "Parent Category" to show only the data for "theater."
9. Created a line chart from the pivot table to visualize the relationship between outcomes and launch month as below:
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/65901034/172291462-3109c0c2-bb34-48eb-bb18-80a2f3010657.png)

### Analysis of Outcomes Based on Goals
In order to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount, i did follwoing steps:
1. In the KickStarter sheet, created a new sheet and label it "Outcomes Based on Goals."
2. In the new sheet, created the columns to hold the data and used CCOUNTIF function to populate  the "Number Successful," "Number Failed," and "Number Canceled" columns for the plays as you see in the screenshot below:
![Screen Shot 2022-06-06 at 11 51 07 PM](https://user-images.githubusercontent.com/65901034/172292134-bb2e5c65-d33e-4e5a-90a0-e68f58aff315.png)
3. Calculated the percentage of successful, failed, and canceled projects for each row.
4. Created a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. The line chart as below:
![Outcome_vs_Goal](https://user-images.githubusercontent.com/65901034/172292350-00acbf8b-cf83-41c1-b375-31b5f4a89eff.png)
### Challenges and Difficulties Encountered
There wasn't a big challenges for me during this analysis. Only problem i have encountered was with the COUNTIFS fuction and fill the conditions inside the conditions. 
## Results
- There is two conclusions i can draw from the Outcomes based on the launched date chart:
   1. Overall, number of successful theatre compagn is higher than failed or cancelled.The Trend of success and failed number during the year is the same. 
   2. During the year, from April to August, successful theater compains have increased and reached the peack on May.  

  - What I can draw as conclusion from the Outcomes based on Goals is while the range of dollar amount of goal increased the percentage of fail increased. However, 35000-45000 gola range, the compaign have better success rate. 
- Limitations in this dataset, 
   1. there is missing data point for theater cancelled compaigns in october bur based on the trend in line chart, it looks does not matter. 
   2. There is few number of compagns for bigger dollar range of goals and the percentage is so sensitive with the outcome. 
- I would have created historgrams with the theater compian success, failed, cancelled through out the year. 
- I would have created bar grapgh to compare overall success and failed rate with play compaign regardless of the goal range. 
