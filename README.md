# CE1015-Mini-Project 
# Dataset based on Modelling Earthquake damage, caused by the 2015 Gorkha Earthquake in Nepal
# Dataset source used for analysis: https://www.drivendata.org/competitions/57/nepal-earthquake/ 
# Dataset prepared by Kathmandu Living Labs and Nepal’s Central Bureau of Statistics; one of the largest post-disaster datasets ever collected
# Objective: To build a code that analyses the given dataset, models and simulates the relationship between the ordinal-variable ('Damage_grade') and the important predictors.
# Damage_grade represents a level of damage to the building that was hit by the earthquake. There are 3 grades of the damage:
  1: represents low damage
  2: represents a medium amount of damage
  3: represents almost complete destruction
# Approach:
  •	Perform basic Uni-Variate Analysis on the response and predictor variables.
  •	One-Hot Encoding of categorical variables, before preparing the decision-tree classifier. 
  •	Build this Decision-Tree based Machine Learning Model to simulate relationship between ordinal-variable ('Damage_ grade') and important predictors. 
  •	Prepare a Feature Importance chart to rank damage level predictors on basis of influence by implementing the Random Forest algorithm. 
  •	Bi-variate and Tri-variate analysis on damage-grade v/s the important predictors, for further analysis and comparison. 
  •	A Simulator that uses the Decision tree to predict the damage grade based on random input values of selected predictor variables. 

