# NBASocialMediaPerformance
Using machine learning to predict NBA player's season performance based on their social media metrics

I worked on this project in May, 2020.

## File Descriptions

**nba_pie.csv**: Data file of each player and the team they are on  

**nba_2017_players_stats_combined.csv**: Data file of each individual player's performance in the 2016-2017 NBA season  

**nba_2017_players_with_salary_wiki_twitter.csv**: Data file of basic player stats as well as salary, wikipedia and twitter statistics  

**decisionTrees.Rmd**: Data cleaning, preprocessing, decision tree algorithm, random forest algorithm, and gini importance mechanism  

**logisticRegression.Rmd**: Cross validation, logistic regression, and avplots  

**nba codebook.pdf**: Dictionary for the different basketball statistics and acronyms  

**PSTAT131FinalProjectSubmission.pdf**: My team's final project submission, includes the writeup and our code at the bottom.  

## Machine Learning

This focuses on predicting one variable, Performance Impact Estimation, or PIE. This variable is a calculated combination of all other variables to estimate a basketball player's skill. I used a decision tree and then a random forest algorithm to see how well social media can predict a player's skill.

This project also considers how well salary measures a player's skill, and which one is a better measurement. Can the masses on social media do a better job at recognizing the best players, or does money talk? This was highlighted through the gini importance mechanism, which found salary to be the best indicator for a player's performance.

## Improvement

- Have more metrics of social media engagement, such as instagram followers or likes
- Have more metrics of wage, such as sponsor deals


