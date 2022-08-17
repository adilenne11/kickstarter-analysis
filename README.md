# Louise's Theater Campaign Analysis
## Purpose:
The purpose of this analysis is to help Louise make informed decisions about when to launch her theater campaign and how much the funding goal should be for the best success rate.
## *Theater Outcomes Based on Launch Dates*:
The line graph *Theater Outcomes Based on Launch Dates* shows the number of successful, failed, and canceled theater campaigns based on the month the theater campaign was launched. A launch date in May for theater has proven to be the most successful in a timeline of 7 years. However, launch dates in May, June, July, August and October have about the same number of failed theater campaigns.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/110357810/185199262-b99dc273-b674-43c2-9eaf-bfc0bb08072d.png)
## *Outcomes Based on Goals*:
The line graph *Outcomes Based on Goals* shows the percentage of successful, failed, and canceled campaigns based on the funding goal. A funding goal of less than $1,000 is proven to be the most successful. 76% of campaigns succeeded with the funding goal of less than $1,000.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/110357810/185199136-d7f0163f-6597-49cd-b404-75b2bc7c8f23.png)
## Conclusion:
Louise has a better theater campaign success rate if the campaign is launched in May with a funding goal of less than $1,000.
## Limitations:
The line graph *Outcomes Based on Goals* does not display the total number of projects.  This is a limitation because percentages alone can’t show the number of campaigns done that resulted in these percentages. For example, based on the line graph alone, one could conclude that there is 100% failure rate for all campaigns that are funded $45,000 to $49,999. However, the line graph does not show that there was only one campaign that received this amount of funding and it failed. The table needs to be alongside the line graph for additional information.
## Challenges:
The writing of the countifs() functions were difficult because of the length and there is more chance for typo errors. I overcame this by writing the countifs() function on paper. This way I was able to visually organize all the additional filters that needed to be added to the function. It also helped to make sure the commas and quotation marks were in the correct place.
Here is what the countifs()function looks like:
```
=COUNTIFS(Kickstarter!$D:$D,">=30000",Kickstarter!$D:$D,"<=34999",Kickstarter!$F:$F,"successful", Kickstarter!$R:$R,"plays")
```
Because it is lengthy there is more chance for typo errors for a beginner like me. I wrote it down on paper to visually organize the additional functions.
![Countifs() functions on paper](https://user-images.githubusercontent.com/110357810/185197351-f20d912d-a49d-456d-aae7-16936f25a82b.jpg)
