# Kickstarting with Excel

## Overview of Project

A fictional playwright, Louise, is using a crowd funding campaign to fund her play "Fever".  She would like to analyze crowd funding data for different campaigns to understand how launch dates and funding goals impact their success.

### Purpose

This exercise works with sorting, charting and analyzing crowd funding data in Excel in order to visualize factors (launch date and funding goals) that contribute to a successful or unsuccessful crowd funding campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

By using a pivot table to filter campaigns by both years and parent category, we can see trends for successful, failed, or canceled campaigns with launch dates at different times of the year. The following chart shows counts of campaigns for years 2009 to 2017 that have parent category "Theater".

![Theater Outcomes vs Launch](/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

Using Excels COUNTIFS() function we can understand how various ranges in funding goals correlate to the success of the campaigns. The following chart shows percentages for subcategory "Plays".

![Outcomes vs Goals](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Overall the exercise was easy to follow. There were a few minor challenges converting deadline and launched at fields to a date format.

Category and and Subcategory had to be broken out into separate columns in order to perform more granular analysis.

## Results

Campaigns with category "Theater", across years 2009 to 2017, are most successful if they launch in the May to June time frame. Theater campaigns are twice as likely to succeed at this time.  December is the least successful time of year to launch, with a roughly 50% success rate. The number of canceled theater campaigns are mostly consistent through the year with a slight uptick for launches in January.


- What can you conclude about the Outcomes based on Goals?

The results of the Outcomes based on Goals analysis shows that campaigns for plays with lower fund raising goals are more successful than campaigns with higher fund raising goals.  

- What are some limitations of this dataset?

Some limitations in this dataset include, the lack of more recent data.  The most recent year is 2017. The number of campaigns can be larger to give a better representation.  Special characters did not properly convert when the file was created. 


- What are some other possible tables and/or graphs that we could create?
Outcomes based on goals doesn't account for currency (USD, EUR, MXN, etc).  5000 in USD is not the same as 5000 in GBP, or especially MXN. Further filtering and sorting by Currency or Country can help make this distinction clearer.

The line chart used for Outcomes based on goals doesn't account for the increased volume of plays that fall within the lower goals ranges and the outliers in the upper goal ranges.  A bar chart may give a more accurate representation of percentages.

Theater outcomes based on launch date could be filtered further by country. Charts that make comparisons to other parent categories may give a good reference as well.

Additionally a box and whisker plot can show mean, upper and lower quartiles and IQR so that we can remove outliers that do not give a good representation of the data.

