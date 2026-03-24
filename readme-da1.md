# DA Project 1 — Unlocking Customer Value Through RFM Segmentation

## Problem Statement
Online retail businesses often spend their marketing budget evenly across all customers without understanding who is actually valuable. Loyal customers receive no special treatment, while inactive customers continue to be funded by wasteful campaigns.

## What We Did
Performed in-depth exploratory data analysis (EDA) on the UCI Online Retail dataset, then calculated RFM scores per customer. Each customer was given a score of 1–5 for Recency, Frequency, and Monetary value — then grouped into 4 strategic segments and visualized in an interactive Power BI dashboard.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Power BI (Dashboard)
- Jupyter Notebook / Google Colab

## Dataset
- **Source:** UCI Online Retail Dataset
- **Size:** 541,909 transactions

## Key Results
| Metric | Value |
|--------|-------|
| Customer Segments | 4 |
| Dataset Size | 541,909 rows |
| Dashboard | Power BI |

## RFM Segments
| Segment | Recency | Frequency | Monetary | Action |
|---------|---------|-----------|----------|--------|
| Champions | Very Recent | Very High | Very High | Reward & retain |
| Loyal | Recent | High | High | Upsell offers |
| At Risk | Not Recent | Medium | Medium | Re-engagement |
| Lost | Long Ago | Low | Low | Win-back or drop |

## So What? — Actionable Insights

**1. Reactivate Lapsing / Inactive Customers**
Send a time-limited reactivation message (email or push notification) offering a simple incentive such as free shipping or a small discount (10%).
> *Why it works: Urgency lowers the barrier to return and encourages customers to re-engage with minimal marketing cost.*

**2. Build Loyalty (Primary Focus)**
Introduce a basic loyalty mechanism — member card or points system — where customers earn points after each purchase. Points can be collected and exchanged for gifts.
> *Why it works: Creates a reason to return, shifting behavior from one-time purchases to repeat buying.*

**3. Increase Spending (Primary Focus)**
Offer bundle deals (e.g., phone case + charger at a discounted price) or add-on discounts at checkout. Send email whenever promotions are created.
> *Why it works: Bundling increases basket size without requiring additional customer acquisition.*

## Author
**Anthony Djiady Djie** — DS39+ Dibimbing.id
[ADJ Business Consulting](https://adjbusinessconsulting.github.io/adj-consulting)
