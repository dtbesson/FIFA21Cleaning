# FIFA 21 Cleaning Project
## Introduction
This is a quick project done at home in order to practise my data cleaning skills in Python. No real data analysis is undertaken on this project. Please check the attached Jupyter notebook to see a walkthrough of the process.

## The Data
The credit for this dataset is to user Rachit Toshniwal on Kaggle, who scraped it off of sofifa.com. Find the Kaggle page here: https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring .

The dataset contains information about every player within the game, including their names, in-game stats, basic information (such as weight, preferred foot, nationality, club) as well as some extra information (such as the players wage, value or whether they are on loan). 
The dataset is intentionally messy for the purpose of practise in data cleaning. There are mixed data types in each column, columns which need to be removed, null values that need to be considered, and unusual characters which need to be dealt with, before any effective
analysis can take place.

## The Process
Please check the Jupyter file for the details of my process.

First, I save the .csv file, import any packages I will be using and load the file into Python. 

The Kaggle user provides 6 questions to guide anyone using the dataset:
1. Convert the height and weight columns to numerical forms
2. Remove the unnecessary newline characters from all columns that have them.
3. Based on the 'Joined' column, check which players have been playing at a club for more than 10 years!
4. 'Value', 'Wage' and "Release Clause' are string columns. Convert them to numbers. For eg, "M" in value column is Million, so multiply the row values by 1,000,000, etc.
5. Some columns have 'star' characters. Strip those columns of these stars and make the columns numerical
6. Which players are highly valuable but still underpaid (on low wages)? (hint: scatter plot between wage and value)

I go about answering these questions, but I also carry out a few more cleaning tasks that I felt were necessary.

The final result is a dataset that is primed for analysis!
