# crowdfunding_analysis


# Kickstarting with Excel

## Overview of Project and Purpose

This project analyzed data from Kickstarter campaigns in a variety of ways to help a "client" determine some characteristics of successful and unsuccessful campaigns in the same category and, in the second deliverable, sub-category as the "client's" campaign. The modules included some activities that are not included in the deliverables for this challenge but the two deliverables focus on comparing campaign outcomes by the month in which they are launched, and the success of campaigns based on fundraising goals. 


## Analysis and Challenges

Overall, this challenge included a number of functions in Excel that were new to me but for which I think will be useful in my current job. I have experience using Pivot Tables and in creating Pivot Charts, however, the COUNTIFS statements needed for the Outcomes Based on Goals were brand new for me. Some simple things tripped me up a bit such as copying statements in to adjacent columns, which would in turn change the columns I was referencing. Ultimately I overcame this, however, I am sure that there are far more efficient ways of doing this. Ultimately, I utilized resources in the module as well as additional outside research to solve issues that I was having.


### Analysis of Outcomes Based on Launch Date

When comparing successful, failed, and canceled campaigns by the month they launched, it was surprising to see the variability of the number of successful campaigns and that during May to August, there were more successful campaigns than any other time during the year. This makes me wonder if the outcomes has to do with theater seasons, at least in the US, mostly running from September through April and perhaps the successful campaign managers are able to focus more of their time on generating funding during the off-season months. It seems that though the trend is more muted, it seems that failed campaigns tend to be launched more often in the same months that more successful campaigns are. 

Out of curiosity, I filtered this Pivot Table by year and until 2014, there were only successful campaigns in the data. I'm not really sure what to make of this in isolation but I found it odd.

Interestingly, there seems to be much less variability in both failed and canceled campaigns. I might assume that the low number of canceled theater campaigns is a result of Kickstarter's all or nothing approach to crowdsourcing, whereas other platforms will allow for campaigns to take in money even if they do not reach their goal. I would suppose that there is little incentive for a campaign to be canceled on Kickstarter, even if its success is unlikely.

All in all, even though a greater number successful campaigns begin in May through July, if it were my campaign, I would want to look more at individual years (and surrounding events) and other trends when deciding on timing.

### Analysis of Outcomes Based on Goals

First and foremost, I am surprised that between the 1,048 projects, none of the theater play campaigns had been canceled in this selection. My main takeaway from the Outcomes Based on Goals deliverable is that campaigns are most successful when the goal is less than $5,000. It would be interesting to see some more granularity in the data from goals between $0 and $10,000. There might be a sweet spot where a campaign sets an achievable goal that is also large enough to make the production a success, as well as the campaign.

As the goal amount increases in this set, so does the percentage of failed campaigns through about $35,000. At the same time the number of campaigns trails. It's difficult to figure out from this information why projects in the $35,000-$44,999 range were more or equally successful than failed. Did those campaigns offer better rewards, have more attractive proposals, or were managers asking for that amount of money more famous or have better track records? It would be interesting to look closer  cases in that range.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. More successful campaigns are launched in May, June, and July than in any other months during the year.
2. Roughly equal numbers of successful and failed campaigns begin in December.
- What can you conclude about the Outcomes based on Goals?
1. The highest percentage of successful campaigns have goals less than $1,000.
2. The highest number of successful and unsuccessful campaigns have goals between $1,000 and $4,999, though campaigns are more successful in this range than not.

- What are some limitations of this dataset?
The dataset doesn't provide the quality of the proposed products, the rewards for backers, the popularity, visibility, or experience of the creators of each campaign, or the quality or extent of the promotional materials. It's difficult and maybe a mistake to use this data to decide when to launch a campaign or set a goal without doing a few case studies of successful or unsuccessful campaigns.

- What are some other possible tables and/or graphs that we could create?

As I mentioned before, I would be interested in looking more closely at campaign success by year. Kickstarter is a relatively new platform and my gut feeling is that at a certain point, the popularity of the service likely created a situation where there were more creators launched campaigns that ended up competing for the same backers, creating more failed campaigns. I think from this data, we could likely draw some of these conclusions.

It might also be interesting to look at the length of time the campaigns are active as compared with their funding goals and success. It could be that certain ranges of goals need more time to reach their goals.




[Written_Report_Template.md](https://github.com/benjaminhogan7/crowdfunding_analysis/files/9059862/Written_Report_Template.md)
