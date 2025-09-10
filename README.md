# 📊 Portfolio and Credit Risk Analysis

This project implements a comprehensive **risk management framework** covering market risk assessment, portfolio optimization, fixed-income securities modeling, and credit risk evaluation for Brazilian assets. The analysis combines quantitative finance techniques with fundamental analysis to provide actionable insights for investment decisions.

## ⚙️ Features

- 📈 **Market Risk Assessment**: Volatility calculation for 20 Brazilian stocks using logarithmic returns
- 🧮 **Portfolio Optimization**: 
  - Equal-weighted portfolio construction
  - Minimum volatility optimization with constraints (0-10% per asset)
  - Maximum Sharpe ratio optimization
- 📊 **Fixed-Income Analysis**: NTN-B bond modeling with cash flow projections and duration calculation
- 🏦 **Credit Risk Evaluation**: Comprehensive assessment of Suzano Papel e Celulose S.A.
- 📉 **Technical Implementation**:
  - Automated data retrieval from Yahoo Finance
  - Statistical analysis and covariance matrix calculations
  - Constrained optimization using SciPy
  - Financial modeling with object-oriented programming

## 📋 Project Structure

### Part 1: Market Risk Analysis
- **Volatility Calculation**: Annualized volatility for 20 Brazilian stocks using daily adjusted closing prices
- **Portfolio Construction**: Equal-weighted portfolio with 19 valid assets (5.3% allocation each)
- **Optimization Results**:
  - Equal-weighted portfolio volatility: 15.98%
  - Minimum volatility portfolio: 13.59%
  - Maximum Sharpe ratio: -0.7188 (negative due to market conditions)

### Part 2: NTN-B Bond Analysis
- **Bond Modeling**: Brazilian inflation-linked government securities with semestral payments
- **Cash Flow Projections**: VNA calculation, coupon payments, and principal repayment
- **Risk Metrics**: Macaulay duration calculation (4.46 years for sample bond)
- **Pricing Model**: Present value calculation using appropriate discount rates

### Part 3: Credit Risk Assessment
- **Company Analysis**: Suzano Papel e Celulose S.A. (SUZB3)
- **Risk Factors**: Market, currency, leverage, operational, environmental, and geopolitical risks
- **Financial Analysis**: Balance sheet, income statement, and cash flow evaluation
- **Credit Recommendation**: Positive assessment for R$500MM credit facility

## 🛠️ Technologies Used

- Python 3.x
- yFinance for market data
- Pandas for data manipulation
- NumPy for numerical computations
- SciPy for optimization
- Matplotlib for visualization

## 📊 Key Features

- Volatility calculation using logarithmic returns
- Portfolio optimization with constraints
- Sharpe ratio maximization
- Fixed-income security modeling
- Comprehensive credit risk assessment
- Financial statement analysis
