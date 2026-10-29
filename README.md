# Pharmaceutical Sales & Inventory Exploratory Data Analysis (EDA)

[![Portfolio Website](https://img.shields.io/badge/Portfolio%20Website-blue?style=for-the-badge)](https://emmanuel-azubuike.lovable.app)

## Executive Summary
This project bridges hands-on pharmacy operations intuition with data analytics. Analyzing **2,106 days** of daily pharmaceutical sales data across **8 major therapeutic categories (ATC classification)**, this exploratory data analysis (EDA) uncovers critical seasonal demand spikes and highlights key inventory holding risks to support smarter stocking decisions.

---

## Business Problem & Challenge
Pharmacy operations face two primary financial and supply chain hurdles:
1. **Stockouts on Fast Movers:** High-demand OTC medications run out quickly if safety stock isn't reliably calculated.
2. **Expiry & Holding Costs on Slow Movers:** Over-ordering slow-moving prescription lines ties up capital and creates near-expiry waste.

**Objective:** Use time-series sales patterns to identify seasonal demand peaks and establish data-backed inventory replenishment strategies.

---

## Dataset & Scope
- **Timeline:** 2,106 days of continuous daily sales activity.
- **Categories:** 8 WHO-Anatomical Therapeutic Chemical (ATC) classifications (including `M01AB`, `M01AE`, `N02BA`, `N02BE`, `R03`, `R06`, `N05C`).
- **Focus Areas:** Sales velocity, seasonality, holding-cost risks, and FEFO/expiration alignment.

---

## Key Insights & Operational Findings

- **Seasonal Demand Spikes:** **R03 respiratory medicines** roughly double in demand during winter months, providing a clear signal for pre-season stock build-up.
- **Fast Movers (Low Expiry Risk, High Stockout Risk):** OTC painkillers (**N02BE**) move consistently and rapidly, requiring tight replenishment cycles and strict safety stock thresholds.
- **Slow Movers (High Expiry Risk, High Holding Cost):** Prescription lines such as **N05C** exhibit slow movement patterns, creating holding-cost and expiry risk if over-ordered.

---

## Tech Stack & Tools Used
- **Language:** Python
- **Data Processing & EDA:** Pandas, NumPy
- **Visualization:** Matplotlib / Seaborn
- **Environment:** Jupyter Notebook

---

## Commercial & Operational Outcome
This project turns everyday pharmacy experience into clear, simple rules using numbers so the store always knows exactly what to reorder without wasting money.
