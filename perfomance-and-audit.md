# 📈 Quantitative Performance & Risk Analytics Framework
### Crystal Capital Systematic Core | Verification & Audit Protocol

This document outlines the performance evaluation methodology, institutional risk management metrics, and capital allocation transparency standards of Crystal Capital.

---

## 🎯 1. Key Performance Indicators (KPI Architecture)

Capital management is engineered around statistical edge and strict tail-risk mitigation, eliminating discretionary execution.

| Metric | Target Benchmark | Methodology / Purpose |
| :--- | :--- | :--- |
| **Target Net APY** | **35% – 60%+** | Net annualized return post-performance fees |
| **Max Drawdown (Hard-Cap)** | **< 8.0%** | Hard-coded stop-loss execution at the API/contract layer |
| **Sharpe Ratio** | **> 2.2** | Risk-adjusted return relative to portfolio volatility |
| **Sortino Ratio** | **> 3.1** | Risk-adjusted return evaluated solely against downside volatility |
| **Profit Factor** | **> 1.85** | Ratio of gross profits relative to gross losses |
| **Win Rate** | **52% – 68%** | Ratio of profitable statistical iterations |

---

## 🛡 2. Institutional Risk Framework

### 2.1. Per-Trade Risk Cap
* Single-trade exposure is strictly limited to **0.5% – 1.0%** of total pool equity.
* Strict prohibition of toxic position scaling: zero martingale strategies, zero reckless grid averaging, and zero uncontrolled leverage.

### 2.2. Drawdown Control Hierarchy (Waterfall Protection)
* **Soft Warning (-3.0%):** 50% algorithmic position scaling reduction; enhanced liquidity filtering activated.
* **Capital Halt (-5.0%):** Immediate position de-risking into stablecoins (USDT/USDC); volatility anomaly audit initialized.
* **Emergency Hard-Stop (-8.0%):** Automated API session revocation and complete execution freeze pending Risk Committee manual review.

---

## 📊 3. Execution & Custody Architecture

* **Non-Custodial SMA Model:** Investor assets remain in the client's direct sub-accounts (Bybit, Hyperliquid, BingX) via strictly defined `Trade-Only API` permissions (withdrawal rights restricted).
* **Slippage & Execution Engine:** Limit order routing protocols (TWAP/VWAP) to minimize slippage and transaction costs across order books.
* **On-Chain Settlement:** Performance tracking and high-water mark fee distributions are recorded transparently.

---
*© 2026 Crystal Capital Management. All rights reserved.*
