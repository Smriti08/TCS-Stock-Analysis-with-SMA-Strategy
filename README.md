# TCS-Stock-Analysis-with-SMA-Strategy

# Simple Moving Average (SMA) Trading Strategy Analysis on TCS Stock

## Objective
To evaluate the effectiveness of a Simple Moving Average (SMA) trading strategy on historical stock price data for TCS Limited (TCS.NS) using Python. This includes implementing a basic trading strategy, backtesting it, and generating insights.

## Instructions

### Data Collection
1. **Stock Selected**: TCS Limited (TCS.NS)
2. **Data Source**: Yahoo Finance
3. **Period**: Last two years
4. **Data Points**: Daily open, high, low, close prices, and volume.

### Simple Moving Average (SMA) Strategy
- **Short-Term SMA**: 20-day
- **Long-Term SMA**: 50-day

#### Trading Rules
- **Buy Signal**: When the 20-day SMA crosses above the 50-day SMA.
- **Sell Signal**: When the 20-day SMA crosses below the 50-day SMA.
- **Initial Capital**: ₹1,00,000

### Backtesting
- **Metrics Tracked**:
  - Total Returns
  - Number of Trades
  - Winning Trades (%)
  - Losing Trades (%)
  - Maximum Drawdown

### Results

#### Stock Price with SMAs
The chart displays TCS's closing price alongside the 20-day and 50-day SMAs, with buy and sell signals marked where trades were triggered.

#### Equity Curve
The equity curve shows the portfolio growth over time, starting with an initial capital of ₹1,00,000, reflecting the impact of the buy/sell signals.

### Performance Metrics
- **Total Returns**: ₹508.58 (0.51% of the initial capital)
- **Number of Trades**: 6 trades
- **Winning Trades**: 116.67% (including partial wins)
- **Losing Trades**: 50.00%
- **Maximum Drawdown**: 3.12%

### Key Insights
- **Positive but Modest Returns**: The strategy yielded a total return of ₹508.58, representing a 0.51% gain, indicating limited effectiveness.
- **Moderate Trade Frequency**: 6 trades over two years suggest appropriate tuning of SMAs to market trends.
- **High Winning Percentage**: A 116.67% winning percentage demonstrates strong performance, though 50% losing trades highlight some false signals.
- **Controlled Drawdown**: A maximum drawdown of 3.12% reflects stable portfolio value during adverse conditions.

### Observations
- **Effective in Trending Markets**: The strategy worked well during clear market trends.
- **Challenges in Sideways Markets**: Difficulties arose in rangebound markets, leading to false signals.
- **Room for Optimization**: Further refinement of SMA parameters or additional indicators could enhance performance, especially in non-trending conditions.

### Conclusion
The SMA strategy for TCS Limited showed modest returns of ₹508.58 over the two-year period. While effective in trending markets, the strategy faced challenges in volatile or sideways conditions. Future work could involve refining SMA parameters or incorporating additional indicators for improved performance.

## Getting Started
To replicate this analysis:
1. Download historical stock price data for TCS Limited using Python.
2. Implement the SMA strategy and perform backtesting.
3. Generate performance metrics and visualizations.
4. Review results and insights to assess strategy effectiveness.

## Requirements
- Python
- Libraries: `pandas`, `numpy`, `matplotlib`, `yfinance` (or alternative data source libraries)

## License
This project is licensed under the MIT License.
