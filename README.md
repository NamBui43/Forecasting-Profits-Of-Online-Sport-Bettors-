# Predicting-profits-of-internet-sport-bettors-
Final Project for CS-C3240 Machine Learning D at Aalto University

## Introduction

- The objective of this project is to formulate and compare the efficiency of 2 machine learning models that closely predict the profit of an internet sport gambler based on his/her gambling volume and tendency. The project has a very specific business application which is to help online casinos effectively classifying customers based on their predicted profits, thereby developing specialized customer strategies such as targeted offers and loyalty program. 

## Data Description and Problem Analysis
- The dataset used in this project comes from the collaborative Internet gambling research project between the Division of Addictions (DOA) and bwin Interactive Entertainment (bwin), and was obtained from transparencyproject.org (title: Population Trends in Internet Sports Gambling)
- The dataset initially contains 46,339 datapoints, which represent the demographic and sport betting records of 46,339 users on bwin’s website throughout 18 months of the research (01.02.2005 - 31.08.2006). All monetary properties are in Euros €. Originally, there are 21 features available for each datapoint, representing specific demographic and sport betting information of users such as gender, date of birth, date of registration, the total number of bets made and the total amount of money spent. Such various and insightful features are compatible for specialized predictions aimed by the models
- The 3 feature variables selected for the model are factors that highly reflect the gambling trend of a sport gambler including the total number of bets, the total number of days doing sport betting on bwin’s website and the average amount of money spent on a bet
  
## Modelling

- Polynomial Regression and Decision Tree Regression were used
- The performances of the 2 models were compared to determine the superior option

