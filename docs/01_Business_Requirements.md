# Business Questions

## Purpose

This document defines the key business questions that InsightForge aims to answer.

Each business question is assigned a unique ID. These IDs will later be referenced in SQL scripts, Python notebooks, dashboards, and reports to ensure every technical deliverable supports a specific business objective.

---

# Executive Questions

| ID | Business Question | Why It Matters | How We'll Answer It |
|----|-------------------|----------------|---------------------|
| EX-01 | Is the business growing over time? | Measure overall company growth. | SQL + Power BI trend analysis |
| EX-02 | Which product categories generate the highest revenue? | Identify the most profitable categories. | SQL aggregation + Dashboard |
| EX-03 | Which states and cities generate the most sales? | Decide where to expand marketing and operations. | SQL + Geographic visualization |
| EX-04 | Which sellers contribute the most revenue? | Identify top business partners. | SQL ranking + Seller dashboard |

---

# Customer Questions

| ID | Business Question | Why It Matters | How We'll Answer It |
|----|-------------------|----------------|---------------------|
| CU-01 | Who are our highest-value customers? | Focus retention efforts on high-value customers. | RFM Analysis + CLV |
| CU-02 | Which customers are likely to return? | Estimate customer loyalty. | Purchase frequency analysis |
| CU-03 | Which customers are at risk of churning? | Reduce customer loss. | Machine Learning Classification |
| CU-04 | How satisfied are customers? | Improve customer experience. | Review analysis |

---

# Sales Questions

| ID | Business Question | Why It Matters | How We'll Answer It |
|----|-------------------|----------------|---------------------|
| SA-01 | What are the monthly sales trends? | Understand seasonality and demand. | SQL + Time-series charts |
| SA-02 | Which products sell the most? | Improve inventory planning. | SQL ranking |
| SA-03 | Which products perform poorly? | Identify products for improvement or removal. | Sales comparison analysis |

---

# Operations Questions

| ID | Business Question | Why It Matters | How We'll Answer It |
|----|-------------------|----------------|---------------------|
| OP-01 | What is the average delivery time? | Measure logistics performance. | SQL date calculations |
| OP-02 | Which regions experience delivery delays? | Identify logistics bottlenecks. | Delivery analysis dashboard |
| OP-03 | Which sellers consistently deliver late? | Evaluate seller reliability. | Seller performance metrics |

---

# Finance Questions

| ID | Business Question | Why It Matters | How We'll Answer It |
|----|-------------------|----------------|---------------------|
| FI-01 | Which payment methods are most commonly used? | Understand customer payment preferences. | Payment analysis |
| FI-02 | What is the Average Order Value (AOV)? | Measure customer spending behavior. | Revenue ÷ Orders |

---

# Predictive Analytics Questions

| ID | Business Question | Why It Matters | How We'll Answer It |
|----|-------------------|----------------|---------------------|
| ML-01 | Can we forecast future sales? | Improve inventory and staffing decisions. | Time Series Forecasting |
| ML-02 | Can we segment customers? | Enable targeted marketing campaigns. | K-Means Clustering |
| ML-03 | Can we predict customer churn? | Improve customer retention. | Classification Model |
| ML-04 | Can we build a seller performance score? | Rank sellers using multiple performance metrics. | Composite KPI Model |