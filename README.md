# Group Project One
 
 ![[Images/title_picture.png]](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/title_picture.png)
 ## Executive summary:
 A client approached RIPPED - an investment consulting company - requiring technical advice on how to invest in the current volatile market conditions. The investor is fully aware that share and crypto prices have been volatile and declining as the US Federal Reserve has dramatically increased the overnight cash rate. 

 With the US 2-year treasury rising from almost zero to 4.16% and the S&P 500 and Nasdaq decreasing in 2022 by 19.6% and 26% respectively, it is time to review the client’s portfolio to provide recommendation (s) that provides the optimal returns with the lowest possible risk. 

 RIPPED has produced for the investor a technical report specifically detailing past percent investment performance, risk analysis, correlation between interest rates moves and the indexes. Based on the analysis RIPPED has also provided Monte Carlo simulations projecting future probable returns. 

 ### Available Investment Funds:
 ---
 Comprised of $100,000 evenly split:
 - S&P500 - $50,000

 - NASDQ - $50,000

 ### Objectives are as follows:
 ---
- Maximise returns\performance
- Evaluate investment split and determine best weighting
- To provide 5 year forecasts providing client with several suitable investment options

 ### Analysis and Forecast Periods:

 - Back test data from 01/10/2002 to 29/09/2022
 - Monte Carlo forecasts for 5 years

 ### RIPPED has performed the following:
 -	Analysed current portfolio and potential risk to performance
 -	Provided recommendation to minimise volatility
 -	Forecast future in interest levels and likely asset performance outcomes
 -	Determine a forecasted optimal portfolio mix
 -	Provided recommendations to his investment strategy 

 ### Technical and Analysis Tools:
 RIPPED utilised the following technical tools to produce a detailed presentation and report:

![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/tools.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/tools.png)

 ### Summary Recommendations:
 As detailed in the report, RIPPED has made the following recommendations based

- The Heavy weight - NASDAQ Portfolio has the greatest return potential of $633,339.
- The Heavy weight - SPY Portfolio has the least downside return potential with $80,192.

![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/bokeh_plot-6%20.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/bokeh_plot-6%20.png)

 ## 1.	Detailed Analysis Outcomes 

 ### Performance of the following stocks over the past 5 years
 ### Cumulative returns
 The cumulative return is the total change in the investment price over a set time—an aggregate return, not an annualized one. Reinvesting the dividends or capital gains of an investment impacts its cumulative return.
 Most investors would view an average annual rate of return of 10% or more as a good ROI for long-term investments in the stock market.
 Cumulative returns for the SP500 and Nasdaq have been outstanding over the past 5 years. Whereas US Bonds (note 30-year Treasury Bonds) have provided a subpar return. Please note the following:
 -	SP500:	 343.563%
 -	Nasdaq:	1241.571%
 -	Bonds:	-20.785%

 ## SP500 Cumulative Returns Chart:
![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Picture%201.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Picture%201.png)

 ## Nasdaq Cumulative Returns Chart:
![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Picture%202.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Picture%202.png)

 ## Bonds Cumulative Returns Chart:
![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Picture%203.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Picture%203.png)

 ## Annual volatility
 Annualized volatility describes the variation in a asset's value over the course of a year. This measure indicates the level of risk associated with an investment. This includes the distribution of a portfolio that features the asset, and the likelihood of a shortfall when during the asset's eventual sale.
 Volatility averages around 15%, is often within a range of 10-20%.  All three assets are considered more volatile.  
 - SP500: 	19.221%
 - Nasdaq: 	22.571%
 - Bonds: 	29.446%

 ## Sharpe ratio
 Sharpe ratios above 1 are generally considered “good," offering excess returns relative to volatility. 
 The ratios for these asset classes clearly show that while returns are high so is volatility – note this is an important factor for the client to consider. Very high returns and high risk. 
 - SP500:	0.48
 - Nasdaq:	-0.69
 -Bonds:	0.11	

 ## Worst Drawn Down Periods:
 Following the Sharpe ratios showing high volatility in respect of returns the clients carefully needs to consider portfolio cash management. High volatility means big swings in portfolio values. 
 The following tables provides statistical forecasts:

 ### SP500:
 ![(Images/S&P500 data.png)](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/S%26P500%20data.png)

 ### Nasdaq:
![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/NDAQ%20data.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/NDAQ%20data.png)

 ### Bonds (US 30 Year Bonds):
![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Bond%20data.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/Bond%20data.png)

 ### Correlation of Asset Performance Returns:
![https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/correlation_plot.png](https://github.com/RJSMART-11/Group_Project_One/blob/main/Images/correlation_plot.png)


 ### References
 ---
 ![(References.md)](https://github.com/RJSMART-11/Group_Project_One/blob/main/References.md)
 
 ### Next time
  - Forecast interest rates
  - Bulit in calculator/ ability to make it inter-active
  - Include more assets class
  - Experince more functions within pyfolio
 
 ### Challenges
 - Timeframe
 - Data Collection - Bonds
 - Pyfolio Concaternation
 ### Installation
 - Pyfolio - git+https://github.com/quantopian/pyfolio
 - yfinance - pip install yfinance
