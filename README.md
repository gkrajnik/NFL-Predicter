NFL-Predictor

In this project, we made a program that predicts the outcomes of NFL regular season games using previous games from the same season, and a point calculation system that takes the previous week's points and adds them up to compare to the opposing teams total. Then it makes a pie chart and a percent comparison to show who is most likely to win.

Dependencies

  OS version: Python 3.13 (Jupyter hub)
  Libraries: Pandas, Numpy, matplotlib.pyplot, sys

Installing

  Download from Github (https://github.com/gkrajnik/NFL-Predictor)

Executing program

Linear Regression

  Download top files “yearly_team_stats_offense.csv” and “yearly_team_stats_defense.csv” so they can be imported
  Run box numbers 1 and 2 to import libraries, upload both files into variables and then clean those files
  In box 3 change the X variable category, the part in quotations, to the category in the dataframe you would like to compare   to wins and run the box
  Run boxes number 4 and 5 to call the linear regression graph and builds the slope by using x to predict y
  In box 6, change the x-label, title, and savefig lines based on what variable you picked as the x variable and run that box
  Then your graph will be produced and saved in your local directory, if you would like to run box 7 to get the slope and       intercept of the line
  
NFL Predictor

  Download files 3 and 4, which is “weekly_team_stats_offence” and “weekly_team_stats_defense” 
  Run box 1 to import libraries
  Run boxes 2 to clean the dataframe 
  Run box 3-4 to initialize the functions used for gathering previous weeks data
  Run box 5-6 to initialize the functions that calculate and output the point total and the team name
  Run box 7 to initialize the final function used to find the percentages of winning that the home team has and the away team   has
  Now, run box 8 to start the code
  After this it will ask for two inputs, one of a team that you input the abbreviation in all caps, and one for the week
  Then it will output the prediction and a pie chart of the game

Files

Notebooks and Scripts

  Linear Regression Graph.ipynb: Used to make the linear regression graphs.
  NFLPredictorREG.ipynb: Main code used to predict the outcome of the next game.
  
Datasets

  Yearly_team_stats_offense.csv: Dataset used to calculate linear regression lines
  Yearly_team_stats_defense.csv: Dataset used to calculate linear regression lines
  Weekly_team_stats_offense.csv: Dataset used for the calculations in the main code
  Weekly_team_stats_defense.csv: Dataset used for the calculations in the main code
  
Authors

  Garrett Krajnik - gkrajnik06@gmail.com 
  Ian Nie - ianjnie24@gmail.com 
  Matt Minor - minor.matt@outlook.com









