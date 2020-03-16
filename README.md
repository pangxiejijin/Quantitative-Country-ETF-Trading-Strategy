# Quantitative-Country-ETF-Trading-Strategy-and-System-of-the-21-Century
WQU Capstone Project

## Authors
* Arturo Aguilar
* Xiaochen Lin
* Wen Jiang

©Arturo Aguilar. ©Xiaochen Lin. ©Wen Jiang. All Rights Reserved.
 
This project is an effort to build an investment strategy of global equity allocation to outperform MSCI All Country World Index (ACWI). The strategy includes technical, fundamental, economic, market sentiment and alternative factors. A framework of the trading strategy is shown below.
![factors](/factors.png)

## Table of Contents
### Folder:
#### factor data
stores time series data for each factor and each ETF, generated using [process raw data into factor data](/process%20raw%20data%20into%20factor%20data.ipynb) and [process price data into factor data](/process%20price%20data%20into%20factor%20data.ipynb).
#### price data
stores daily ohlcv data for each ETF, generated using [download price data](/download%20price%20data.ipynb).
#### forward return
stores forward 21-trading day return for each ETF, generated using [process price data into forward return](process%20price%20data%20into%20forward%20return.ipynb)
#### raw data
stores raw factor data (has been removed).


## Results
### Developed Markets & Emerging Markets

<br/><br/>
<br/><br/>
<br/><br/>
<br/><br/>
<br/><br/>
<br/><br/>

### U.S. Subcase: Three Factors & Five Factors: 2017 and 2018

US:VOO

S&P 500 Index, representing 500 of the largest U.S. companies. Goal is to closely track the index’s return, which is considered a gauge of overall U.S. stock returns. 

https://investor.vanguard.com/etf/profile/VOO


FF3_factors[['Mkt-RF','SMB','HML']])



FF5_factors[['Mkt-RF','SMB','HML','RMW','CMA']]
 


## References

[1] Marko Kolanovic & Zhen Wei (2013). Systematic Strategies Across Asset Classes. JP Morgan. Available at: https://www.cmegroup.com/education/files/jpm-systematic-strategies-2013-12-11-1277971.pdf (Accessed: 17 February, 2020).

[2] MSCI. (2020). MSCI ACWI Index. Available at: https://www.msci.com/acwi (Accessed: 17 February, 2020).

[3] Bloomberg. (2020). Market Data. Available at: https://www.bloomberg.com/professional/product/market-data/ (Accessed: 17 February, 2020).

[4] Jennifer Bender, Remy Briand, Dimitris Melas & Raman Aylur Subramanian (2013). Foundations of Factor Investing. MSCI. Available at: https://www.msci.com/documents/10199/71b6daf5-9e76-45ff-9f62-dc2fcd8f2721 (Accessed: 17 February, 2020).

[5] GMO. Global Equity Allocation Fund. Available at: https://www.gmo.com/americas/product-index-page/equities/global-all-country-equity-allocation-strategy/global-equity-allocation-fund---geaf/?accept=Funds(Accessed: 17 February, 2020)
