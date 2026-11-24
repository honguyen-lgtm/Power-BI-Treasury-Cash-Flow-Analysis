# Treasury Cash Flow and Liquidity Analysis

## Project Overview

This Power BI project analyzes cash flow performance, forecasts future cash balances, and evaluates liquidity requirements to support treasury and financial decision-making.

## Business Objectives

- Monitor historical cash inflows and outflows.
- Identify monthly cash flow trends.
- Determine the largest cash expenditure categories.
- Evaluate projected cash balances over a 90-day period.
- Assess whether projected cash balances meet minimum liquidity requirements.

## Tools and Technologies

- Microsoft Power BI
- Microsoft Excel
- DAX
- Relational Data Modeling
- Financial Data Visualization

## Data Modeling

The data model consists of three tables:

- **BankAccounts:** Beginning balances, minimum balance requirements, and bank account information.
- **CashTransactions:** Historical cash transactions, departments, categories, and transaction amounts.
- **CashForecast:** Expected future cash transactions, forecast amounts, and expected dates.

One-to-many relationships were established using Account ID to connect the BankAccounts table with the CashTransactions and CashForecast tables.

<img width="583" height="241" alt="image" src="https://github.com/user-attachments/assets/a84b19ab-19f7-4c8e-9cb0-7c9537a45c1a" />

## Dashboard 1: Historical Cash Flow Overview

The dashboard provides an overview of historical cash flow performance from January through September 2026.

| Financial Metric | Result |
|---|---:|
| Beginning Cash Balance | $725,000 |
| Total Cash Inflows | $5.31M |
| Total Cash Outflows | $4.46M |
| Net Cash Flow | $844.19K |
| Ending Cash Balance | $1.57M |

The dashboard includes monthly cash flow trends, expenditure categories, and interactive department filtering.

<img width="575" height="332" alt="image" src="https://github.com/user-attachments/assets/a7515ee6-abe1-46cb-b43a-39987af9ef8c" />

## Dashboard 2: Cash Forecast and Liquidity

The dashboard evaluates projected cash flow from October through December 2026.

| Financial Metric | Result |
|---|---:|
| Forecasted Cash Inflows | $1.44M |
| Forecasted Cash Outflows | $942.35K |
| Forecasted Net Cash Flow | $502.27K |
| Projected Cash Balance | $2.07M |
| Minimum Cash Required | $425,000 |
| Liquidity Buffer | $1.65M |

<img width="578" height="322" alt="image" src="https://github.com/user-attachments/assets/f2ea1e64-8ef9-4129-87e6-d2a7bacdb7c4" />


## Key Findings

- Historical cash flow was positive overall despite negative cash flow in January, March, and April.
- Vendor payments represented the largest cash outflow category.
- Projected cash balances exceeded minimum liquidity requirements.
- The projected liquidity buffer of approximately $1.65 million indicates sufficient cash under the forecast assumptions.

## Business Recommendations

- Monitor vendor payments to identify potential cash management opportunities.
- Closely monitor December's forecasted cash outflows, which exceed expected inflows for that month.
- Regularly update cash forecasts to reflect changing financial conditions.
- Maintain sufficient cash reserves to meet operational requirements.

## Skills Demonstrated

- Financial Analysis
- Treasury and Liquidity Analysis
- Cash Flow Forecasting
- DAX Measures
- Relational Data Modeling
- KPI Development
- Interactive Dashboard Development
- Business Intelligence
- Data Storytelling
