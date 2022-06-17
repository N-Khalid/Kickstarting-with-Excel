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

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103234661/174200265-1ba03fd7-b6cc-45f3-a81b-0fdde43f27fa.png)

2. Next I created a table of the outcomes of the 'plays' subcatergory based on the goal.
 - Using the COUNTIFS function, I determined the number of 'plays' campaigns that were successful, failed and canceled within various goal ranges.
 - Next I used used the SUM function to determine the total kickstart projects within certain goal ranges. 
 - I found what percent of campaigns were successful, failed and were canceled based on the goal range.
 - I completed this analysis by using a line graph to help visualize the outcomes of the 'plays' subcatergory based on the goal. 
 
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103234661/174201055-bfc20331-97bc-4335-a0d7-f9f96c4b714e.png)

There were two challenges performing this analysis:
 1. Deciding which fields I wanted to add to my PivotTable to help portray the outcomes of the 'theater' category based on launch date. I overcame this challenge taking a step back to decide how I would create a similar table without the use of PivotTables and walked myself through each step in my head.

 2. Fixing the errors on the calculated percentage when dividing by 0 and to have the '%' sign show next to the values. I overcame this challenge by using the IFERROR function and changing the values from 'General' to 'Percentage'

### Analysis of Outcomes Based on Launch Date

What are two conclusions you can draw about the Theater Outcomes by Launch Date

### Analysis of Outcomes Based on Goals

What can you conclude about the Outcomes based on Goals?

### Challenges and Difficulties Encountered

What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create?

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
