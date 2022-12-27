# Analysis of Kickstarter Theater Campaigns

---
## Overview of Project

---
### Purpose

---
This report summarizes data on both successful and failed kickstarter campaigns for plays in the US from May 2009 to March 2017. The project dollar amounts and starting month are tracked to determine the best options for a successfully funded campaign.

---
## Analysis and Challenges

---
The data summarized here is based on actionable, quantifiable variables. The timing of the campaign launch and the monetary campaign goals are straightforward measures of success, but these are not the only factor in the success of a campaign. Unquantifiable data, such as the name of the play and the information provided in the blurb will impact the number of backers, and the level of support backers are willing to provide. 

Not unexpectedly, the succesful campaigns have on average more backers (63 for successful campaigns vs 8 for failed campaigns) and higher average donations ($93 for successful campaigns vs $50 for failed campaigns). While this information is worth noting for monioring the campaign once iut is launched, this is not data that can be acted upon.

---
### Analysis of Outcomes Based on Launch Date
---
The average success rate for all theater campaigns in the US is 61.3%. May has the most campaigns launched in raw counts (166), as well as the most successful campaigns (111) and the highest percentage of successful campaigns (66.9%). December is the worst month to start a campaign, with only 49.3% of the 75 campaigns launched in December being successfully funded. The figure below shows campaign outcomes based on the month the campaign was launched, with May showing the most successful campaign launches. Success rates remain above average through July, then dip below average in August and continue to be at or below average through December and into January. 

![Theater Campaigns by Month Launched. Data is from May 2009 to March 2017.](https://github.com/jaime-mclean/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png) 

---
### Analysis of Outcomes Based on Goals
---
94% of all campaigns had a goal under $20,000. While there are some higher success rates with some of the higher dollar campaigns, the lower sample size at the higher dollar amounts limits the usefulness for predicting success when considering only the campaign goal. What is clear is that campaigns with a goal under $20,000 have a 50% or greater chance of success, with sub-$5,000 campaigns having a 73% chance of being fully funded. The graph below shows the outcomes based on the campaign goal. A reminder that this data shows the percentage of successful and failed campaigns, but does not provide the number of campaigns in each goal range.

![Outcomes of campaigns based on campaign goal](https://github.com/jaime-mclean/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

---
### Challenges and Difficulties Encountered
---
This analysis looks at the actionable variables of launch date and campaign goals separately. These factors do provide adequate guidance for when to launch and reasonable budgetary goals for a successful campaign. Keeping in mind that there is an unquantifiable marketing aspect of the play name and the provided description that can impact the interest of potential backers, both the timing and the goals of successful campaigns are apparent in this analysis.

---
## Results
---
The data indicates that May is the optimal time to launch a campaign, with June and July both being feasible but not ideal. Campaign goals under $5,000 have nearly a 3 in 4 chance of being funded, with campaigns up to $20,000 still having a 50% or greater chance of full funding. For the highest probability of success, launch the campaign in May with a goal of <$5,000. Should the goal exceed $5,000 I wld recommend a more granular analysis, using both the launch date and campaign goal to determine the best launch timing for higher dollar campaigns.

---
