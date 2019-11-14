# YASH KALE: FINAL PROJECT PLAN

## MOTIVATION
1. It has been a long time since I have been planning to study the results of the English Premier League. I want to examine the trend of clubs that have been relegated, that have ended up winning the league and see how they perform from season to season.
2. I also want to examine the effects of external factors like referees, or stadiums which the players play in and how that affects the performances of the players on the pitch. This could give a really good insight into the mental aspect of players of a football club. 
3. Another factor that I would like to examine is the effect of playing in front of the home fans vs playing in front of the away games. Does a stadium change make any difference to the outcome of results? Some clubs do really well at their home stadium where as some clubs play particularly well against higher ranked teams. 
5. The fiery games (called derbies) are always very heated matches. In these matches the form of a club always goes for a toss. These are very fiercely contested. Do clubs’ forms change after having a very good result in these derby matches? This causes an uptrend in their form.
6. I want to check if a team starts well in a season, does it help/ has no effect in its final position in the league table?

## DATASET
The dataset can be found on the following website: https://www.football-data.co.uk/data.php.
The dataset contains historical information about the different premier league teams that play in England. The different fields in the dataset provide us with basic data points of the match like goals scored, half time goals scored, goals scored by the home team as well as the away team, number of red cards and yellow cards per team, referee for each match, shots on target, betting odds for these matches, etc. It also provides which was the home team and which was the away team. Alongwith this, we have the exact day on which this match was played. We have this data for the last 25 years, although I plan to use the last 8-9 years of data.

There is no specific licensing page that is present on the webpage, however they have mentioned this on their website, quote: *"You are free experiment with the data yourselves"* and *"Like all of Football-Data's files, it free to download."*

I plan to use this dataset, by analysing if away/home games make a difference to the scoreline of teams. If the home team is trailing at half time, does the home crowd/home stadium help the home team make a comeback? I also plan to see if clubs which are the big spenders, does a managerial change affect how the club performs?
I feel the impact of this analysis is pretty big in terms of how clubs approach certain games. For some teams, they make more fouls, whereas against some teams, they do not change the line ups for home games. This is the reason I chose to study this dataset.

## ETHICAL CONSIDERATIONS
The dataset contains the names of the referees who officiate in football matches. However, they do not contain any information about these referees. Hence, I do not think this violates any ethical rules. However, I had planned to conduct research on a question that revolved around analysing the impact of referees on match results. The result, which would contain the names of the referees, may have resulted in a situation that may have created an issue for the referees, which I have now avoided.  

## QUESTIONS

The specific research questions that I want to ask are as follows:
1. Do clubs recover from a scoreline that is heading to a draw/ one team is losing and go on to win games? How does this defer in home games/away games? Is it easier to win such games in front of the home fans?

2. How do clubs fare in the festive season (December - January) than when they fare throughout the rest of the season? There are a lot of matches in the festive season and clubs faulter during this time.

3. Which clubs have garnered the most points in the 'top 6' against each other?

4. Do clubs that finish lower in the table generate more number of yellow and red cards than the clubs that finish in the top half of the table?

5. Are there any bottom half clubs that are considered as the 'bogey' team for top clubs?

6. Before derby matches, does the form of a club matter and influence the derby games?

7. Do clubs that start well in the season, end up finishing as the winners or in the top 4? Similarly, those who start worse off in the league, do they finish in the bottom half or do they claw their way back?

## BACKGROUND/RELATED WORK

A lot of the questions that I pose come from my backgroung of following the English Premier League and extensively watching these matches. Post matches, there is always analysis done on Television on the number of cards shown, fouls occurred, corners taken etc. I am trying to develop my own analysis of these matches to help answer some questions and develop some hypothesis. Football fans across the world could use this study to understand how the clubs they support fare in the game across the components that I am exploring

## METHODS
I plan to use the basic strategy of grouping the different csv files and created dictionaries per season and per club. I plan to use the pandas, numpy, matplotlib and seaborn libraries of python. Some questions would require plotting of charts using the matplotlib and seaborn libraries, where as some questions can be answered by displaying tables using the pandas dataframe and display them within Jupyter notebook. I would be generating the entire league table by calculating the points won by each club and ordering them in descending order of points won. This will help in giving an overview of what 'top' clubs are and what 'bottom' clubs are.

## Human Centered Considerations
In this dataset, I am to bring about a change in which statistics and numbers are viewed in football. At times, only numbers are not enough to understand how a club is playing. There are other aspects to the game, like the mentality of the players, their eating habits, stadium atmospheres and fan following that affect the result of a match. I want my analysis to show that we need to go beyond quantitative research when analysing how well a football club is doing. This could potentially be used by clubs to introspect and fans to see how their club is performing over seasons. I do not feel there is any bias in the data as these are purely match facts.