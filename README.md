# Stock Market Index Trading Strategies with ARIMA+GARCH Model
## Abstract
This report aim as modeling stock index time series by ARIMA, GARCH and multivariate models. The R code is attachded at the appendix of the report. 

## Sections
1.	INTRODUCTION	3
1.1	Introduction to Index Investing	3
1.2	Motivation	4
2.	EXPLORATORY DATA ANALYSIS	5
2.1	Data-at-a-glance	5
2.2	Data Cleaning	6
2.3	Unit Root Test: Dickey-Fuller Test	6
2.4	Serial Correlation Checking: Ljung–Box test	7
2.5	ARCH Effect Detection: Ljung–Box test	8
2.6	Cointegration Test: Johansen Test	8
3.	MODEL FITTING AND VALIDATION	9
3.1	Univariate ARIMA Model	9
3.1.1 Hang Seng Index	9
3.1.2 S&P 500	9
3.1.3 FTSE100	10
3.1.5 Conclusion	11
3.2	ARIMA-GARCH Model	12
3.2.1 Hang Seng Index	12
3.2.2 S&P 500 Index	13
3.2.3 FTSE 100 Index	13
3.2.4 SSE Index	14
3.3	Multivariate Autoregressive Moving Average (ARMA) Models	15
3.3.1 Vector Autoregressive (VAR) Model	15
3.3.2 Vector Moving Average (VMA) model	18
3.3.3 Vector-Autoregressive Moving Average (VARMA) Model	21
3.3.4 Model Summary	23
3.4	Multivariate GARCH Model – BEKK	23
4.	TRADING STRATEGIES AND BACKTESTING RESULT	24
4.1	Implementation of the strategy	24
4.2	Back-testing Result –S&P 500 Index	25
5.	DISCUSSION	26
5.1	Data Limitation	26
5.2	Model Limitation	26
6.	CONCLUSION	27
Reference	28
Appendix	30# HKUST-MSBD-5006-Quantitative-Analysis-of-Financial-Time-Series
