# Kickstarting with Excel

## Overview of Project
This project tested the Excel analysis skills learned in this week's module to provide different visuals of how outcomes of different kickstarters based on their Launch Dates and Goals
### Purpose
The purpose of this project is to show Louise how her kickstart fared against others based on their funding goals, their launch date, and whether or not they were successful, failed, or cancelled
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I created a pivot table based on the kickstarter challenge dataset, set the rows to months, the columns to outcomes, filtered out the data based on Parent Category(theater) and year, and the values were the count of each outcome. After, I used the pivot table to create a line graph to show the trend in theater outcomes based on launch dates.
### Analysis of Outcomes Based on Goals
After setting up the proper headers for the rows and columns, I used many variations of the COUNTIF function in Excel to count the number of successful, failed, and cancelled kickstarters in their respective column and in the range of their funding goal.  I also applied filters in the kickstarter challenge dataset in the outcome and subcategory columns to make sure I am looking at the correct outcome for all play kickstarters.  Next, I calculated  the sum of total projects for each funding goal range. I then calculated the percentage of each outcome based on their respective funding goal range. Once the chart was completed, I created a line chart to show the trend in the percentage of outcomes based on their funding goal.
### Challenges and Difficulties Encountered
One challenge I faced is modifying the COUNTIF function based on what funding goal and outcome I was working with. I also had difficulties figuring out which pivotchart field to drag in which area and which filters to apply to make sure I got the correct outcome.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion I can draw about the Outcomes based on Launch Date is that theater kickstarters were most successful when they launched in May. Another conclusion is that the amount of successful kickstarters tend to decrease towards the end of the year. 
- What can you conclude about the Outcomes based on Goals?
It seems that the higher percentage of failed outcomes are when the funding goal is less than 1000 or more than 50000
- What are some limitations of this dataset?
There were not any  cancelled play kickstarters that I believe is a limitation of this dataset.
- What are some other possible tables and/or graphs that we could create?
We could have created a stacked column graph to show percentage of successful, failed, and canceled outcomes compared to the different ranges of funding goals.