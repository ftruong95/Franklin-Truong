
ETL Project

In order to gather data needed for our project we used 3 different datasets from Kaggle which lead us to the CDC website to gather additional data. The data in the three files included the following information:
•	Covi-D-19 
•	Obesity 
•	Population Density
The fields of interest include the following:
•	State
•	Population 
•	Population Density
•	Number of Covi-D-19 cases
•	Covi-D-19 Cases per 1,000,000 Population
•	Death from Covi-D-19
•	Covi-D-19 Deaths per 1,000,000 Population
•	Obesity per state

Sources for our datasets used:
https://worldpopulationreview.com/state-rankings/state-densities
https://chronicdata.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/data
https://www.kff.org/other/state-indicator/confirmed-covid-19-cases-and-deaths/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D

Transformation
In order to use and merge the data together in our project we had to do the following:
•	We used Pandas in Jupyter Notebook to and transformed them into data frames.
•	Identified duplicates and changed column names to be used for PgAdmin
•	Created queries by grouping the data by state, obesity stats, and population density per state. 
 Load
In order to transfer out final output into a database. We created a database and table to match the data we had in our final clean Pandas Data Frame we created through Jupyter Notebook. Using Postgre in PGadmin we loaded our clean data sets and generated new tables for the data frames. 
Summary
The ETL Project was overall a group collaboration project. We were able to gather data through various websites and began to clean and merge using Jupyter Notebook. With PGadmin we were able to generate the tables for our dataframes. We ran into some initial issues cleaning data when we could not drop a row due to a column spacing error, but we were able to overcome this.  One issue we ran into but could not finish due to the time constraint. We were not able to have the decimal points in our data to have the same number of spaces. 

