# An Analysis of Kickstarter Campaigns

## Overview of Project
#### By studying a wide range of Kickstarter campaigns we've been able to analyze trends related to: campaign starting dates and duration; fundraising goals; and finally, the outcomes of campaigns similar to that of Louise's play, "Fever".  

#### The purpose of this is to understand how Louise might have better positioned her fundraising campaign for a greater level of success.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
#### By analyzing outcomes of campaigns based on their launch date we can begin to target success.  Below is an analysis of fundraising campaign outcomes within the "Theater" category based on the campaign launch date.

##### For the purpose of this analysis, a pivot table was created in which all Kickstarter campaigns were filtered by the category of "Theater", and for all years being studied.  The total number of campaigns was charted according to the outcomes of "successful", "failed", and "cancelled" based on the date the campaign began.

![Theater_Outcomes_vs_Launch.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
#### By analyzing outcomes of campaigns based on their fundraising goal we can further leverage the data toward a successful effort.  Below is an analysis of fundraising campaign outcomes based on the fundraising goals that were originally set.
##### By creating a table and a CountIf function to sum the results of each campaign in the "play" subcategory according to the set goal ranges we can draw the following conclusions.
1. The percentage of successful campaigns steadily decreases from 76% for campaigns with goals less than $1,000, to 20% for campaigns with goals in the $25,000 to $29,999 range.  The total number of campaigns represented in this overall goal range (less than $1,000 to $29,999) is 1010.
2. Campaigns achieved the highest overall success rate with goals of $1,000 to $4,999.  Of 534 campaigns in this group, 388 met their fundraising goal.  This appears to be the ideal goal range of a successful kickstarter campaign for the subcategory of "play".
3. The percentage of successful campaigns with goals of between $30,000 and $44,999 increases for just 20 campaigns.  These campaigns could be interpreted as outliers due to extenuating circumstances, and further investigation into those successful campaigns might be appropriate.
4. Of the 17 total projects with goals of $45,000 and higher, only 2 were successful.

![Outcomes_vs_Goals.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
##### One challenge that appeared within this analysis was the discovery of a hole in the data due to the requested fundraising goal ranges.  In the prompt for Deliverable 2 (Item 3), campaigns with goals of exactly $50,000 aren't represented by the table.  Because of this, if a formula is created according to that request, it is exclusive of that $50,000 value resulting in the omission of data for 4 plays.  Although this doesn't have a major impact on the overall results of the analysis due to the limited number of excluded campaigns, it should be noted that all values within the range being analyzed should be included for accurate reporting.

![Goal_ranges_original_table.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Goal_ranges_original_table.png)
![Goal_ranges_modified_table.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Goal_ranges_modified_table.png)


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Two conclusions drawn by comparing fundraising campaign outcomes with the date they were launched are listed below.
1.  Theater campaigns initiated in the months of May and June were considerably more successful than those campaigns initiated in other months.
2.  December campaings resulted in the fewest successes.  Perhaps due to potential contributions being limited by holiday season spending, this month had the fewest successful campaigns of the years studied in the analysis.


- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?








