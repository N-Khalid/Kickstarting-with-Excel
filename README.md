# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis is to determine the results of different Kickstart campaigns in relation to their launch dates and what their funding goals were set at. 

## Analysis and Challenges

1. I began my analysis by creating a pivot table using the Kickstarter data to find the outcomes of the 'theater' category based on launch date. The pivot table was set up as followed:
 - Filter 'categories' and 'years'
 - Place 'outcomes' in the columns container and also placing it in the values container
 - Place 'Date Created Conversion' in the rows container

Using PivotTable Analyze, I inserted a line graph to help visualize data based on the 'theater' category. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103234661/174417731-dd6b8f00-b8e5-4190-aff0-e7a43b1bdb1b.png)

2. Next I created a table of the outcomes of the 'plays' subcatergory based on the goal.
 - Using the COUNTIFS function, I determined the number of 'plays' campaigns that were successful, failed and canceled within various goal ranges.
 - Next I used used the SUM function to determine the total kickstart projects within certain goal ranges. 
 - I found what percent of campaigns were successful, failed and were canceled based on the goal range.
 - I completed this analysis by using a line graph to help visualize the outcomes of the 'plays' subcatergory based on the goal. 
 
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103234661/174417617-46d9dfac-eb05-4b7d-be50-2f664b466a81.png)

There were two challenges performing this analysis:
 1. Deciding which fields I wanted to add to my PivotTable to help portray the outcomes of the 'theater' category based on launch date. I overcame this challenge taking a step back to decide how I would create a similar table without the use of PivotTables and walked myself through each step in my head.

 2. Fixing the errors on the calculated percentage when dividing by 0 and to have the '%' sign show next to the values. I overcame this challenge by using the IFERROR function and changing the values from 'General' to 'Percentage'

### Analysis of Outcomes Based on Launch Date

1. The best time to start a theater-based Kickstarter campaign would be May due to the rate of success versus all other months

2. As a whole, the theater category of campaigns have a steady failure rate. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103234661/174417734-7a5e41cf-a335-4abb-ae85-f9918468e99a.png)

### Analysis of Outcomes Based on Goals

When the goal is relatively small (under $4,999), more campaigns are created and of those created campagins, more are successful.  

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103234661/174417623-7ff925ef-a569-4752-a168-04c8aee583b1.png)

### Challenges and Difficulties Encountered

**What are some limitations of this dataset?**

Two limitations of this dataset are the timeframe the data was collected and the amount of platform's used in this dataset.

1. As Kickstarter gains or loses more traction as a platform, data that is current would provide a far larger sample size. The last recorded ending date ends in 2017. In the next 5 years, the platform's popularity may have attracted or dissuaded certain demographics which may skew the data of certain categories.

2. Kickstarter is one of many platforms where people can bring their projects to life with community support. GoFundMe or IndieGoGo are examples of other popular platforms similar to Kickstarter that take up a large marketshare. If we were to collect data from all of these platforms, we would be presented a much more accurate display of campaign success rates, funding amounts and category popularity.

**What are some other possible tables and/or graphs that we could create?**

Based on this data set, there are many useful tables and graphs that could be created such as a table with outcomes based on each country. It would be useful to know if countries that deal with harsher weather conditions would have a flatter line graph over the full year or if there may be other factors contributing to why the spring and summer months show more success. 
