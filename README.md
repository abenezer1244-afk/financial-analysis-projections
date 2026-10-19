# financial-analysis-projections
This project is a financial analysis tool that evaluates publicly traded companies using financial data from Yahoo Finance. Users can enter a company’s stock ticker symbol, and the program automatically retrieves the company’s available historical financial statements.

The analysis focuses on revenue, net income, operating income, operating cash flow, capital expenditures, free cash flow, profit margins, and historical growth. It also creates five-year financial projections using bear-case, base-case, and bull-case scenarios.

The goal of this project is to make financial statement analysis more accessible while demonstrating how Python can be used to analyze companies and support investment research.

## Main Features

- Analyze different publicly traded companies by entering their ticker symbol
- Retrieve financial statement data through Yahoo Finance
- Review up to five years of historical financial performance
- Analyze revenue and net income trends
- Calculate operating and net profit margins
- Calculate operating cash flow and free cash flow
- Estimate historical revenue growth using CAGR
- Create five-year financial projections
- Compare bear-case, base-case, and bull-case scenarios
- Display financial values in billions of dollars
- Create professional charts and tables
- Export historical analysis and projections as CSV files

## How to Use the Project

The project is designed to be used in Google Colab.

1. Open the notebook in Google Colab.
2. Locate the ticker input near the top of the code.
3. Enter the ticker symbol of the company you want to analyze.

For example:

```python
TICKER = "AAPL"
