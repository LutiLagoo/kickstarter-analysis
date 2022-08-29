# Kickstarting with Excel

## Overview of Project
Client wants to compare her fundraising results against other similar campaigns based on their launch dates and funding goals. Her fundraising campaign was for a play she would like to produce.
### Purpose
Our analysis will help the client identify how effective her campaign was and what factors correlate with successful, failed, and canceled outcomes. 
## Analysis and Challenges
### Dataset Setup
Since the client’s fundraising campaign is for a play, our analysis begins with only looking at the Theater parent category and Plays subcategory. This will filter the dataset to show the best comparable campaigns.
image
### Analysis of Outcomes Based on Launch Date
#### Theater Outcomes Based on Launch Date
image
Pivot Chart was created and organized in a way that we could see the launch dates by month, outcome, and totals of outcomes. This way we could have a PivotTable to see the results while also being able to create a line chart.
#### Line Chart
image
Line chart was created with the PivotChart tool so we can visualize the data from the PivotTable. In this format, we can see how the successful, failed, and cancelled outcomes correlate with the launch date months.
### Analysis of Outcomes Based on Goals
#### Table
image
A table was created manually so we could see the number of successful, failed, and cancelled outcomes based on their goals. Table was organized with ranges of goal amounts. The subtotal of each range of goal amount outcomes was then used to identify the percentage rate for each outcome.
#### Line Chart
image
From the table, we were able to create a line graph to look for patterns. The patterns that were discovered were clear enough to make out trends for successful and failed outcomes. There were no cancelled outcomes for plays.
### Challenges and Difficulties Encountered
When making the Outcomes Based on Goal table, I made a formula error that prevented Excel from including all the outcome results within a range. It took two hours to figure out that I was missing an “=” when writing out the criteria for the ranges. 
## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?

First conclusion, the most successful fundraising campaigns are launched in May, but the number of successful outcomes begin a downtrend from June to the end of the year. Also, from March to May, the number of successful outcomes gradually increase. This can mean there could be events starting in March that increase successful outcomes until the effectiveness peaks in May.

Second conclusion, the number of failed outcomes stay consistent throughout the year. This can indicate that there are common factors of how a campaign was launched instead of when a campaign was launched. An example would be that there is a stronger correlation between campaign goals and failed outcomes then the correlation between launch dates.
### What can you conclude about the Outcomes based on Goals?

The higher the campaign goal, the more likely the campaign is to fail. The most successful percentage rates were for campaigns with goals under $5,000, then a sharp decrease and gradual decline begins when analyzing campaigns with goals above $5,000.
### What are some limitations of this dataset?
Some limitations include the lack of information on who runs the campaign and the lack of recent data in the 2020s. This is a major gap as COVID might have significantly influenced the outcomes for these campaigns.
### What are some other possible tables and/or graphs that we could create?
A great table would be to track the length of the campaigns, what month they were launched, the goal amount, and the outcome. This way we could identify if there is correlation between the launch month, length of campaign, and goal amount. We could find major factors that determine outcomes by how we 