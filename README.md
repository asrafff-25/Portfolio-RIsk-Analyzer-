# Quantitative Portfolio Management & Risk Analytics Suite

An institutional-grade quantitative development framework designed to perform asset allocation, risk attribution, and trend decomposition across multi-sector equity universes. The suite constructs a 25-stock benchmark matrix (evenly split across Technology, Financials, Energy, Healthcare, and Consumer Staples) and assesses structural portfolio vulnerabilities using advanced parametric risk engines, Markowitz optimizations, and stochastic predictive modeling.

## 📊 8-Panel Diagnostic Dashboard Matrix

The framework generates a high-definition mathematical workspace (`portfolio_risk_dashboard.png`) breaking down performance metrics across eight distinct dimensions:

| **Cumulative Portfolio NAV & System Drawdowns** | Captures historical peak-to-trough wealth expansion paired with high-fidelity asset drawdowns |
| **Covariance-Based Volatility Contribution** | Maps risk attribution per asset relative to its raw capital weight using marginal risk algorithms |
| **System Intermarket Correlation Array** | Evaluates a $25 \times 25$ Pearson coefficient matrix configured to detect systemic sector clustering |
| **Allocation Divergence Profile** | Contrasts baseline capital allocations ($1/N$) against active volatility risk weight exposure |
| **Rolling Annualized Volatility Trajectory** | Measures dynamic 252-day historical standard deviation trends against inception averages |
| **Rolling Risk-Adjusted Efficiency Engine** | Measures continuous 252-day dynamic Sharpe ratio fluctuations over market cycles |
| **Markowitz Capital Optimization Frontier** | Simulates randomized multi-asset portfolios via vectorized algebraic engines to trace out efficient asset bounds |
| **Monte Carlo Simulation Horizon** | Projects 500 stochastic paths forward for a 1-year trading horizon using localized drift parameters |

## 🛠️ System Architecture & Mathematical Core

### 1. Risk Attribution Engine

The core framework avoids slow operational resource loops by deploying highly optimized matrix transformations:

**Portfolio Annualized Volatility:**

Annualized volatility (\(\sigma _{annual}\)) is calculated by multiplying the standard deviation of returns (σ) over a shorter period (like daily, weekly, or monthly) by the square root of the number of those periods in a year (T

**Component Risk Contribution:**
Component risk contribution measures the exact amount of risk (such as volatility or Value-at-Risk) that a single asset or position adds to an entire portfolio. It allows managers to break down portfolio risk into additive parts, where the sum of each component's risk equals the total portfolio risk.


### 2. Advanced Performance Analytics

Beyond basic measurements, the analytics engine tracks tail dependencies and downside asset profiles:

- **Sortino Ratio:** Substitutes standard deviation for downside semi-deviation to isolate malicious downside volatility
- **Calmar Ratio:** Contextualizes annual returns against absolute maximum portfolio drawdowns
- **Parametric Value at Risk (VaR) & Expected Shortfall (CVaR):** Pinpoints exact 95th-percentile historical boundaries and measures the structural mean expectation of losses beyond that boundary threshold

