# An Analysis of Kickstarter Campaigns

## Overview of Project
In this project I performed data analysis on several thousand crowdfunding projects to uncover hidden trends.

### Purpose
The purpose of this analysis is to assist Louise in launching a effective and successful kickstarter campaign for her play.
## Analysis and Challenges
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96965776/168953051-21139a2f-b102-4d71-b62c-b4a3575a32aa.png)
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/96965776/168953126-e44baca2-e555-43f7-852b-5fad0ec94a14.png)


### Analysis of Outcomes Based on Launch Date
Looking at the "Outcomes Based on Launch Date" graph we can see that campaigns at the beginning of the year trend upward. With campaigns launched in May having more success. As the year goes on, it can be seen that the successful launches trend downward and eventually cross the failed campaigns.


### Analysis of Outcomes Based on Goals
Looking at the "Outcomes Based on Goal" graph we can see there is a downward trend of successful campaigns as the amount of the goal increases. After about 30,000 the success/fail rate is about fifty percent. There after that range the fail rate goes up to 100 percent.


### Challenges and Difficulties Encountered
In this data set there were a few challenges. One was converting the dates to a readable format to better graph our analysis. This was overcome by using the Date function in Excel to adjust the time stamp to a readable format. Another challenge was an #DIV/0! error. Some kickstarters did not have backers. This was addressed by using the IFERROR function to have the outcome be zero if there were no backers and the #DIV/0! error pops up. Zero was put instead of a text to help with graphing the data.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first conclusion would be that launching in the spring time, or more specifically May, would give Louise the best chance to have a successful campaign.

The second conclusion is the first 3 months of the year, Oct and Nov have about the same amount of succesful campaigns.

- What can you conclude about the Outcomes based on Goals?

We can conlcude that the Goal of the campaign highly effects the success of the campaign. A reasonable range would be from 1-20,000.

- What are some limitations of this dataset?

One limitation of the data set is that there was one outlier where the goal was the highest, it was funded with the fewest people, and had the highest donations that could possibly skew the data.

- What are some other possible tables and/or graphs that we could create?

We could have used a histograph to display the "Outcomes Based on Launch date." We could also use a box plot to show "Outcomes Based on Goal" to help identify any outliers in the data.
