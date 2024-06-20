# Market Risk Management Project

### Project Context
We’ve explored various facets of market risk, including risks associated with equities, bonds, and derivatives. We’ve also use 
the probabilistic and statistical measures to quantify market risk and estimate potential losses for investors or portfolio managers.

### Project Objectives
The main goal of this project is to simulate a real-world risk management process. This involves:

1. Identifying the Portfolio: Selecting a portfolio of assets to assess.
2. Historical Data Analysis: Analyzing historical data to understand past performance and risks.
3. Statistical Risk Measurement: Using statistical methods to measure and understand the risks in the portfolio.
4. Value at Risk (VaR) Calculation: Computing VaR to estimate potential losses at different confidence levels.

### Project Tools
We've ued Microsoft Excel.

### Portfolio and Data
For this project, we focused on a globally diversified portfolio consisting of four equity indexes:
- S&P 500 (US)
- Nikkei 225 (Japan)
- Hang Seng Index (China)
- DAX Index (EU)

The dataset spans two years, from February 2018 to February 2020, providing 500 trading days of data for each index. This period is
selected to include market behavior before the significant impact of the COVID-19 pandemic.

### Currency Considerations
Since the portfolio includes indexes denominated in different currencies (USD, JPY, HKD, EUR), we first converted all values to a 
common currency, which in this case is USD. This requires using exchange rates for:
- USD/JPY for Nikkei 225
- USD/HKD for Hang Seng Index
- USD/EUR for DAX Index

### Data Examination
We started by examining the historical performance of each index within their local currencies and then convert them to USD for a 
unified analysis. Here are the initial observations in local currencies:
- S&P 500: Showed moderate volatility with an upward trend from 2,700 to 3,300.
- Hang Seng Index: Declined slightly from 30,000 to 28,000.
- Nikkei 225: Increased modestly from 2,500 to 23,200.
- DAX Index: Rose from 12,500 to 13,800.

When converted to USD, the Nikkei's performance remains similar, but the DAX shows a slight decline due to currency fluctuations.

### Portfolio Allocation
The portfolio weights reflect the market capitalization of the respective regions:
- S&P 500: 40%
- Hang Seng Index: 30%
- Nikkei 225: 20%
- DAX Index: 10%

### Analysis and Risk Measurement
Here are the steps followed:
1. Portfolio Construction: Combining the indexes into a single portfolio.
2. Statistical Analysis: Calculating measures such as volatility, kurtosis, and other relevant statistics.
3. Value at Risk (VaR) and Expected Shortfall (ES): Determining the VaR for different confidence levels to understand potential losses.

### Summary
This project provides with practical skills in market risk management, including data analysis, statistical risk measurement, 
and portfolio risk assessment in real world. It helps to understand of how to measure and manage market risk in a diversified global portfolio.
