# BAIS3250-MS
Michael Swaim & Brady Hunter

## Table of Contents
| Name | File/Folder | Description |
| ----- | ----- | ----- |
| Data | Folder | Contains all data files and relevant code for this project |
| cleaned_sp500_data.csv | File | Final cleaned and merged dataset located within the Data folder |
| Final Project_Full.ipynb | File | Jupyter Notebook containing all analysis and code |
| Report | Sub-Folder | A subfolder within the Data folder that holds the written report |

## Project Description
This project applies various data analysis techniques to examine and interpret trends within the S&P 500 index.

Most files are stored within the Data folder, including the two key data-related files:
- cleaned_sp500_data.csv (the finalized, cleaned dataset of S&P 500 stock data)
- Final Project_Full.ipynb (the Jupyter Notebook containing the full analysis)

A separate subfolder called Report contains the written summary of our analysis.

## Research Questions

This project seeks to answer several descriptive questions related to the S&P 500. The questions include:
- Does industry sector impact stock price?
- Are some sectors inherently more volatile or more heavily traded?
- Can we identify patterns or trends that suggest sectoral influence on stock prices?

## Data Dictionary
| Field Name | Data Type | Description | 
| ------ | ------ | ----- |
| Symbol | Text | Stock Ticker Symbol |
| Company | Text | Company Name |
| Sector | Text | Industry Sector (Technology, Healthcare, etc.) |
| Location | Text | Company Headquarters (U.S. or Non-U.S.) |
| Date_Scraped | Date | Date the data was collected |
| High | Numeric | Highest stock price on a given day |
| Low | Numeric | Lowest stock price on a given day | 
| Open | Numeric | Opening stock price for the day |
| Close | Numeric | Closing stock price for the day |
| Volume | Numeric | Number of shares traded on a given day |

## References and Initial Datasets
These datasets and sources were scraped, cleaned, and merged to form the final dataset in the Data folder:
- [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) - Historical stock data obtained from Yahoo Finance
- [Wikipedia S&P 500](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies) - Sector and company data gathered from Wikipedia
