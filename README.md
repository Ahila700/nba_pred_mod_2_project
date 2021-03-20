# NBA Stats Analysis

### Project Overview

My project is to analyze nba statistics from the last 10 seasons. Winning games in the nba is hard and there are 15 players, a head coach, multiple assistants, general managers etc whose job is just to win games. So what I want to try and do is help find the statistics from seasons that have happened to see what exactly led to those wins in the season. Analyzing stats such as pace, defensive ft attempts per game, assists, rebounds etc. 

The idea is to see that if pace has a large affect on the data than playing faster will be important for all teams, and following suit for all the other stats. And so thats what I did. I found that in fact the defensive statistics are the ones that have the largest affect on the data. Turnovers and defensive effective field goal percentage were the stats that had the largest affect on wins. On the offensive side it was efficiency that really had an affect on wins rather than quantity, meaning stats like true shooting percentage was more important than points in general. 

---
### Process and Data Gathering

All of my data for this work was taking through wed scraping of the basketball reference site. They have a ton of data from every year, and since I was just looking for the basic and advanced stats for all the teams that was all on there. I took data for every team from the 2014 season to the present. Mainly to keep the data manageable and easy to analyze through simple visualizations. But also because the NBA has undergone a drastic shift in styles in the last decade compared to previous years. With analytics in basketball causing a huge 3 point shift. The change in the approach to games, I felt, would have too much of an impact and cause the data to be muddled if I went back much further. 

---
### Github Content

####Exploratory Data Analysis - 
Scatter plots for all features against the wins

![alt text](https://github.com/Ahila700/nba_pred_mod_2_project/blob/master/TS%25.png)

![alt text](https://github.com/Ahila700/nba_pred_mod_2_project/blob/master/DFG%25.png)

![alt text](https://github.com/Ahila700/nba_pred_mod_2_project/blob/master/Age.png)

Heat maps for correlation to find high correlation and collinearity


####Final Models:
Final model was made using lasso method and the best features from the analysis through Exploratory data Analysis
  
####CSV files -
Csv files used and created during the project are all part of the github
 


