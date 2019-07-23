# Shiny application for algorithmic trading

Author: Piotr Wójcik (University of Warsaw)

# Description

The aim of this presentations is to show Shiny application that can be applied to backtest selected algorithmic strategies applied on historical quotations of S&P 500 stocks. Uploading own data with is also possible. The application allows to select assets that will be considered in the strategy, define different entry and exit techniques based on technical analysis indicators (including two moving averages/medians crossover, volatility breakout and double volatility breakout). Trading can be applied on single assets or pairs. Different pair selection methods are available ? based on correlation, regression and cointegration. The strategy performance is assessed with several commonly used measures (incl. aggregated PnL, Information Ratio, maximum drawdown) in gross and net terms (after taking into account transactional costs). One can also perform strategy parameters optimization based on the selected criterion and verify its performance on the test data. 

