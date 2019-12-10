# machine_learning_volatility
Machine Learning algorithm that trains on a market dataset and then determines if the future volatility will be higher than various volatility levels.   It processes a data set and then uses Decesion Tree clustering algorithm to test various volatility levels.  It also shows various other volatility statistics.   

# Objective 
Machine Learning Algorithm that takes an asset's high, low, close, open interest and volume information, trains and predicts if the future realized volatility will be higher or lower than a user defined level. Preprossing functions cleans and creates data frames that looks ahead to a forward period from points in time and determines if a user defined volatility threshold has been exceeded. This allows for a Machine Learning Algorithm to train on the data set and make predictions.  Within this notebook, a Machine Learning clustering Decision Tree algorithm trains on a financial asset's daily market information. Function allows user to set a range of volatilities to test after training. It then makes predictions based on the most recent days in the data set. 

# Volatility
Volatility is an annualized standard deviation and used as the unknown variable when pricing options. A link to how volatility relates to option prices is here: 
[Volatility Explanation](https://www.investopedia.com/ask/answers/062415/how-does-implied-volatility-impact-pricing-options.asp)


# Install
The Jupyter notebook is written in Python 3.  In addition a sample csv file is provided.  Set variable 'og' in the notebook to the sample csv file.  Run the notebook.  

# Contributing
machine_learning_volatility was written by Matthew Aronowitz


