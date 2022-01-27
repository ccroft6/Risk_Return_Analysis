# Risk_Return_Analysis

This is a risk-return analysis of four investment options for inclusion in client portfolios. The goal is to determine the fund with the most investment potential based on four key risk-management metrics: daily returns, standard deviations, Sharpe ratios, and betas. This quantitative analysis took into account the performance, volatility, risk, risk-return profile, and portfolio diversification when deciding which of the four funds to include in the client portfolios. The following four funds were analyzed: Soros Fund Management LLC, Paulson & Co Inc, Tiger Global Management LLC, and Berkshire Hathaway Inc. They were compared against the broader market benchmark of the S&P 500.                                           

---

## Technologies

This project uses Jupyter Notebook (within [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)) and the standard Python 3.8 libraries. In addition, this project requires the following libraries and/or dependencies:

* [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation

* [Pathlib](https://docs.python.org/3/library/pathlib.html) - a Python module which provides an object API for working with files and directories

* [NumPy](https://numpy.org/) - a Python library that provides a multidimensional array object, various derived objects, and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more

* [matplotlib](https://matplotlib.org/) - a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy

---

## Definitions

* **Daily Returns**: A rate-of-return calculation that compares the current value of a stock to its initial value. In this case, the current value is the closing price, and the initial value is the closing price on the previous day. Higher daily returns mean better asset performance. 

* **Standard Deviation**: Measures the volatility of an asset's price compared to its historical mean over a particular time period. A higher standard deviation means more volatility (more risk). When daily return values are greater than +/-1 standard deviation of the mean, the asset is considered more volatile. 

* **Sharpe Ratios**: Assesses risk and reward by measuring the excess return (that is, the reward, or profit) for the risk that someone assumes when investing in the asset. The greater the value of the Sharpe ratio, the more attractive the risk-adjusted return is for an asset. 

* **Beta**: Measures the directional relationship between an asset (i.e., stock, fund) and the broader market. A beta of 1.0 indicates that the asset's return value will likely be exactly the same as that of the market. A beta that's greater than 1.0 indicates that the change in the asset's return value will likely be greater than the change in the market's return value. A beta that's less than 1.0 indicates that the change in the asset's return value will likely be less than that of the market.

* **Portfolio Diversification**: Reduces risk by spreading money among a wide array of investments. Includes an assortment of assets that have different risk profiles. 

---

## Methods

For this analysis, the following steps were taken:

1. Analyze the Performance - Plot the daily return data and the cumulative return data of the four funds and the S&P 500 portfolio to see if any of the portfolios outperform the broader stock market (represetned by the S&P 500). 

2. Analyze the Volatility - Plot box plots of the daily return data for the four funds and the S&P 500 and then box plots for just the four funds. Assess the spread and determine which fund is the least and most volatile. 

3. Analyze the Risk - Evaluate the risk profile of each portfolio by calculating the standard deviation, annualized standard deviation, and 21-day rolling standard deviation. Plot the rolling standard deviations and assess which portfolio poses the most risk. 

4. Analyze the Risk-Return Profile - Evaluate the risk-return ratio by calculating the Sharpe Ratios. Plot a bar chart to visualize the Sharpe Ratios assess which portfolio offers the best risk-return portfolio.

5. Diversify the Portfolio - Evaluate how the portfolios react relative to the broader market by calculating the betas of two of the four portfolios that look the best to include in the portfolio. Plot the 60-day rolling beta of the two portfolios and assess which of the two portfolios are the best recommnedation for inclusion in the firm's suite of fund offerings. 

---

## Findings

In response to each of the steps taken as indicated in the Methods section above, these were the results:

1. Performance: None of the four funds outperformed the broader stock market (S&P 500). 

2. Volatility: The Berkshire Hathaway fund was the most volatile as indicated by ....

3. Risk: The fund that poses the most risk is .... as indicated by ....

4. Risk-Return: The fund that offers the best risk-return profile is .... as indicated by ....

(sharpe ratio graph)

5. Portfolio Diversification: The best fund for inclusion in the firm's suite of fund offerings is ....

---

## Contributors
Catherine Croft

Email: catherinecroft1014@gmail.com

LinkedIn: [catherine-croft](https://www.linkedin.com/in/catherine-croft-4715481aa/)

---

## License

MIT