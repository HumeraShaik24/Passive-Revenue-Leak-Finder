# 🚀 Passive Revenue Leak Finder
*A Data-Driven Expedition to Uncover Hidden Financial Leaks*

## 🧐 The Challenge
In a fast-paced business environment, revenue can silently slip through the cracks.  
This project performs a **deep-dive analysis** of a company's transaction data to **identify and quantify passive revenue leaks**.  
By pinpointing the **source, scale, and location** of these leaks, we provide actionable recommendations to **stop financial losses and boost profitability**.

---

## 📊 The Data
We analyzed the `passive_revenue_leak_finder_6000.csv` dataset, containing detailed transaction records, including:

- **Transaction ID** – Unique identifier for each transaction
- **Order Details** – Product information, quantity, and pricing
- **Financials** – `unit_price`, `cost_price`, `discount_percent`, `shipping_fee`
- **Anomalies** – `refund_flag` and `anomaly_type` to flag potential issues

---

## 🔍 Key Discoveries: The Leaks
Our Python-powered analysis and data visualizations revealed **three major sources** of revenue leakage:

### 1️⃣ Refunds – *The Gushing Torrent*
- **Total Leak:** ₹1,010,681.00 (98.4% of total losses)
- **Culprit:** Electronics category, responsible for **72% of all refund losses**

### 2️⃣ Below-Cost Sales – *The Silent Drip*
- **Total Leak:** ₹14,003.00
- **Cause:** Products sold for less than cost due to excessive discounting
- **Hotspots:** Electronics & Sports categories

### 3️⃣ Free Shipping Errors – *The Systemic Sieve*
- **Total Leak:** ₹1,621.00
- **Observation:** Widespread issue linked to `free_shipping_error` anomaly type

---

## 📈 Visual Insights
- **Heatmap:** Total revenue leaks by category & city — Red hotspots in **Hyderabad & Delhi**, especially in Electronics.
- **Bar Chart:** Total revenue leaks by city — Highlights the biggest contributors.

---

## 🛠️ Actionable Recommendations
Based on the findings, we propose the following **five-point recovery plan**:

1. **🎯 Refine Refund Policies**  
   Investigate high refund rates in Electronics for Hyderabad & Delhi to uncover root causes.

2. **🛡️ Implement Pricing Guardrails**  
   Automate checks to prevent discounts from pushing the net price below cost.

3. **📦 Audit Logistics Systems**  
   Fix free shipping errors by auditing the order management system.

4. **🏙️ Targeted City Initiatives**  
   Launch recovery programs in high-loss cities.

5. **🚨 Proactive Anomaly Monitoring**  
   Implement a real-time alerting system for leak detection.

---

## 💡 Outcome
This project identifies a **₹1,026,305.99** financial recovery opportunity and provides a **clear, data-backed roadmap** for a more **profitable and resilient business**.
