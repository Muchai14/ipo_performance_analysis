
# IPO Performance Analysis

A Python project exploring IPO performance, holding periods, and an RSI-based trading strategy using financial market data.

## Analysis

- Classify withdrawn IPOs and compare offering values.
- Evaluate growth, volatility, and Sharpe ratios for 2025 IPOs.
- Compare holding periods from 1 to 12 months.
- Backtest a strategy investing $1,000 per RSI oversold signal.
- Explore ideas for improving IPO selection.

## Key Findings

- A one-month holding period produced the highest median IPO growth, approximately 0.935×, representing a 6.46% loss.
- Longer holding periods generally showed lower median growth.
- Extreme outliers distorted average performance, highlighting the importance of examining medians.

## Tools and Data

**Python:** Pandas, NumPy, yfinance, Requests, gdown, PyArrow

**Sources:** IPOScoop, Yahoo Finance, and a course-provided dataset containing technical and macroeconomic indicators.

## Getting Started

Install dependencies:

    pip install pandas numpy yfinance requests lxml gdown pyarrow jupyter

Open `ipo_performance_analysis.ipynb` in Jupyter or Google Colab and run the cells in order.

## Methodology and Limitations

Results depend on data availability and may change over time. The RSI backtest treats each signal as an independent investment and excludes trading costs. The Sharpe calculation follows the course formula and differs from the conventional returns-based definition.

## Background

Developed from a financial data analysis course assignment and presented as a portfolio project.
