# PCA of Top 20 (Market Cap) Tech Sector Stocks in S&P 500

This project performs Principal Component Analysis (PCA) on the daily returns of the top 20 tech-sector stocks in the S&P 500 index, based on their market capitalization. The analysis provides insights into the underlying factors driving the movements of these stocks.

## Project Overview

The notebook demonstrates the following steps:
1. **Stock Data Collection**: Using the `yfinance` library, stock data for 20 top tech companies is fetched for a 2-year period (from December 2021 to November 2023).
2. **Daily Returns Calculation**: Daily returns are computed for each stock, and the dataset is saved for further analysis.
3. **PCA Implementation**: Principal Component Analysis is applied to the stock returns to identify the key factors (principal components) that explain the variance in the stock returns.
4. **Visualization**: The results of PCA are visualized to interpret the importance of each component.

## Files

1. **`PCA_AS.ipynb`**: The main Jupyter notebook containing the code for the analysis.
2. **`stock_data.xlsx`**: Contains the stock data and daily returns for the selected stocks. This is used as input for PCA.
3. **`pca_results.xlsx`**: Contains the results of the PCA analysis, including the eigenvalues, eigenvectors, and explained variance for each principal component.

## Setup

To run this project, you need the following Python libraries:
- `yfinance`
- `numpy`
- `pandas`
- `sklearn`

You can install them via pip:

```bash
pip install yfinance numpy pandas scikit-learn
