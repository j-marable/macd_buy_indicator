# MACD Stock Purchase or Sale Indicator

- This project is written in Python 3.10 coding language..
-  Skills shown and used include a basic knowledge of Python functionality including:
  - - if/else/elif statements
  - - Data Type interchanges
  - - variable creation, scope, and utilization
  - - indexing knowledge and data manipulation

## Libraries and Modules Used:
- numpy
- pandas
- matplotlib
- yfinance

## Financial Advice Disclaimer: 
- This is not financial or investment advice. I do not have formal training or knowledge in financial trading or markets. This project is created purely for educational purposes and you should not construe any such information or other material as legal, tax, investment, financial, or other advice. I am not an attorney, accountant, or financial advisor, nor am i holding myself out to be. The information outputted by this code and contained in this repository is not a substitue for financial advice from a professional who is aware of the facts and circumstances of your individual situation.

## Purpose and Usage:

- Purpose - see how/if the Moving Average Convergence/Divergence (MACD), is a good indicator of when to buy and/or sell a stock for maximum gain. The MACD is classically a trend following momentum indicator that shows the relationship between two Exponential Moving Averages (EMAs) of a security's price. 

- Usage - this code uses the EMA-12 and EMA-26 to calculate MACD, a MACD signal, MACD value, and MACD histogram are graphically plotted to visualize these trends. Based on comparison, this code will output whether or not it may be a good time or bad time to buy a particular security of interest. To run the code, input security ticker of interest (all caps) in Cell 2 where (ticker = "insert ticker here"), then excecute all cells to calculate and plot. Please see disclaimer above before downloading and/or using.
  
## Data Source:
- Yahoo Finance (yfinance) API
