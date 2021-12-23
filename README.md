# Kickstarting with Excel

## Overview of Project

A fictional playwright, Louise, is using a crowd funding campaign to fund her play "Fever".  She would like to analyze crowd funding data for different campaigns to understand how launch dates and funding goals impact their success.

### Purpose

This exercise works on sorting, charting and analyzing crowd funding data in Excel in order to visualize factors (launch date and funding goals) that contribute to a successful or unsuccessful crowd funding campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

By using a pivot table to filter campaigns by both years and parent category "Theater", we can see in a line chart trends for successful, failed, or canceled campaigns with launch dates at different times of the year.

![Theater Outcomes vs Launch](/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

Using Excels COUNTIFS() function we can understand how various ranges in funding goals correlate to the success of the campaigns. Filtered to campaigns with subcategory "Plays".

![Outcomes vs Goals](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

## Results

Campaigns with category "Theater", across years 2009 to 2017, are most successful with launch dates in the May to June time frame. Campaigns are twice as likely to succeed at this time.  December is the least successful time of year to launch, with a roughly 50% success rate. The number of canceled theater campaigns are mostly consistent through the year with a slight uptick for launches in January.


- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
