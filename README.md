# Kickstarting with Excel:When and How Much? An Informed Analysis on How to Successfully Fund Your Next Kickstarter

## Overview of Project

### Raising money can be a daunting thought.  It takes a great deal of effort.  It can tap into the energy you need for your creative project.  I believe we can use historical fundraising data to help take the guess work out of this process.  By examining the previously successful kickstarter campaigns, the time of year they started, and how much money was requested (“Goal”), we can help pinpoint when and how much you should ask for to improve your odds of becoming 100% Funded.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    I gathered performance data on successful, failed, and canceled campaigns between 2010 and 2017 across multiple countries for a variety of disciplines ranging from technology, film, photography, and food to name a few.  However, these campaigns may perform very differently.  My scope will be isolated to “theaters” and eventually how “plays” perform specifically.  After extracting the year created from a UNIX timestamp, I organized a pivot table by month.  I then examined the count of all theater campaigns across the 3 outcomes:  successful, failed, and canceled.  To enhance our understanding, I created a line graph as a visual with Month along the x axis.  This provides insight on which month/s have the highest count of successful vs failed campaigns.  

### Analysis of Outcomes Based on Goals
    Through additional analysis I concluded that the goal set by the requestor is also crucial in improving the likelihood of success.  Grouping individual goals into consistent ranges in increments of $5,000 for plays specifically, I examined the count and percentage of the outcomes in question.  To enhance our understanding, I created a line graph as a visual with Goal Ranges along the x axis.  

### Challenges and Difficulties Encountered
    This exercise was fairly straightforward.  Potential issues could arise with dragging CountIFS formulas or forgetting critical criteria.  Placing absolute cell references ($) is key.   

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    My analysis of campaign outcomes by Month shows that regardless of month, the number of successful theater campaigns will always be higher than the number of failed campaigns.  However, to improve and even double the likelihood of 100% funding, I recommend starting your campaign in May or June.  You will face more competition but the conclusion remains the same.

- What can you conclude about the Outcomes based on Goals?
    My analysis of campaign outcomes by Goal Range shows that the amount you request for a “play” factors into the likelihood of 100% funding.  Although findings show two potential sweet spots ($1,000 to $4,999 or $35,000 to $39,999), the higher range ($35,000 to $39,999) is based on a small population and may misrepresent conclusions.  The lower range ($1,000 to $4,999) has the highest percentage of total projects and a 73% chance of success.  A goal in that range should improve likelihood of success.

- What are some limitations of this dataset?
    To improve future analysis, I would have liked to examine how many previous campaigns were initiated by the person requesting funding and whether their previous outcomes influenced backers behavior on later campaigns.  I would also have liked segmentation of backers to provide advice on which type of backers pledge to specific disciplines in order to target campaigning.  

- What are some other possible tables and/or graphs that we could create?
      As the analysis stands, a few observations could be misrepresented.  In the Theater Outcomes by Launch Date, 1 specific year could highly influence the findings.  If a specific year is driving the results, gauging how long ago that was is also important since the conclusion may not be appropriate for the current environment.  We also do not know which subcategory is driving this trend of success in May and June.  Musicals and Spaces could be more successful in those months vs Plays.  I would create a pivot and chart breaking out the 3 theater subcategories for confirmation of findings.  In the Outcomes Based on Goal, I would break down the range 1000 to 4,999 even further to illustrate if success occurs closer to 1000 or closer to 5000.  There additional tables and charts I would create to explore if the binary “staff picks” data influences outcome.  I am also interested to see if duration of a campaign impacts success. 
