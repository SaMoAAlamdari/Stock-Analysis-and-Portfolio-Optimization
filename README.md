# Stock-Analysis-and-Portfolio-Optimization

## Description
This project provides tools for downloading historical stock data, visualizing trends, calculating statistics, and performing portfolio optimization using the Sharpe Ratio.

## Table of Contents

1. [Description](#description)
2. [Setup and Installation](#setup-and-installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Code Overview](#code-overview)
6. [Data](#data)
7. [Contributing](#contributing)
8. [License](#license)
9. [Conclusion](#conclusion)

## Setup and Installation

### Requirements

- Python 3.7+
- pandas
- yfinance
- matplotlib
- seaborn
- numpy

### Installation

Install the required libraries using pip:


pip install pandas yfinance matplotlib seaborn numpy


## Usage
1. Download or clone the repository.

2. Run the provided script to:

  - Download historical stock data.

  - Prepare and clean the data.

  - Visualize stock prices and calculate moving averages.

  - Calculate daily returns and correlations.

  - Perform portfolio optimization and simulate portfolios.

## Features
Data Visualization: Line plots, histograms, and heatmaps to understand stock trends and relationships.

Moving Averages: Calculation and plotting of 50-day and 200-day moving averages.

Daily Returns: Calculation and visualization of daily returns for each stock.

Correlation Matrix: Calculation and plotting of the correlation matrix of daily returns.

Portfolio Optimization: Simulation of portfolios to optimize returns based on the Sharpe Ratio.

## Code Overview
Importing necessary libraries.

Downloading and preparing historical stock data.

Visualizing stock prices and moving averages.

Calculating daily returns and plotting their distribution.

Calculating and plotting the correlation matrix.

Simulating portfolios and calculating Sharpe ratios.

Identifying optimal portfolios and their stock allocations.

## Data
The historical stock data used in this project can be downloaded using the yfinance library as shown in the scripts.

## Contributing
Feel free to contribute by creating pull requests, raising issues, or suggesting improvements.

## License
This project is licensed under the MIT License.

## Conclusion
In this project, we successfully analyzed historical stock data, visualized key financial trends, and performed portfolio optimization using the Sharpe Ratio. The insights gained from the data analysis and visualization help in understanding the performance of different stocks, while the portfolio optimization process assists in making informed investment decisions to maximize returns and manage risk.

We utilized various Python libraries such as pandas, yfinance, matplotlib, seaborn, and numpy to achieve these goals. The comprehensive approach provided a thorough understanding of stock market behavior and the importance of diversification in investment portfolios.

Future enhancements could include incorporating additional financial metrics, automating data updates, and extending the analysis to other asset classes such as bonds or cryptocurrencies.

By leveraging these tools and techniques, investors can make data-driven decisions to optimize their portfolios and achieve better financial outcomes.
