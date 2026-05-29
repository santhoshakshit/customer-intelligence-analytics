# Customer Intelligence & Growth Analytics Dashboard

<img width="901" height="505" alt="image" src="https://github.com/user-attachments/assets/f44fafcf-5e60-4b74-979e-fded28f55a71" />
<img width="908" height="510" alt="image" src="https://github.com/user-attachments/assets/2a1dce75-3f11-49cb-ab2d-36e0d82a6f67" />
<img width="906" height="510" alt="image" src="https://github.com/user-attachments/assets/470eb47f-6f39-436c-a648-98a1d0d032dc" />


## Problem Statement
An e-commerce company is spending heavily on customer acquisition but revenue 
is flat. The CEO wants to know — who are our best customers, who is about to 
leave, which products drive repeat purchases, and where are we losing people?

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data merging, cleaning, RFM computation |
| SQL (SQLite) | Business-focused customer behavior analysis |
| Power BI | 3-page interactive dashboard |
| PowerPoint | Executive insight presentation (5 slides) |

## Dataset
- Source: Olist Brazilian E-Commerce (Kaggle)
- Size: 96,478 delivered orders across 5 interconnected tables
- Tables: customers, orders, order_items, products, payments

## Headline Finding
**97% of customers never return after their first purchase.**
Yet repeat buyers generate 2x more revenue per customer.
Converting even 10% of one-time buyers = 150–180% revenue growth per converted customer.

## RFM Segments Identified

| Segment | Customers | Revenue | Avg Days Inactive | Priority |
|---------|-----------|---------|-------------------|---------|
| At Risk | 22,230 (23.8%) | R$3.7M (24.1%) | 395 days | URGENT |
| Loyal | 27,292 (29.2%) | R$3.7M (23.7%) | 144 days | MAINTAIN |
| Potential Loyalists | 16,044 (17.2%) | R$3.2M (20.9%) | 314 days | CONVERT |
| New Customers | 14,984 (16.1%) | R$2.4M (15.9%) | 91 days | NURTURE |
| Champions | 6,493 (7.0%) | R$2.0M (13.1%) | 91 days | REWARD |
| Lost | 6,315 (6.8%) | R$352K (2.3%) | 397 days | ACCEPT |

## Business Recommendations
1. **Win-Back At-Risk** — SMS/email campaign with 15% discount for 180+ day inactive customers
2. **Convert New Buyers** — Automated welcome series: Day 1, Day 7, Day 30
3. **Protect Champions** — VIP loyalty program + referral rewards

## Dashboard Structure
- Page 1 — Executive Overview (revenue trend, KPIs, payment methods)
- Page 2 — Customer Intelligence (RFM segments, treemap, priority matrix)
- Page 3 — Retention Strategy (revenue at risk, days inactive waterfall)

## Key Concepts Used
- RFM Segmentation (Recency, Frequency, Monetary — industry standard framework)
- Multi-table SQL joins across 5 datasets
- Delivery performance analysis (91.9% delivered early — 13.7 days before estimate)
- Customer lifetime value thinking — retention economics

---
*Built by Santhosh Akshit | CSE-AI, PBR VITS | June 2026*
