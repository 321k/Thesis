Thesis
======
This repository consists of the functions and tests used for my Master's Thesis at Hanken School of Economics.

The main functions are:
downloadDailyGT
- Download Google Trends data in monthly intervals for a specified list of queries. Google returns the data in daily intervals.

downloadWeeklyGT
- Download Google Trends data for all available periods. Google returns the data in weekly or monthly intervals.

importGT
- Import all csv files from a given directory into a list

summaryTable
- Summarize the data structure of the imported data

formatGT
- This function extracts the time series data based on the specified data structure in summaryTable

mergeGT
- Merges the Google Trends data into a data frame

Once these functions have been added to R from files 1-3, file 4 contains the code for executing the functions and organizing the data. The data is stored as a list containing the Google Trends data and stock market data.
