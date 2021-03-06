Kickstarting with Excel

Overview of Project

Purpose

The purpose of the project is to examine the relation between theater campaign outcomes and their launch dates; and play campaigns and their funding goals using Kickstarter data and provide information to the client that will allow her to determine when to launch her campaign and what goal to target in order to increase her odds of having a successful campaign. The client had requested additional information into different campaign outcomes based on their launch date and funding goals.

Analysis and Challenges

Analysis of Outcomes Based on Launch Dates

<img width="1040" alt="launch_outcomes" src="https://user-images.githubusercontent.com/104040230/166172064-f8820f2e-4e69-4e48-a030-ca880020d22c.png">


To visualize theater outcomes based on launch dates, we created a pivot table showing the number of successful, failed, and canceled campaigns by month based on all the included years in the provided Kickstarter data. We then plotted that information on a line graph to visualize the data and provide the client with useful information about when to best launch her campaign.

Analysis of Outcomes Based on Goals

<img width="993" alt="goal_outcomes" src="https://user-images.githubusercontent.com/104040230/166172007-68e35977-4d2c-4100-82c8-58a8f07c86e9.png">


To analyze outcomes based on goals, we focused on the “Play” subcategory and pulled data from Kickstarter detailing how many successful, failed, and canceled campaigns there were based on goal ranges. The raw number of campaigns in each outcome was then converted to a percentage based on the total number of campaigns in a specific goal range, which was then plotted in a line graph to show the correlation between campaign outcomes and goal ranges.
Outcomes_vs_Goals

Challenges and Difficulties Encountered

While the client had requested information on the outcome of different campaigns based on launch date and goals, in this analysis we only focused on the Parent Category “theater” for the first analysis and the Subcategory “plays” for the latter. This likely provides Louise with more useful information for her own theater campaign, but does not exactly fit her request. In addition, while there was a correlation between successful outcomes and launch dates and target goals in the theater category, there remains plenty of unknown factors about what contributes to a successful outcome. Unfortunately, it is likely that many campaigns failed because of subjective measures like donors did not like the synopsis of a production.

A factor that may have affected the Outcomes Based on Goals measures may have been the different currencies being used. The numbers should have been converted into one standard currency, but those values would have depended on the exchange rates during the campaign. Using contemporary exchange rates to convert the current to a standard unit is beyond my current skill level. However, using the objectives of the client and the Kickstarter information we were able to provide some data-based results that should give Louise with the knowledge of when to begin her campaign and what goal to target in order to have a successful campaign.

Results

Looking at the graphs in Outcomes Based on Launch date, it's clear most campaigns, regardless of outcome, began in May, June, July, and August (in that order). Overall, more theater campaigns succeeded regardless of launch month, except in December when failed and successful campaigns were near parity. Based on the analysis, however, one conclusion is that campaigns launched in May, June, and July succeeded more than failed (the delta between the two outcomes was at the widest in May, followed by June, and then July). Another conclusion would be to avoid December launch dates since it was the least successful month to launch a campaign.

From the Outcomes Based on Goals analysis, by looking at the graph it appears that Play campaigns under 20,000 and between 35,000 and 44,999 were over 65% successful and that Louise should target a goal of under 4,999 or between 35,000 and 44,9999 for the most successful outcome; however, there are too few actual data points to draw the conclusion that Louise should have a target goal of over 20,000. It is somewhat misleading to use percentages to visualize this data because it does not translate effectively into useful information and gives equal weight to potential outliers. There were only 9 campaigns with goals between 35,000 and 44,999. There were 1,047 total Play campaigns, and 1,005 all had target goals of under 19,999 (with 534 of those campaigns with targets between 1,000 and 4,999). One conclusion that can be drawn from the data is that Louise would have a greater likelihood of success if her target was under 5,000, but ultimately this data should be adjusted to account for outliers and the different currencies.

Another factor potentially impacting the results of the Outcomes Based on Goals is that the currency wasn’t standardized. GBP 5,000 is vastly different than USD 5,000 or CAD 5,000, particularly given fluctuating current exchange values. To better understand the relationship between Outcome and Goal we should have standardized the currency using contemporary exchange rates. This may have shifted some campaigns into higher or lower goal brackets and shown a truer view of the correlation between goal amounts and outcomes.

Other graphs or charts that may provide the client with relevant information to guide her decision on when to launch her campaign and what goals to target include a box plot between goal and pledged for plays in the US and Great Britain. This would provide the client with more information on what goal to target using measures of tendency, measures of spread, and identification of outliers. Another chart that could be useful to the client is one that shows the number of backers and average donations for plays that are similar in scope or plot to the one she is proposing.
