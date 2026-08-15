# ⚙️ Quantitative Core & Systematic Execution Framework
### Mathematical Edge | Statistical Arbitrage | Algorithmic Risk Controls

This document details the mathematical architecture, execution algorithms, and risk mitigation models deployed across Crystal Capital quantitative strategies.

---

## 📐 1. Core Quantitative Strategy & Edge

Crystal Capital eliminates emotional discretion, relying entirely on systematic statistical execution:

* **Mean Reversion & Order Flow Imbalance:** Capturing microstructural price discrepancies and mean-reversion behavior in highly liquid digital asset markets.
* **Zero-Forecast Principle:** Models do not attempt to predict macro trends; they exploit short-term volatility mispricings with positive mathematical expectation ($EV > 0$).
* **Execution Protocols:** Algorithmic routing via TWAP and VWAP limits to mitigate market impact and capture maker rebates across central and decentralized order books.

---

## 🛡 2. Institutional Risk Parameters

| Parameter | Limit / Policy | Implementation |
| :--- | :--- | :--- |
| **Max Risk Per Trade** | **0.5% – 1.0%** | Hard-coded sizing based on dynamic volatility metrics |
| **Max Open Drawdown** | **8.0% Hard-Cap** | Automatic execution freeze and liquidation to stablecoins |
| **Leverage Limit** | **1x – 3x (Conservative)** | Strict leverage ceiling to prevent liquidation risks |
| **Toxic Strategies** | **Strictly Prohibited** | Zero martingale, zero unhedged grid averaging |

---

## 🔐 3. Non-Custodial SMA Architecture

* **Client Control:** Capital remains under client-controlled accounts on supported venues (Bybit, Hyperliquid, BingX).
* **Trade-Only API:** Connection utilizes restricted API keys with disabled withdrawal and transfer permissions.
* **Separation of Risk:** Each pool operates independently to eliminate contagion across client accounts.

---
*© 2026 Crystal Capital Management. All rights reserved.*
