# Kickstarting with Excel

## Overview of Project
Analysis of historical Kickstarter campaign data to better understand campaign outcomes relative to campaign goals and the time of year that the campaign is launched.  The analysis provides a focused perspective on Kickstarter campaigns for theatrical plays.

### Purpose
The analysis will help identify the Kickstarter campaign likelihood of sucess, based on the funding goal and time of launch, for a prospective play called Fever.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
After converting unix based timestamps into 'readable' dates we are better able to understand campaign outcomes over the course of a calendar year.  We find that the highest theatre campaign activity and highest success rates are in the months of May and June where roughly 2 out of 3 campaigns are successful at reaching their target goal.  With a June launch, Fever is launching their campaign during a period with historically higher success rates and higher campaign activity.
![image_name](https://github.com/Christopheremorgan/kickstarter-analysis/blob/main/resources/Theatre_Outcomes_Vs_Launch.png)

### Analysis of Outcomes Based on Goals
Theatre play campaigns with target goals less than $5K have the highest success rates with roughly 3 out of 4 campaigns ending in success.  For campaigns like Fever's with a target goal between $10K between $15K, a little more than half of the campaigns have been successful.  
![image_name](https://github.com/Christopheremorgan/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
One particular challenge was conversion of data from Unix timestamps and then converting into Microsoft serial number dates to be able to filter the data by years.  At first I thought there was an issue with building statistics for 'canceled' play campaigns, but interestingly, when looking at the raw data there is no history of a play campaign that was canceled. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?  First, the months with the most campaign activity and the highest success rates historically are the months of May and June.  December and January seem to be the least favorable time periods to start a Kickstarter campaign for a play.

- What can you conclude about the Outcomes based on Goals?  With the exception of a handful of play campaigns in the $35k to $45K range, the success rate for play campaigns decline as the funding goal increases.  However, ~90% of all Kickstarter theatre campaigns had funding goals of less than $10K.

- What are some limitations of this dataset?  It would be helpful if there were more categorization of plays for Louise to better understand how she trends against like productions.  Also, given that we only have the final numbers, we don't have an opportunity to tell Louise how she compares against other campaigns at a particular point in the campaign.  For example, did most successful campaign achieve >50% of their funding in the first week of the campaign? 

- What are some other possible tables and/or graphs that we could create?  One in particular that would be helpful for Louise is to identify how well the campaign is progressing is the percentage funded rates for failed campaigns.  Since Louise's funding has started strong her likelihood of success is high as 97%% of failed projects did not achieve 50% of their funding goal and a large majority achieved less than 30% of their goal.  Relatively few campaigns failed after reaching 50% of their funding goal.

For more detail see analysis file at following link...
[Kickstarter Challenge](https://github.com/Christopheremorgan/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)
