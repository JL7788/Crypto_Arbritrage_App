# Crypto Arbitrage App

This application will allow you to sort through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. It will apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.

---

## Technologies

This project uses Python 3, Pandas, Pathlib, and matplotlib

---

## Installation Guide

Before running the application first install the following dependencies.<br />

Python, Pandas, Jupyter Notebook

---

## Findings

To use the loan qualifier application simply clone the repository and run the **crypto_arbitrage.ipynb** with python.<br />
Make sure to open the folder along with the resources included.<br />
<br />I first set the paths for both the Bitstamp and Coinbase dataframes and dropped all the NaN values. All the "$" values were then removed and all values in the "Close" column were changed to a float type. <br />All duplicated values from both dataframes were then removed as well.<br />
Next I sliced the Close column for both dataframes in order to get summary statistics and plot graphs for early, middle, and late date's in the dataframe. I then plotted the two plots on top of each other to visualize the differences. <br /><br />I also used a simple equation to find the arbitrage spread and plotted that as well using early, middle, and later dates to test each of them respectively. Data was also plotted to in box plots as well to show the spread. 


---

## Contributors

Starter code provided by UCB 

