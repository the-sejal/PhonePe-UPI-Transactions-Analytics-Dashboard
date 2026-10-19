# 💳 PhonePe UPI Transactions Analytics Dashboard (Excel MIS Project)

An end-to-end Management Information Systems (MIS) and data analytics project built entirely in **Microsoft Excel**. This dashboard transforms massive, row-level digital payment logs into clean, visual business reports. It provides real-time operational visibility for digital wallet networks, merchant banks, and compliance teams to track app market share, detect payment failure hotspots, and monitor risk vectors.

---

## 🛑 Business Problem Statement

Fintech ecosystems handle hundreds of thousands of concurrent Unified Payments Interface (UPI) transactions daily across various apps, banks, states, and merchant types. Without a centralized MIS dashboard, operations teams face serious daily bottlenecks:
* **Reactive Fraud Identification:** Delayed visibility into high-risk transaction clusters leads to increased exposure to digital fraud and financial loss.
* **Network Failures & Unstable Success Rates:** Lacking clear tracking across individual banking rails prevents technical teams from predicting bank server drops, leading to transaction failure spikes.
* **Vague Consumer Profiling:** Product teams struggle to understand transaction trends without granular data showing exactly how and when users spend money (e.g., P2M shopping vs. P2P transfers).

**Project Objective:** Build a high-performance Excel dashboard to process UPI payment records, track operational KPIs, map transaction velocity, and analyze market share dynamics to improve system success rates and secure digital assets.

---

## 📋 MIS Report System & Dashboard Requirements

The data architecture handles a comprehensive set of performance trackers, organized into two core phases:

### Phase 1: Operational KPI Requirements
1. **Total Transactions:** Monitors the overall count of payments running through the portfolio to evaluate system load.
2. **Total Amount (INR):** Aggregates the total monetary throughput running across the network.
3. **Total Cashback (INR):** Tracks the total promotional incentive capital distributed to users.
4. **Success Rate:** Measures system efficiency by calculating the percentage of successfully cleared transactions against failures.
5. **Suspected Fraud:** Isolates and counts transactions flagged by compliance filters for immediate review.

### Phase 2: Core Analytical Visuals
1. **Transaction Amount Over Time (Daily):** A line chart tracking daily transaction value waves to forecast monthly cash-flow trends.
2. **Transaction by UPI App:** A donut chart illustrating market share distribution across different consumer digital wallets.
3. **Transaction by Status:** A donut chart mapping the final state of all orders (Success, Failed, Pending, Refunded) to track system errors.
4. **Transaction Amount by State:** A regional map graphic highlighting geographical spending hotspots.
5. **Transaction Amount by Bank:** A horizontal bar chart tracking throughput performance across specific banking clearing rails.
6. **Transaction Amount by Transaction Type:** A horizontal bar chart showing customer transaction intent (P2M, P2P, Bill Payments, etc.).
7. **Transaction Amount by Hour & Day:** A time-series distribution mapping transaction velocity across hourly and daily matrices to isolate peak server stress hours.

---

## 💵 Macro Financial & Portfolio Baselines

By aggregating and cleaning the transaction log data points, the Excel engine establishes a clear performance baseline:
* **Total Network Volume:** **5,02,887 total transactions** successfully processed.
* **Aggregate Value Throughput:** Total transaction value balances at **₹44.25 Crores**.
* **Incentive Capital Dispersal:** **₹34.63 Lakhs** distributed in promotional user cashbacks.
* **System Efficiency Rating:** The pipeline holds a **91.00% Success Rate** (with 7.0% failed, 2.0% pending, and 0.0% refunded).
* **Risk Tracking Vector:** Flags **17,089 suspected fraud cases** for advanced lookup.

---

## 📈 Deep Operational Insights

### 🔄 1. Payment App Market Share & Bank Performance
* **Fintech App Dominance:** PhonePe rules the digital landscape, capturing **49.8% of the total transaction value**. Google Pay takes the secondary baseline at **21.3%**, with Paytm tracking at **14.3%**, and Amazon Pay checking in at **4.9%**.
* **Banking Rails Throughput:** Financial volume clears smoothly through premium banking routes. **HDFC Bank logs the highest total volume at ₹5.89 Crores**, with State Bank of India (SBI) right behind at **₹5.84 Crores**, and Kotak Mahindra Bank stable at **₹5.58 Crores**. Canara Bank, ICICI Bank, and Axis Bank track closely between ₹5.52 Cr and ₹5.49 Cr.

### 🗺️ 2. Regional Layouts & Transaction Intent
* **Geographical Hotspots:** **Maharashtra leads absolute regional volume at ₹4.54 Crores**, followed closely by Karnataka (₹4.51 Cr), Delhi (₹4.48 Cr), and Rajasthan (₹4.42 Cr). 
* **Transaction Intent Vectors:** **Peer-to-Merchant (P2M) payments drive the entire ecosystem, accounting for ₹13.88 Crores** in user spending. Peer-to-Peer (P2P) transfers hold second place at **₹8.77 Crores**, while regular Bill Payments add a structural **₹6.17 Crores**.

### ⏰ 3. Time-Series Bottleneck Drift
* **Daily Wave Fluctuations:** Daily transaction value displays cyclical fluctuations over the month, remaining range-bound between **₹1.36 Crore and ₹1.48 Crore per day**, with systemic peaks building around the 5th and 14th calendar markers.
* **Hourly Traffic Spikes:** The hourly transaction velocity follows a clear **bimodal (two-peak) distribution**. A minor peak occurs during standard morning startup hours (9:00 AM - 11:00 AM), while the absolute **primary daily peak builds heavily in the evening between 6:00 PM and 8:00 PM**, reflecting peak post-work commerce window transactions.

---![Dashboard Snapshot]()


## 🛠️ Tech Stack & MIS Skills Applied
* **Tool:** Microsoft Excel (Pivot Tables, Advanced Formulas, Cross-Report Slicers, Visual Formatting).
* **MIS Domain Skills:** Digital payment analytics, transaction success diagnostics, market share tracking, time-series fraud mapping, geo-spatial financial reporting.
