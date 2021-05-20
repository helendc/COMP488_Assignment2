# COMP488_Assignment2
# Task
Given a data set with ~30 million records from LendingClub.com determine an investment strategy for peer2peer lending.

# Project Breakdown
1. Data Cleaning
> - Remove unnecesary columns
> - Remove special applicants
> - Convert categorial data 
> - Replace Nan values with reasonable sustitutes
2. Data Wrangling 
> - Create "red-flag" indicator 
> - Formulate return
> - Create dummy variables from categories
> - Create Sharpe Ratio
> - Standardize the numeric data
3. Determine the target
> - Split independent features into train and test sets 
5. Analysis of two models
> - Average return for each sub grade 
6. Portfolio Simulation
> - Tested on different loan size per sub grade 

# Conclusion
Our regressions reveal that mixing “shaky” high grade loans (e.g. A4s, B3s) with sure bets (e.g. A1s) yields the highest returns.
