# STOCK PRICE ANALYSIS
Apple price analysis and prediction
## Project Objective
Analyze and predict Apple (AAPL) stock prices using Python and Machine Learning.

## Data Source
- Historical stock data from Yahoo Finance (using `yfinance` Python library)

## Tools Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- scikit-learn (Linear Regression)

## Analysis Steps
1. Download Apple stock data (2020–2025)
2. Visualize closing price
3. Calculate 50-day moving average
4. Calculate daily returns
5. Build Linear Regression model to predict next-day closing price

## Results
- Mean Squared Error (MSE): 8.58  
- R² Score: 0.99  
- Predicted prices closely match actual prices


# Financial AB Test: Trading Strategy Comparison

## Objective

Compare two trading strategies using Apple stock data:

- Strategy A: Buy when price > 50-day moving average
- Strategy B: Buy when price > 200-day moving average

## Data Source

Yahoo Finance (AAPL) using yfinance Python library.

## Methodology

Calculated daily returns
- Applied trading signals for both strategies
- Computed cumulative returns
- Performed statistical AB test (proportion z-test)
- Compared profitability

## Results

- Strategy performance visualized using cumulative returns
- Statistical test used to evaluate significance
- Best-performing strategy identified

Although Strategy B produced a higher cumulative return (1.68 vs 1.57), the statistical test yielded a p-value of 0.9177 and a Z-statistic of 0.1033, indicating that the difference between Strategy A and Strategy B is not statistically significant.
Therefore, the observed performance difference cannot be considered reliable.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- statsmodels
- Google Colab

## Author

KENGNE NGUEKO Danielle

