# Kickstarting with Excel

## Overview of Project
**Analysing and visualizing Kickstarter Theatre plays campaign outcomes**
based on Launch dates and funding goals

### Purpose
**Provide Louise with a clear and simple display showing campaign results** 
based on the launch date and funding goals, so right decisions can be made on when she should launch her next project, and how much funding should she be aiming at.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To analyse outcomes based on launch date, we had to diplay the right information
In this case, we had to have "THEATRE" ,"YEARS" , and "OUTCOMES" filtered
The challenge lies in filling the pivot table fields with the right values, and then 
pivoting to a linear chart for better and clearer visualization purposes.
![Theatre_Outcomes_vs_launch](https://user-images.githubusercontent.com/85769235/122838759-98d0e680-d2ab-11eb-8655-ae0bfe47813c.png)

### Analysis of Outcomes Based on Goals.
To analyse outcomes based on Goals, we had to go deeper into excel formulas so we can pull out the right information quickly and efficiently
We had to create different ranges of Goal amounts and work on each and every one using COUNTIF formulas 
(ex: =COUNTIFS('Successful plays worksheet'!D:D,">=10000",'Successful plays worksheet'!D:D,"<=14999")) 
so we can extract the right information out of this goal range and relate the successes, fails and plays cancelations to each range with the appropriate percentage.
Now that we have a clear table displaying this data, a line chart is needed to showcase the outcomes in a fun and easy readable way
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85769235/122838918-e0577280-d2ab-11eb-9995-9f08d43853e8.png)

### Challenges and Difficulties Encountered
Setting up the pivot tables with the right fields so the right data set is dispayed, and going through all the countifs formulas to make sure we have the right goal ranges was a bit challenging

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1- A theatre play's kickstarter campaign best chances to succeed comes in May and June, although the failed campaign number have slightly risen as well, but that's minor looking at the exponential rise in the successes 
2-Worst time window to throw a Theatre play kickstarter is by the end of the year, December to be more precise, as it shows on the linear chart where success rate drops so low while failure rates increase.

- What can you conclude about the Outcomes based on Goals?
A theatre play's kickstarter campaign goal ranging between 1000-4900 & 40000-44999 have the best chance of succeding with low failure chances as diplayed.

- What are some limitations of this dataset?
Working on two different data sets, in the first one, we are analysing "theatre outcomes" while we're doing "plays outcomes" on the second one

- What are some other possible tables and/or graphs that we could create?
Outcomes based on backers count
Outcomes based on country
Outcomes based on deadlines
Outcomes based on date created
