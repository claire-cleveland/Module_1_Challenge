# Kickstarting with Excel

## Overview of Project

The client, Louise, is funding a play called Fever. As part of market research, she wanted to know how different campaigns fared in relation to their launch dates and funding goals.

### Purpose

To use Kickstarter data to better understand how launch dates and goals impact the success rate of a campaign.

## Analysis and Challenges

I used the expanded Kickstarter data that was modified to include subcategories as well as converted dates and a years column. I then analyzed the data using pivot tables and line charts. 

To analyze the outcomes based on launch date, I used a PivotTable that filtered the data by tear and then parent category "theater." From there, I filtered the table to contain only "successful," "canceled," and "failed." The resulting line chart was named "Theater Outcomes Based on Launch Date." 

#Challenges in Analyzing Outcomes Based on Launch Date

I encountered challenges in this part of the analysis because my data on the Kickstarter sheet still had filters on it from the earlier exercises. Once I removed the filters in that sheet, then the PivotTable and resulting line chart matched what the assignment called for. 

To analyze the outcomes based on goals, I created a table in a new sheet that had 12 rows and 8 columns. The rows were split into categories to organize the goal amounts in $5,000 increments. The columns broke up the projects into "successful," "canceled," and "failed" counts, then a sum of the projects, and then the percentage of each category of the total projects. I used the =COUNTIFS formula to count from the Kickstarter sheet if the goal, type (Number successful, for example) and subcategory "plays" was met. Then the =SUM function and =B2/E2*100 division formula was used to calculate the percentage. Finally, I created a line chart with percentage on the Y access and goal amount on the x-axis. The three lines of the chart represented the "Percentage Successful," "Percentage Failed," and "Percentage Canceled."

#Challenges in Analyzing Outcomes Based on Goal

My line chart for this section does not look like the provided line chart. This was my biggest challenge in this section of the analysis. I have not identified what the issue is. I made sure that the Kickstarter sheet was not filtered in a way that would impact my analysis. I must have made an error somewhere in the coursework, but I don't know where and did not have time to repeat the coursework before the submission deadline. 


### Analysis of Outcomes Based on Launch Date

Theater outcomes are most successful in May. There appears to be a spike in October of failed campaigns and successful and failed campaigns are about equal in December, based on the data analysis. This means that if Louise is looking for a good launch date, she should consider May or even June or July, which also have higher numbers of successful campaigns. Canceled campaigns are pretty consistent throughout the year and are likely related to factors other than timing. 

### Analysis of Outcomes Based on Goals

Theater campaigns that have lower goal amounts are more successful than those with higher goal amounts. However, my data in this section is problematic, therefore my conclusions are off. If I look at the example line graph, then campaigns under $20,000 are more likely to be successful then to fail, which is also true of the $35,000 to $45,000. Campaigns over $45,000 are much more likely to fail. 

### Challenges and Difficulties Encountered

Analyzing a limited Kickstarted dataset is a good starting point for understanding trends in time or goal amounts that may affect the outcomes of a campaign for a theater or play project, but more data on other potential compounding factors would benefit the analysis. For example, while more campaigns may be successful in May, that's also the month when there're the most campaigns launched. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Outcomes are better, more successful, in May. December is not a good month for starting a campaign. 

- What can you conclude about the Outcomes based on Goals?

Campaigns are more successful if the goal is less than $5,000 or between $35,000 and $45,000. 

- What are some limitations of this dataset?

This dataset is only from Kickstarter which does not account for projects that raise funds on different platforms or in different ways. This dataset is rather basic in including only names, blurbs, goals and launch dates. There is consumer trends data about why and how people contribute to Kickstarters that could also be used for better analysis, for example. Additionally, the dataset is small. 

- What are some other possible tables and/or graphs that we could create?

We could create a table that considers both the launch date and deadline to better understand when campaigns are successful based on when they open and close. We could also analyze the data in different countries or with different currency to see if the currency impacts the success rate. 