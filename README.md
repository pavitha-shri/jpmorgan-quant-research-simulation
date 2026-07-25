# J.P. Morgan Quantitative Research Virtual Experience Simulation

## 📌 Project Overview
This repository contains my solutions and quantitative models developed during the **J.P. Morgan Quantitative Research Virtual Experience Program** (Completed July 2026). The simulation involved solving real-world financial engineering and risk analytics problems across energy commodities and credit risk.

---

## 🛠️ Detailed Task Breakdown

### Task 1: Commodity Price Analysis & Seasonality Modeling
* **Objective:** Clean historical natural gas price data and build a predictive model to estimate prices at future dates.
* **Methodology:**
  * Cleaned time-series data and formatted datetime elements.
  * Extracted seasonal trends, natural gas injection/withdrawal cycles, and long-term price drift.
  * Implemented an extrapolation function in Python to interpolate prices for arbitrary future contract dates.

### Task 2: Valuation of Natural Gas Storage Contracts (NPV Pricing Model)
* **Objective:** Build a prototype pricing model to evaluate the Net Present Value (NPV) of natural gas storage contracts.
* **Methodology:**
  * Designed a Python function taking input parameters: injection dates/rates, withdrawal dates/rates, storage capacity, and storage holding costs.
  * Calculated cash flows based on price differentials between injection (buying) and withdrawal (selling) periods.
  * Incorporated operational constraints and discounted cash flows to calculate net contract value.

### Task 3: Credit Risk Modeling & Probability of Default (PD)
* **Objective:** Estimate borrower credit risk and total expected financial loss on a loan portfolio.
* **Methodology:**
  * Analyzed borrower historical financial metrics to predict default likelihood.
  * Built a logistic/statistical model in Python to calculate individual Probability of Default (PD).
  * Calculated Expected Loss (EL) using the core formula:
    $$\text{Expected Loss (EL)} = \text{PD} \times \text{LGD} \times \text{EAD}$$
    where Exposure at Default (EAD) and Loss Given Default (LGD) were factored into portfolio loss estimates.

### Task 4: Credit Score Bucketing via Dynamic Programming
* **Objective:** Optimize FICO score rating maps to convert continuous credit scores into discrete risk buckets.
* **Methodology:**
  * Implemented a Dynamic Programming algorithm in Python to find optimal bucket boundaries.
  * Maximized log-likelihood / minimized loss to ensure score buckets accurately reflected borrower default probability profiles.

---

## 💻 Technical Stack & Concepts
* **Language:** Python
* **Data & Math Libraries:** Pandas, NumPy, Scipy
* **Financial & Math Concepts:** Time-Series Interpolation, Net Present Value (NPV), Probability of Default (PD), Dynamic Programming, Expected Loss Estimation

---

## 📜 Certification
* Issued by **J.P. Morgan** (July 2026)
