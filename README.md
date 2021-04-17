# Kickstarting with Excel

## Overview of Project
Analysis of historical Kickstarter campaign data to better understand campaign outcomes relative to campaign goals and the time of year that the campaign is launched.  The analysis also provides a focused perspective on Kickstarter campaigns for theatrical plays.

### Purpose
The analysis will help identify the Kickstarter campaign likelihood of sucess for a prospective play called Fever based on the funding goal and time of launch.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
After converting unix based timestamps into 'readable' dates we are better able to understand campaign outcomes over the course of a calendar year.  We find that the highest theatre campaign activity and highest success rates are in the months of May and June where roughly 2 out of 3 campaigns are successful at reaching their target goal.  With a June launch, Fever is launching their campaign during a period with historically higher success rates and backer activity. ---
![image_name](https://github.com/Christopheremorgan/kickstarter-analysis/blob/main/resources/Theatre_Outcomes_Vs_Launch.png)

### Analysis of Outcomes Based on Goals
Theatre play campaigns with target goals less than $5K have the highest success rates with roughly 3 out of 4 campaigns ending in success.  For campaigns like Fever's with a target goal between $10K between $15K, a little more than half of the campaigns have been successful.  Although not as likely to succeed as smaller campaigns, we find that the likelihood of success typically perform better than project campaigns targeting more than $15K in funding. ---
![image_name](https://github.com/Christopheremorgan/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
challenges you encountered and how you overcame them. learning conversion for Unix timestamps and how to convert into Microsoft serial number dates to get to years was a bit of a challenge.  thought there was an issue with 'cancelled' plays and realized there was not any. If you had no challenges, describe any possible challenges or difficulties that could be encountered. ---
For more detail see analysis file at following link...
[Kickstarter Challenge](https://github.com/Christopheremorgan/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?   Although less likely to succeed, the fact that Fever is trending well towards it's goal is a favorable sign.  When we looks specifically at failed campaigns most only attract a small percentage of their goal [fact check this].

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
