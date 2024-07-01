<h1 align="center">Cricket Data Analysis</h1>

## Problem Statement
We are given four datasets containing the information of all matches played in world cup 2022.
- Match results dataset
- Batting dataset
- Bowling dataset
- Players dataset
  
## Goal
- From the given data create a team of 11 best players across the tournament.
- That include 2 openers and 2 middle order batsman, 2 batting and 2 bowling all rounders and 3 specialist bowlers.
- The team should be able to score good runs as well as it is capable to defend that target easily.


### Our execution plan
- We are given data into json file which is not arranged properly.
- Our plan is to clean data
- After cleaning data add viaualization on it.
- From visualization fetch the required result.

#### Data Cleaning and preprocessing.
- We are given data into json file.
- we have to perform data cleaning over it using pandas.
- make a list of columns that has to be calculated for selecting players for each role based on given criteria and parameters.
#### Data Visualization.
- Performed data visualization over cleaned data by ploting the graphs.
- Choose the best players that make best fit for specific playing role.
#### Calculate results.
- Select all players and create a team of 11.
- Calculate the total performance of whole team.

## End Results
#### Batting point of view.
- The team is able to score 180+ runs with the batting strike rate of 150+.
- The good batting average and average balls faced by each players results the team will survive it does not fall to all out.
- Good boundary percentage results the team is full of hard hitters who gets most of the runs through boundaries.
#### Bowling point of view.
- Our bowling average falls below to 11.61 that is our team is capable of taking wicket for each 11.61 balls.
- Our bowling strike rate falls below to 11.26 that is our team is capable of taking wicket for each 11.26 runs.
In case if we need an extra bowler we have two extra batting all rounders which is able to bowl well.
