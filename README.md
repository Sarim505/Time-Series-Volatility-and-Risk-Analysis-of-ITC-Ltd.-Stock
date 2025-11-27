# Time-Series-Volatility-and-Risk-Analysis-of-ITC-Ltd.-Stock
Here’s a **concise and professional project document** you can use as a report section or GitHub/portfolio summary 👇

---

## **Project Title:**

**Time Series Volatility and Risk Analysis of ITC Ltd. Stock**

---

### **Objective**

The primary objective of this project is to **analyze and forecast the volatility and downside risk** associated with ITC Ltd.’s stock using advanced **time series and econometric techniques**.
The study focuses on identifying the **nature of price fluctuations**, measuring **market risk**, and estimating the **potential losses** under both normal and stressed market conditions.

---

### **Methodology**

1. **Data Preparation:** Collected historical ITC stock prices and calculated daily log returns.
2. **Stationarity Testing:** Applied the Augmented Dickey–Fuller (ADF) test to examine price and return stationarity.
3. **Volatility Modeling:** Fitted a **GARCH(1,1)** model to capture volatility clustering in returns.
4. **Forecasting:** Predicted short-term volatility for 5 trading days ahead.
5. **Risk Measurement:**

   * **Value-at-Risk (VaR)** calculated at 95% and 99% confidence levels.
   * **Stress Test** simulated a 5σ extreme event to assess tail risk.

---

### **Key Results**

* **Forecasted Volatility:** Slightly increasing trend, indicating moderate near-term uncertainty.
* **95% VaR:** -2.88% → 5% chance of daily loss exceeding this level.
* **99% VaR:** -4.07% → 1% chance of daily loss exceeding this level.
* **Stress Test (5σ Event):** Potential loss up to **-8.75%** under extreme conditions.

---

### **Applications**

* **Financial Risk Management:** Quantifies potential portfolio losses under normal and stressed scenarios.
* **Investment Decision-Making:** Helps assess volatility persistence and short-term risk exposure.
* **Market Analysis:** Supports risk-based portfolio allocation and trading strategy evaluation.
* **Corporate Finance:** Demonstrates how financial institutions use econometric models for capital adequacy and stress testing.

---

### **Challenges and Problems with Financial Time-Series Data**
High Noise and Randomness: Financial returns are heavily influenced by random market factors and exhibit low signal-to-noise ratio, complicating accurate predictive modeling.

Non-Stationarity: Price series are typically non-stationary, requiring transformations (usually returns or differencing) before modeling to ensure reliable statistical inference.

Volatility Clustering and Heteroscedasticity: Returns tend to show volatility clustering, where periods of high and low volatility alternate, necessitating models like GARCH in addition to SARIMA.

Structural Breaks and Market Regime Changes: Sudden market shifts or external shocks can affect model stability and reduce forecasting reliability.

Limited Predictability: Due to efficient market hypothesis, financial markets often behave near-randomly, limiting the achievable accuracy of any model.
--
