# An Analysis of Kickstarter Campaigns

## Overview of Project
#### By studying a wide range of Kickstarter campaigns we've been able to analyze trends related to: fundraising goals; campaign starting dates and duration; and finally, the outcomes of campaigns similar to that of Louise's play, "Fever".  

### Purpose
#### The purpose of this is to understand how Louise might have positioned her fundraising campaign for a greater level of success.


## Analysis and Challenges
### One challenge that appeared within this analysis was the discovery of a hole in the data requested based on the ranges established.  As you can see below the request was made for campaigns according to various goal ranges.  Based on the captured image of the request below you can see that campaigns with goals of exactly $50,000 aren't represented by  the table.  Because of this, if a formula is created according to that request it is exclusive of that $50,000 value and the table doesn't capture a total of 4 plays.  Although this doesn't have a major impact on the results of the data due to the limited number of excluded campaigns, it should be noted that all values within the range being analyzed should be included for accurate reporting.

![Goal_ranges.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Goal_ranges.png)
![Goal_ranges_original_table.png](github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Goal_ranges_original_table.png)
![Goal_ranges_modified_table.png](github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Goal_ranges_modified_table.png)


### Analysis of Outcomes Based on Launch Date
#### Two conclusions drawn by comparing fundraising campaign outcomes with the date they were launched:
1.  Theater campaigns initiated in the months of May and June are considerably more successful than those campaigns initiated in other months.
2.  December campaings resulted in the fewest successes.  Perhaps due to potential contributors adjusting their spending for the holiday season, this month had the fewest successful campaigns of the years in the analysis.


![Theater_Outcomes_vs_Launch.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
#### Below you can see an analysis of fundraising campaign outcomes based on the fundraising goals that were set.
#### By creating a table and a CountIf function to sum the results of each campaign in the "play" subcategory according to the set goal ranges we can see that:
1. The percentage of successful campaigns steadily decreases from 76% for campaigns with goals less than $1,000 to 20% for campaigns with goals in the $25,000 to $29,999 range.  The total number of campaigns represented in this overall goal range (less than $1,000 to $29,999) is 1010.
2. Campaigns achieved the highest success rate with goals of $1,000 to $4,999.  Of 534 campaigns in this group, 388 met their fundraising goal.  By analyzing "play" campaign outcomes we see that this might be the ideal range for a campaign goal.
3. The percentage of successful campaigns with goals of between $30,000 and $44,999 increases for just 20 campaigns.  These could be interpreted as outliers due to extenuating campaign circumstances and further investigation into those successful campaigns might be appropriate.
4. Of the 17 total projects with goals of $45,000 and higher, only 2 were successful.  
![Outcomes_vs_Goals.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?








