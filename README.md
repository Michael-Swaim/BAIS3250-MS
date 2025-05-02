# BAIS3250-MS
Michael Swaim & Brady Hunter

## Project Description
This project is a combination of different analysis techniques to evaluate the S&P 500 stock index

Regarding differnt files, most files will be placed in the Data folder as we only have 2 main files regarding data
- cleaned_sp500_data.csv (the actual cleaned and merged data for the S&P 500 stock data)
- Final Project_Full.ipynb (the Juypter Notebook that contains the code containing our analysis)

There will be a different subfile called Report that will contain the written report of our analysis

## Research Questions

This project aims to find the answers to multiple descriptive questions regarding the S&P 500. The questions are as followed:
- How do average closing prices vary across different sectors in the S&P 500?
- Do specific sectors exhibit stronger performance trends?
- How does trading volume relate to stock price across different sectors?
- Time Series question...

## Data Dictionary
| Field Name | Data Type | Description | 
| ------ | ------ | ----- |
| Symbol | Text | Stock Ticker Symbol |
| Company | Text | Company Name |
| Sector | Text | Business Sector (Technology, Healthcare, etc.) |
| Location | Text | Company Location (U.S., Non-U.S.) |
| Date_Scraped | Date | Highest price of the stock on a given day |
| High | Numeric | Highest price of the stock on a given day |
| Low | Numeric | Lowest price of the stock on a given day | 
| Open | Numeric | Stocks opening price on a given day |
| Close | Numeric | Stocks closing price on a given day |
| Volume | Numeric | Number of shares traded on a given day| 


## References and Initial Datasets
These datasets and websites were scraped, used, cleaned, and then merged together to create our final cleaned dataset in the Data folder
- [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) - Data directly pulled from Yahoo Finance
- [Wikipedia S&P 500](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies ) - Data scraped from multiple pages of Wikipedia
