# Financial Time-Series Analysis – Amazon Stock (AMZN)

## Objective
Analyse historical Amazon (AMZN) stock price data to evaluate returns, volatility, moving averages, and drawdowns, deriving actionable insights for financial risk assessment.

## Dataset
- Source: Yahoo Finance
- Asset: Amazon (AMZN)
- Period: 2018-01-01 to 2023-01-01
- Frequency: Daily
- Column used: Close Price

## Tools
- Python (pandas, numpy, matplotlib)
- Jupyter Notebook

## Analysis Steps
1. Data acquisition and cleaning
2. Exploratory Data Analysis (price trends)
3. Returns and rolling volatility calculation
4. Moving averages and trend analysis
5. Drawdown calculation for downside risk
6. Insights and business implications

## Key Findings
- Amazon’s stock shows long-term growth with intermittent corrections.
- Short-term volatility spikes during market stress periods.
- Long-term volatility is more stable, indicating trend stability.
- Moving averages differentiate short-term fluctuations from long-term trends.
- Drawdowns highlight periods of downside risk for better portfolio management.

## Notebook
- `notebooks/amzn_analysis.ipynb` contains full analysis and plots.
- Includes **Price, Volatility, Moving Averages, and Drawdown charts**.

## How to Run
```bash
# Activate virtual environment if you have one
# Install dependencies
pip install pandas numpy matplotlib yfinance

# Open notebook
jupyter notebook notebooks/amzn_analysis.ipynb
