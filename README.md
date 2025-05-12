# Trading Bot

### Description: 
This was a Group assignment done for CFM 101, where teams competed to create a portfolio of stocks which would maximise their risk. A CSV file with randomely picked stocks tickers 
would be given to each team. From this each team creates the most volatile strategy to pick sstocks for their portfolio.
This was then measured over a 5 day period, where my team and I won 3rd place. 

**How The strategy works:** Using python in JupiterNotebooks, we retrieved the monthly closing prices of each stock, and filtered them to suit the competitions requirements. 
Next we found the standard deviation, the top 10 most correlated stocks for each stock, and the moving mean across 9 months. This was used to find a group of stocks that had the 
highest overall correlation, that were also extremely volatile and had showed promising price movements. We used the Monte Carlo simulation to optmise each stock weighting within 
the portfolio to maximise overall volatility. 

### Download Instructions: 
