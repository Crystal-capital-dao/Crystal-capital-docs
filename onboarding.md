# 🚀 Institutional Investor Onboarding Protocol
### Crystal Capital | Allocation Steps, SMA Configuration & Settlement

This guide details the step-by-step procedure for institutional allocators, Family Offices, and qualified partners to allocate capital across Crystal Capital Quantitative and RWA strategies.

---

## 📋 1. Onboarding Workflow

The capital allocation process follows a structured four-stage cycle:

[ Stage 1: Due Diligence ] ➔ [ Stage 2: Mandate & KYC ] ➔ [ Stage 3: Account Setup / Allocation ] ➔ [ Stage 4: Execution & Settlement ]

1. **Strategy Alignment & Review:** Initial discussion with the investment committee to select the target strategy (Systematic Quantitative Core or RWA Infrastructure).
2. **KYC/AML & Documentation:** Verification of corporate/accredited status and execution of the Investment Mandate / Master Service Agreement (MSA).
3. **Account Provisioning:** Configuration of direct exchange sub-accounts or smart-contract whitelisting.
4. **Active Management & Reporting:** Continuous systematic execution with real-time performance reporting.

---

## 🔑 2. SMA (Separately Managed Account) Setup Guide

For algorithmic quant execution, capital remains under direct client ownership:

* **Supported Exchanges:** Bybit, Hyperliquid, BingX.
* **API Key Permissions:**
  * ✅ **Enable:** Read-Only / Position Information.
  * ✅ **Enable:** Spot / Derivatives Trading (`Trade-Only`).
  * ❌ **Disable:** Withdrawals (API withdrawal access must remain strictly unchecked).
  * ❌ **Disable:** Internal Asset Transfers.
* **IP Whitelisting:** Bind the API connection to dedicated Crystal Capital execution server IP addresses provided during onboarding.

---

## 💼 3. Fee Structure & Settlement Terms

| Component | Quantitative Core (SMA) | RWA Division (cFUNGI) |
| :--- | :--- | :--- |
| **Management Fee** | **0% – 1.5%** *(Tiered by AUM)* | **0%** |
| **Performance Fee** | **20% – 30%** *(High-Water Mark)* | **Waterfall Model (80/20 ➔ 50/50)** |
| **Lock-Up Period** | **0 Days (Instant Liquidity)** | **Development & Harvest Cycle** |
| **Reporting Cycle** | **Real-Time / Monthly Statement** | **Quarterly Operational Statements** |

---

## 📬 4. Contact Investment Relations

To initiate the onboarding process or request formal DD documentation:

* **Headquarters:** Dubai, United Arab Emirates
* **Direct Channel:** Contact Investment Committee via official DAO channels
* **Documentation Portal:** [Crystal Capital Institutional Docs](README.md)

---
*© 2026 Crystal Capital Management. All rights reserved.*
