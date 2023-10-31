## [Project 1: Sales Prediction Model](https://github.com/WasiShaikh977/Sales-Prediction-Model/tree/main)
![](/images/DL_RMSE.png)

### Project Overview
In this study, the primary objective was to develop a machine learning and deep learning model that leverages historical sales data of similar products to predict the sales of unsold items.

We had data from a chain of stores selling food items. The data was divided into 2 datasets - 
- Train data (historical data with target column)
- Test data (Prediction dataset with no target column)

### Conclusion
#### Key Insights
1) Outlet **OUT027** is making the most amount of money.
2) Outlet location tier 3 seem to make the most sales. Especially the combination of Tier 3 location and SuperMarket Type 3.
3) Starchy foods and Dairy have high MRPs whereas Seafood and Starchy food seem to be making more sales on average.
4) Grocery Stores have been the worst performers compared to all other supermarket types.
5) Medium sized stores make the most amount of money followed by High and then Small. The mean MRP of the goods sold is nearly the same for all the sizes.

### Model Performance
The Deep Learning model turned out to be out best model with an RMSE of 1074.7. Both the deep learning models were identical in their performance.
The top 3 models were as follows:

1 - Deep Learning: RMSE 1074.7

2 - Optimized Random Forest Regressor: RMSE 1077.5

3 - Gradient Boosted Decision Tree: RMSE 1082.5

## [Project 2: Estimating the salary of a Data Scientist](https://github.com/WasiShaikh977/Data-Science-Salary-model)
![](/images/salary.png)

### Project Overview
- Created a model that estimates the salary for a job in data (data science,data analysis,MLE, etc)
- Exploratory analysis of the data to find patterns and get insights
- Visualisation of the said patterns and insights
- Tested on Linear, Lasso and Random Forest Regressor. Used GridSearchCV to optimize our best model

### Conclusion
##### Key Insights from EDA
- Python is as key programming software for people looking to work in the field of Data Science or any other data related roles.
- People with Python and Machine Learning skills stand a good chance of earning an above average salary (in relation to other data roles)
- California, DC and New York came out as the best locations overall, taking into account the number of openings and the estimated salary.
- Low to mid tier companies seem to be hiring a high number of people in data related jobs whereas public companies are the ones offering the highest salaries

##### Modelling performance
- Linear Regression: Extremely poor performance
- Lasso: 15.68 MAE (Decent)
- Random Forest: 10.06 MAE (Good)


## [Project 3: Who is the best winger in the English Premier League?](https://github.com/WasiShaikh977/PL-Wingers-Weighted-index)
![](/images/SalahReport.jpg)

### Project Overview

In modern football, tons of different metrics are used to determing how well a player does in certain aspects of the game. Goals, shots on target, goal conversion rate, etc, show you how good a player is at scoring goals. Whereas, other stats like key passes, assists, through passes, cross completion percentage, etc, point towards how good a player is at creating chances for her teammates. Hundreds of KPIs (Key point indicators) are used by football analysts and data scientists to objectify a player's performance.

In this project, we will handpick 21 of these KPIs and use statistical modelling techniques to mesh all of them together into one metric. This is the Wingers Weigthted index. The higher the index, the better the player. We will create 4 such indexes (All rounder, Goalscorer, Creator, Dribbler). Different weights will be given to different metrics for the various indexes.
- All Rounder index: Equally distributed weights as per a winger's requirements
- Goalscorer index: More importance given to goalscoring metrics
- Creator index: More importance given to chance creation metrics
- Dribbler index: More importance given to dribbling metrics

![](https://github.com/WasiShaikh977/PL-Wingers-Weighted-index/blob/main/images/All%20Rounders.png)

### Key Findings
- Statistically speaking, Mohamed Salah has been the best winger in the Premier League for the past 3 seasons. This is also backed by the general fan sentiment and the mainstream football opinion.
- The next 3 in the list are all Manchester City players. No surprise here as City have dominated the Premier League and have one of the best goalscoring output not just in the league but also across Europe.
- Phil Foden and Gabriel Martinelli are the only current U23 players to make the top 10 in the overall rankings.
- Michael Olise ranked 3rd among the best U24 wingers over the last 3 seasons. Olise and Neto were the only 2 players who played for a non-top 6 club and finished in the top 10 (for U24s).
- Statistically, Gabriel Martinelli was the best U23 winger last season and the 2nd best overall pipping the likes of Jack Grealish, Phil Foden, Mahrez, et al. Salah was still number 1.
- The top 2 U-23 wingers last season were Bukayo Saka and Gabriel Martinelli, both of Arsenal. These 2 young men led Arsenal's title challenge with their scintillating play. Bukayo Saka also earned the young player of the season award for his performances.
- Julio Enciso made a mark in his first season in the PL ranking 3rd for U23s and 7th overall in the season 22-23.

## [Project 4: Underlying Performance Numbers of the top 6 Premier League Sides](https://github.com/WasiShaikh977/Top-6-teams-xG-SMA/tree/main)

### Project Overview

The goal of this study is to quantify underlying performance metricss of the top 6 teams in English Premier League to see how they have progressed/regressed since the start of the season 2019/2020 season

Expected Goals (xG) is a statistical metric used in soccer to assess the quality of a scoring opportunity. It quantifies the likelihood that a shot will result in a goal based on historical data and various factors. For this study we will look at the difference between cumulative xG of a team and Expected Goals Against (xGA). xGA is the total xG value of all the shots conceded by a team, reflecting the expected goals their opponents could have scored. This difference is called the expected goal difference or xGD.

We will look at the trends in Expected Goals Difference for the top 6 English Premier League teams since the start of season 2019/2020 upto gameweek 4 of season 23/24 (03/09/2023).

![](/images/Top6updated.png)

### Key Findings

- Manchester City have been the best-performing team in the English Premier League since Boxing Day 2019.
- Arsenal have shown significant improvement in performance during the study timeframe.
- Liverpool challenged City's dominance in the 21/22 season but has since seen a decline.
- Chelsea have been the worst-performing side in the sample.

## [Project 5: Finding Vardy's Replacement (Tableau project)](https://public.tableau.com/app/profile/wasiuddin.shaikh8022/viz/ReplacingJamieVardy/Story1) 

### Project Overview

In this project, I acted as a recruitment analyst for Leicester City Football Club (LCFC) and aimed to find a successor for their and England Natoinal team striker Jamie Vardy. I looked at Vardy's importance to LCFC starting from season 2015-2016 up until 2022-2023 (8 seasons), his style of play, how we compares to other strikers in the league, LCFC's transfer trends and multiple seasons player data from 3 different leagues (England Championship , French Ligue 1 and Italian Serie A) to draw out a shortlist of strikers to replace Jamie Vardy with.

Similar to project 3, I created a weighted index metric to find the best strikers who are similar to Jamie Vardy in their playing style.

### Key Findings
- Statistically, Vardy has been one of the best strikers in the English Premier League. He profiled as a poacher- A striker who is not too involved in the game for the most part but is deadly in front of the goal.
- 4 of the top 5 players in our shortlist played in Ligue 1.
- Folarin Balogun (finished 2nd in our rankings) was my recommendation as the recruitment analyst taking into account all the variables (explained in the Tableau slides)

![](/images/Vardy.png)


### Extras

#### [Masters' Dissertation: How to score from a corner kick?](https://medium.com/@wasi.ws453/analysis-of-attacking-corner-kicks-in-division-1-of-english-football-2f13766a30ab)

![](/images/corner.png)

