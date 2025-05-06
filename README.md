# DS4002-CS3
## Summary 
This repository is organized as follows:
LISCENCE.MD: proper citation for repository
SCRIPTS folder: source code for project (for tweets, stock price, and analysis data)
DATA folder: initial and combined data from tweets and stock price dataset
OUTPUT: figures and tables generated from scripts
REFERENCES: sources used throughout project

SCRIPTS



## Reproducing results

1.Tweet_Sentiment_Analysis_&_EDA: Read in Musk tweets dataset imported from Kaggle and perform sentiment analysis and EDA.

Output = new dataframe (Tweet Sentiment Data.csv), EDA graphs

2.Stock_Price_EDA: Read in Tesla stock prices from yfinance over same period of time as twitter dataset, and perform EDA.

Output = new dataframe (Tesla Stock.csv), EDA graphs

3.Data Analysis: This re-reads in Musk tweets and Tesla stock price dataframes, 1)processes and merges data into 1 dataframe (Merged Data.csv), 2)process merged dataframe for time-series analysis so both sets of data are stationary, and 3)performes multiple statistical analysis' to test relationship between sentiment of Musk's tweets and Tesla stock prices.

Output = new dataframe (Merged Data.csv), and statistical summaries of each test

References
References
Metta, Sanjeev & Madhavan, Nidheesh & Narayanan, Krishnamoorthy. (2022). Power of 280: Measuring the Impact of Elon Musk's Tweets on the Stock Market. Ushus Journal of Business Management. 21. 17-43. 10.12725/ujbm.58.2. 
Lennart Ante, How Elon Musk's Twitter activity moves cryptocurrency markets, Technological Forecasting and Social Change, Volume 186, Part A, 2023, 122112, ISSN 0040-1625, https://doi.org/10.1016/j.techfore.2022.122112.
Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text. Eighth International Conference on Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014.
