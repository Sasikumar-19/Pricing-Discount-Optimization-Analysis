# 📊 Pricing & Discount Optimization Analysis

> Analysed 1M+ retail transactions to identify optimal discount
> tiers, measure price elasticity per category, and validate
> findings with A/B testing — delivering a per-category pricing
> recommendation table for the CFO.

---

## 🔍 Project Overview

A retail company runs frequent discounts but lacks clarity on
whether discounting improves profitability or erodes margin.

This analysis answers: **at what discount % does margin turn
negative, and which categories actually respond to discounts?**

---

## 💡 Key Findings

| Metric | Value |
|---|---|
| Transactions analysed | 1M+ |
| Margin trap threshold | **2.8% discount** |
| Inelastic categories | **5 of 322** — avoid discounting |
| Highly elastic categories | **281** — priority discount targets |
| A/B test result | **0.000000 < 0.05** — statistically significant |
| Cohen's d (effect size) | **0.7686** ([Medium]) |

---

## 🛠️ Tools & Techniques

`Python` `pandas` `matplotlib` `seaborn` `scipy.stats`
`numpy` `SQLite` `Power BI` `Price Elasticity Modelling`
`A/B Testing` `Statistical Significance Testing`

---

## 📁 Project Structure

pricing-discount-project/
├── Pricing_Discount_Analysis.ipynb  ← Full analysis notebook
├── retail_cleaned.csv               ← Cleaned dataset
├── discount_tier_summary.csv        ← Revenue vs margin by tier
├── pricing_recommendations.csv      ← Per-category max discount
├── ab_test_results.csv              ← A/B test significance
├── pricing_dashboard_screenshot.png ← Power BI dashboard
└── README.md

---
## Dashboard
<img width="1285" height="725" alt="image" src="https://github.com/user-attachments/assets/9e9aabcf-24c0-4f95-bece-84011612804a" />

---

## 🔬 Methodology

### Step 1 — Business Framing
Defined the optimal discount question before touching data.

### Step 2 — Cleaning + Feature Engineering
Removed cancellations, negative quantities, zero prices.
Engineered: Revenue, Standard_Price, Discount_Pct,
Discount_Tier, Margin_Score from raw transaction data.

### Step 3 — Discount Impact Analysis (6 charts)
Showed revenue and margin diverge beyond 25%+ discount depth.

### Step 4 — Price Elasticity Modelling
Calculated per-category elasticity. 284 categories elastic,
8 inelastic. Built pricing recommendation table with
optimal max discount per category.

### Step 5 — A/B Test Simulation
Control = full price | Treatment = discounted.
t-test p-value = 0.000000. Cohen's d = 0.7686 ([Medium]).
Per-category tests identified [X] categories with significant lift.

### Step 6 — Dashboard 
Power BI dashboard with 7 visuals + recommendation table.
Along  with 3 actionable recommendations.

---

## 👤 About
Built by **AVALA NAGA VENKATA SASI KUMAR** | June 2026
🔗 https://www.linkedin.com/in/sasikumar19 | 📧 anvsasikumar19gmail.com
