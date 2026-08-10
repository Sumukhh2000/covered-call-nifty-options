# Quantitative Analysis of Covered Call Strategy on NIFTY Options

A quantitative finance project developed during a Finance Internship at Ratio Ventures LLP, focused on designing, analysing and back-testing a covered call strategy using NIFTY 50 index options.

The project combines historical market analysis, Black-Scholes option pricing, Option Greeks, Geometric Brownian Motion, Monte Carlo simulation, Value at Risk, macroeconomic analysis, tail-risk hedging and strategy back-testing.

---

## Project Objectives

- Analyse NIFTY 50 price behaviour and historical volatility
- Apply Black-Scholes for theoretical option valuation
- Calculate and interpret Option Greeks
- Simulate NIFTY price paths using Geometric Brownian Motion
- Estimate downside risk using Monte Carlo simulation and VaR
- Analyse the relationship between NIFTY returns and macroeconomic variables
- Study lagged effects of macroeconomic variables on NIFTY
- Design and back-test a rule-based covered call strategy
- Evaluate tail-risk hedging using OTM puts
- Compare the strategy against a long NIFTY / buy-and-hold approach

---

## Methodology

The project followed a multi-stage quantitative framework:

1. Historical NIFTY price and return analysis
2. Geometric Brownian Motion simulation
3. Black-Scholes option pricing
4. Option Greeks analysis
5. Standard deviation and probability-range analysis
6. Monte Carlo simulation and Value at Risk
7. Large-move / gap analysis
8. Macroeconomic regression and lag analysis
9. Tail-risk hedging analysis
10. Covered call strategy formulation
11. Historical back-testing
12. Risk-return evaluation

The report states that the back-test used five years of NIFTY data and monthly rolling positions, with commission and slippage assumptions incorporated into the analysis.

---

## Black-Scholes & Option Greeks

Black-Scholes was applied using spot price, strike price, volatility, time to expiry, risk-free rate and dividend yield.

The project calculated:

- Delta
- Gamma
- Theta
- Vega
- Rho

These measures were used to understand option price sensitivity and support strike selection and hedging decisions.

---

## Back-Testing

The strategy was tested using five years of historical NIFTY data with monthly rolling positions.

Performance was evaluated using:

- Average return
- Volatility
- Sharpe ratio
- Maximum drawdown
- Hit rate
- Trade-level profitability
- Premium income

The report found that the covered call strategy delivered superior risk-adjusted performance compared with a pure buy-and-hold approach, while the tail hedge helped reduce drawdowns during major market stress periods.

---

## Project Files

- [Internship Report](Covered_Call_NIFTY_Options_Report.pdf)
- [Excel Analysis](Covered_Call_NIFTY_Options.xlsx)

---

## Tools & Technologies

- Microsoft Excel
- Black-Scholes Model
- Option Greeks
- Geometric Brownian Motion
- Monte Carlo Simulation
- Value at Risk
- Regression Analysis
- Historical Back-testing
- NIFTY 50 Market Data

---

## Limitations

The analysis recognises several limitations, including the constant-volatility assumption of Black-Scholes, normally distributed returns in Monte Carlo simulations, and assumptions around liquidity and execution.

These limitations are important when interpreting the strategy's historical performance and simulated risk estimates.
