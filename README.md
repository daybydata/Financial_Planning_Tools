# Financial_Planning_Tools
This notebook contains some tools for financial prediction and planning. The program uses The Free Crypto API to pull crypto currency values and the  Alpaca API to assemble the last 3 years of data on daily closing values of stocks. It uses Monte Carlo simulations to forecast returns for a given portfolio and compare the returns for different portfolio weights and timeframes. The analysis uses data visualization and descriptive statistics to explore and compare scenarios.

<img src="images/MC_30year_sim_plot.png" width="800" height="400">

## Technologies

This program was written in python 3.7. It uses the following libraries:

* [pandas](https://github.com/pandas-dev/pandas) - For dataframe tools and quantitative analysis.

* [pathlib](https://github.com/budlight/pathlib) - For importing and reading csv files.

* [matplotlib](https://github.com/matplotlib/matplotlib) - For creating graphs and charts.

* [requests](https://github.com/requests) - For pulling data from the Free Crypto API.

* [json](https://github.com/python/cpython/blob/main/Lib/json/__init__.py) - For parsing a json file when this format is used by APIs.

* [dotenv](https://github.com/theskumar/python-dotenv) - To get and set keys for APIs.

* [alpaca_trade_api](https://github.com/alpacahq/alpaca-trade-api-python) - A python library for the Alpaca Commission Free Trading API.

## Contributors
Rachael Donham rachaeldonham@gmail.com

## License
MIT
