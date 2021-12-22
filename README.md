{\rtf1\ansi\ansicpg1252\cocoartf2580
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww16600\viewh7140\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Kickstarting with Excel\
\
## Overview of Project\
\
A fictional playwright, Louise, is using a crowd funding campaign to fund her play "Fever".  She would like to analyze crowd funding data for different campaigns to understand how launch dates and funding goals impacted their success.\
\
### Purpose\
\
This exercise works on sorting, charting and analyzing crowd funding data in Excel in order to visualize factors (launch date and funding goals) that contribute to a successful or unsuccessful crowd funding campaign.\
\
## Analysis and Challenges\
\
### Analysis of Outcomes Based on Launch Date\
\
By using a pivot table to filter campaigns by both years and parent category "Theater", we can see trends for successful, failed, or canceled campaigns with launch dates at different times of the year.\
\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0
\cf0 https://github.com/NinaQuik/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\
### Analysis of Outcomes Based on Goals\
\
Using Excels COUNTIFS() function we can understand how various ranges in funding goals correlate to the success of the campaigns with subcategory "Plays".\
\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0
\cf0 https://github.com/NinaQuik/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
### Challenges and Difficulties Encountered\
\
## Results\
\
Campaigns for category "Theater", across all years 2009 to 2017, have the highest count of success with launch dates in the May to June time frame. Campaigns are twice as likely to succeed at this time.  December is the least successful time of year to launch, with a roughly 50% success rate. The number of canceled theater campaigns are mostly consistent through the year with a slight uptick with launches in January.\
\
\
- What can you conclude about the Outcomes based on Goals?\
\
- What are some limitations of this dataset?\
\
- What are some other possible tables and/or graphs that we could create?\
}