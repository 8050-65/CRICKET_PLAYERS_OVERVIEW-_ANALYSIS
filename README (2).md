# Sports Analytics (Cricket) 
# Objective:
The primary goal of this data analysis project is to evaluate the fitness and performance of cricket players in preparation for an upcoming T20 game. The analysis will focus on understanding each player's current form and historical performance. The insights gained will aid team management in making informed decisions regarding player selection and strategies for the upcoming game. 
# Dataset:
The data includes player details such as full name, date of birth, playing style, teams played for, and career statistics including batting and bowling averages, high scores, wickets, and more. The information is provided in JSON format.
The data is of T20 International. The dataset has players’ details from 7 different countries.
Total Players - 3347
The dataset had too many missing values in the statistics and Top statistics columns. Either the player was not given a chance to bat during a particular match or data was not available. Hence it is meaningless to impute the missing values in the dataset as every player has a unique career statistics. So it is better to drop these null values for further analysis. After dropping the nulls, the data had players around 530 players. 
# Tools Used
* Python
* Pandas
* PowerBI(EDA)
# Data Cleaning
* The information of every player in .json format was extracted to make separate dataframes and then concatenated to make a final dataframe for EDA.
* The relevant information of the players like demographic feature, Player statistics were Extracted and a dataframe was created
* Some of the preprocessing stpes like dropping nulls, duplicates, correcting the data types, formatting the columns and creating new columns were done.
* Once the dataset was clean it was saved as a csv file for further analysis using Power BI.

