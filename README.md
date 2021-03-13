# An Analysis of Kickstarter Campaigns

## Overview of Project
#### By studying a large amount of compiled data, we've been able to analyze trends and compare the outcomes of many Kickstarter fundraising campaigns.  The focus of this analysis is on the subcategory of ***Plays***, and the gathered data has been filtered to provide insights according to both *campaign launch date* and *fundraising goals*. 

#### This valuable information helps organizers understand how they might better organize their fundraising campaign.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
By analyzing outcomes of campaigns based on their launch date we can begin to target success.  In order to do this, a pivot table was created in which all Kickstarter campaigns were filtered to the category of ***Theater***, and for **all years** within the overall data set.  Shown below is a chart detailing the outcome of that table.

![Theater_Outcomes_vs_Launch.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
By analyzing outcomes of campaigns based on their fundraising goal we can further leverage the data toward a successful effort.  This was achieved by creating a table and using a ***CountIfs*** function to sum the results of each campaign in the ***Play*** subcategory according to both; the established **goal ranges** *(shown below on the "x" axis and represented by dollar amounts)*, and various **outcomes** *(successful, failed, or canceled)*.  By doing so, we can quickly visualize the result.  Below is a chart showing the percentage, by campaign **outcome**, of the total number of campaigns within each defined **goal range**.

![Outcomes_vs_Goals.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
One challenge that was encountered during this analysis was the discovery of a potential hole in the reported results due to the specified data requested.  In the prompt for Deliverable 2 (Item 3), campaigns with goals of exactly $50,000 aren't represented by the table.  Because of this, if a formula is created according to that request, it would exclude results for campaigns with goals of exactly $50,000.  Consequently, this would result in the omission of data for 4 plays.  Although this doesn't have a major impact on the overall results of this analysis due to the limited number of excluded campaigns, it should be noted that all values within the range being analyzed should be included for accurate reporting.  

This was overcome by simply modifying the ***CountIfs*** function to include those potentially omitted results with a *"greater than or equal to"* formula instead of just a *"greater than"* formula.  By doing so we ensured that all data gathered in the study was included in the analysis.  Below are two images.  One is of the table that is exclusive of the $50,000 value, and one is of the table that is inclusive of the $50,000 value.  The inclusive table is that which was used for this analysis.

![Goal_ranges_original_table.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Goal_ranges_original_table.png)

![Goal_ranges_modified_table.png](https://github.com/frostbrosracing/kickstarter-analysis/blob/main/Resources/Goal_ranges_modified_table.png)


## Results

#### Two conclusions drawn by comparing fundraising campaign ***outcomes with the launched date*** are listed below.
- Theater campaigns initiated in the months of May and June were considerably more successful than those campaigns initiated in other months.
- Perhaps due to potential contributions being limited by holiday season spending, December campaigns resulted in the fewest successes. 

#### According to the data gathered by comparing fundraising ***outcomes based on their goals*** we can also determine the following:
- The percentage of successful campaigns steadily decreases from 76% for campaigns with goals less than $1,000, to 20% for campaigns with goals in the $25,000 to $29,999 range.  The total number of campaigns represented in this overall goal range (less than $1,000 to $29,999) is 1010.
- Campaigns achieved the highest overall success rate with goals of $1,000 to $4,999.  Of 534 campaigns in this group, 388 met their fundraising goal.  This appears to be the ideal goal range of a successful kickstarter campaign for the subcategory of ***play***.
- The percentage of successful campaigns with goals of between $30,000 and $44,999 increases for just 20 campaigns.  These campaigns could be interpreted as outliers due to extenuating circumstances, and further investigation into those successful campaigns might be appropriate.
- Of the 17 total projects with goals of $45,000 and higher, only 2 were successful.


- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?








