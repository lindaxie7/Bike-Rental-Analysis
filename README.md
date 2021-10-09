# NYC-CitiBike-Analysis

Overview of Project
We have an excel spreadsheet with 14 columns and 4115 rows of campaign fundraising data, some of the columns contain text while other columns contain numbers. The Goal column tells us how much money each campaign will need to succeed. The Pledged column tells us how much each campaign actually made. The Outcomes column tells us if the campaign met its goal. The Country column lists the country in which the campaign was started. Since theater is a popular and successful type of campaign overall. I created a pivot table "Theater Outcomes by Launch Date" to filter the data by Parent category and Years, this gives us the summary of how many successful, failed, canceled campains on theater plays in each month. I created a line chart from the pivot table to visualize the relationship between outcomes and launch month. I also created a table "Outcomes Based on Goals" gives us the cumulative numbers of successful, failed, canceled campaigns based on the goals. I created a line chart to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount.

Purpose
We are performing data analysis on several thousand crowdfuding projects to uncover any hidden trends, to provide information to help Louise plan her campaign.

Analysis and Challenges
I created a pivot table "Theater Outcomes by Launch Date" to filter the data by Parent category and Years. I also created a table "Outcomes Based on Goals" gives us the cumulative numbers of successful, failed, canceled campaigns based on the goals.

Analysis of Outcomes Based on Launch Date
I find that the month that launched the most successful theater campaigns was May. However, January, June, July and October all had roughly the same number of failed campaigns launched. June seems to be a good month to launch a campaign! Theater_Outcomes_vs_Launch

Analysis of Outcomes Based on Goals
I find that failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns. $25000 to $30000 fundraising goal is the point where the failed campaigns reached to the peak and the successful campaigns starts to raising. And when the fundrasing goal reach to $45000 to $50000, the successful campaign goes to the lowest point. So the $30000 fundraising goal seems a good goal to start a campaign, and the $45000 fundraising goal seems a good goal to end the campaign. Outcomes_vs_Goals

Challenges and Difficulties Encountered
The outcomes based on goals was a bit challenge for me, to understand the filtering requriement clearly and use the countifs function to get the cumulative information based on goals.

Results
What are two conclusions you can draw about the Outcomes based on Launch Date?
I find that the month that launched the most successful theater campaigns was May. January, June, July and October all had roughly the same number of failed campaigns launched.

What can you conclude about the Outcomes based on Goals?
The $30000 fundraising goal seems a good goal to start a campaign. The $45000 fundraising goal seems a good goal to end the campaign.

What are some limitations of this dataset?
We have limited data information included in the Kickstarter spreadsheet, including more data will make our analysis even more detailed and thus generate additional insight.

What are some other possible tables and/or graphs that we could create?
We could create outcomes based on pledged, We could also create theater outcomes by country, category outcomes by Years.


