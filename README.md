# 📉 Indian Stock Market Analysis (2020–2025)

## About
Exploratory Data Analysis on 10 NIFTY 50 stocks across 4 sectors
using Python and yfinance. The project analyzes 5 years of real stock
market data from January 2020 to December 2025.

## Stocks Covered
| Sector | Companies |
|---|---|
| IT | TCS, Infosys, Wipro |
| Banking | HDFC Bank, ICICI Bank, SBI |
| Energy | Reliance, ONGC |
| FMCG | HUL, Nestle |

## What the project covers
- **Price Trends** — How each stock moved over 5 years with major events marked
- **Daily Returns** — How much each stock moves on an average day
- **Risk Analysis** — Which stocks and sectors are riskiest
- **Correlation** — Which stocks move together and which are independent

## Key Findings
- ONGC is the riskiest stock (2.30% daily std dev), Nestle is the safest (1.38%)
- TCS and Infosys are highly correlated (0.71) — they move almost identically
- HUL and ONGC are almost independent (0.11) — best pair for diversification
- March 23, 2020 was the worst single day for 8 out of 10 stocks (COVID crash)
- Best 3 stock portfolio from this dataset: TCS + SBI + HUL

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- yfinance

## Dataset
Data downloaded live using the yfinance API — no CSV files needed.
