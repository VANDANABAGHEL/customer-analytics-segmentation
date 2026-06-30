# E-Commerce Customer Analytics & Machine Learning Segmentation Engine

An end-to-end data analytics and unsupervised machine learning project that processes over 500k raw transaction records from an international e-commerce retailer. This engine tracks customer behavioral decay over time through **Cohort Analysis** and segments the user base using **RFM Feature Engineering** combined with **K-Means Clustering**.

## Project Overview & Business Value
In e-commerce, generic marketing campaigns yield low conversion rates. This project solves that problem by:
1. Building a **Cohort Retention Matrix** to find exactly when and at what velocity customers stop returning.
2. Automating customer grouping using **Unsupervised Machine Learning** to build data-driven marketing personas (VIPs, Promising, and Churned).

## Tech Stack
- **Languages:** Python (Pandas, NumPy)
- **Machine Learning:** Scikit-Learn (K-Means Clustering)
- **Data Visualization:** Seaborn, Matplotlib

## Key Insights & Customer Personas

The finalized K-Means model successfully segmented 4,338 unique customer accounts into three highly actionable business personas:

| Cluster Label | Persona | Avg Recency | Avg Frequency | Avg Monetary | Customer Count | Marketing Strategy |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| **Cluster 0** | **Champions / VIPs** | 13.3 days | 13.0 orders | \$7,608.2 | 781 (18.0%) | Premium perks, zero-friction loyalty tiers, and early stock access. |
| **Cluster 2** | **New / Promising** | 53.5 days | 3.5 orders | \$1,364.6 | 1,695 (39.1%) | Cross-selling recommendation engines to increase purchase frequency. |
| **Cluster 1** | **At-Risk / Lost** | 161.3 days | 1.3 orders | \$339.5 | 1,862 (42.9%) | Automated, low-cost "Win-Back" email automation with steep discounts. |

---
*Developed during academic breaks as a student at IIT Jodhpur.*
