# Customer Segmentation using RFM Model

**CRM Analytics Dashboard | Excel Portfolio Project**

> An end-to-end customer segmentation project built using the RFM (Recency · Frequency · Monetary) framework across a 100-customer dataset, delivered as a fully formatted Excel dashboard and a styled PDF recommendations report.

---

## Project Overview

This project applies the **RFM Model** — one of the most widely used frameworks in CRM and direct marketing analytics — to segment 100 customers into six behavioural groups. Each segment is profiled across recency of purchase, frequency of transactions, and monetary value, and mapped to targeted marketing and retention strategies.

The deliverable is a **production-ready Excel workbook** with 7 embedded charts, KPI cards, data tables, and strategic insight blocks, alongside a **multi-page PDF report** formatted to professional consulting standards.


| Attribute | Detail |
|---|---|
| Customers Analysed | 100 |
| Data Period | April 2024 – March 2025 |
| Analysis Date | 31 March 2025 |
| Segments | 6 (Champions → Lost Customers) |
| Deliverables | Excel Dashboard + PDF Report |
| Tools | Python, openpyxl, ReportLab |

---

## RFM Framework

| Metric | Definition | Scoring |
|---|---|---|
| **Recency (R)** | Days since last purchase | 1 (oldest) → 5 (most recent) |
| **Frequency (F)** | Total number of orders | 1 (lowest) → 5 (highest) |
| **Monetary (M)** | Total purchase value (INR) | 1 (lowest) → 5 (highest) |

**RFM Total Score = R + F + M** (range: 3 – 15)

### Segment Definitions

| Score Band | Segment | Description |
|---|---|---|
| 13 – 15 | **Champions** | Most recent, most frequent, highest spenders |
| 11 – 12 | **Loyal Customers** | Regular buyers with above-average spend |
| 9 – 10 | **Potential Loyalists** | Moderate engagement; convertible |
| 7 – 8 | **New Customers** | Recent but low frequency |
| 5 – 6 | **At-Risk** | Declining recency and frequency |
| 3 – 4 | **Lost Customers** | Long inactive, low engagement |

---

# Dashboard

<img width="1918" height="993" alt="P4 O S1" src="https://github.com/user-attachments/assets/0a016422-79ba-461f-bdb8-346a61f9171d" />
<img width="1918" height="990" alt="P4 O S2" src="https://github.com/user-attachments/assets/d8a51267-32fe-469c-aaf4-8421cf05fea8" />
<img width="1918" height="990" alt="P4 O S3" src="https://github.com/user-attachments/assets/0331caf3-9bd2-46e3-b1b6-8a9ac32989b0" />
<img width="1918" height="990" alt="P4 O S4" src="https://github.com/user-attachments/assets/cd4dc4b4-6b40-48e8-b01d-4a24306c1da7" />

---

## Repository Structure

```
rfm-customer-segmentation-excel/
│
├── dashboard/
|   ├── RFM_Customer_Segmentation_Dashboard.xlsx   # Excel dashboard
|                      
├── data/                     
│   ├── dataset.xlsx                               # Raw dataset of 100 customers
|
├── reports/
│   └── RFM_Recommendations_Report.pdf             # PDF of recommendations
│
├── screenshots/                                   # excel dashboard screenshots
│   └── dashboard 1.png
│   └── dashboard 2.png
│   └── dashboard 3.png
│   └── dashboard 4.png
|
└── README.md
```

---

## Excel Dashboard — Sheet Structure

The workbook contains **4 sheets**, opening on the Dashboard.

### 1. Dashboard *(opens by default)*
- **Title bar** with project name, analysis period, and customer count
- **5 KPI Cards** — Total Customers, Total Revenue, Champions, At-Risk, Loyal Customers
- **Segment Distribution Table** — customer count, revenue, and revenue % per segment
- **Revenue Contribution Table** — total revenue, % share, and avg spend per customer
- **7 Embedded Charts** (see chart section below)
- **6 Strategic Insight Blocks** — one per segment with recommended action
- **Footer** with project attribution

### 2. RFM Summary
- Segment-wise summary: count, revenue, avg RFM score, avg recency, avg orders, avg spend
- RFM Scoring Framework table mapping score bands to segments and recommended actions

### 3. Chart Source Data
- 7 clean source tables powering all embedded charts
- Structured with labelled headers and consistent formatting

### 4. Recommendations
- Strategic recommendation matrix: Segment → Priority → Strategy → Action Plan → Expected Outcome → Timeline → KPI → Budget Impact

---

## 7 Embedded Charts

| # | Chart Type | Data Shown |
|---|---|---|
| 1 | Clustered Column | Customer count by RFM segment |
| 2 | Horizontal Bar | Revenue contribution by segment |
| 3 | Pie (with % labels) | Loyalty status distribution |
| 4 | Clustered Column | Revenue by region |
| 5 | Pie (with % labels) | Customer age group distribution |
| 6 | Clustered Column | Average orders by segment |
| 7 | Pie (with % labels) | Gender split |

All charts are embedded directly in the Dashboard sheet with section banners and consistent brand colouring.

---

## PDF Recommendations Report

### Report Sections

| # | Section |
|---|---|
| 1 | Executive Summary |
| 2 | Key Findings (5 colour-coded finding tags) |
| 3 | Improvement Recommendations (priority table) |
| 4 | Segment Performance Summary |
| 5 | Methodology |
| 6 | Implementation Roadmap (4 phases) |
| 7 | Conclusion with outcome targets |

---

## Key Insights from the Analysis

- **Champions and Loyal Customers** together generate the majority of total revenue despite being a minority of the customer base — protecting this segment is the single highest-priority action
- **At-Risk customers** show measurable decline in recency and frequency — a targeted 20% re-engagement coupon campaign is recommended immediately
- **Lost Customers** represent recoverable revenue through social media awareness and win-back offers
- **Potential Loyalists** are the highest-opportunity conversion segment — a 3-purchase nurturing discount sequence is the recommended trigger
- **New Customers** require an onboarding journey (7-day email series) to drive a first repeat purchase within 30 days

---

## Implementation Roadmap

| Phase | Actions | Timeline | Expected Outcome |
|---|---|---|---|
| Phase 1 — Quick Wins | VIP programme for Champions; At-Risk re-engagement coupons | Q1 2025 | Retention +15%, Recovery +20% |
| Phase 2 — Nurturing | Onboarding for New Customers; nurture for Potential Loyalists | Q2 2025 | Conversion +25%, Repeat +15% |
| Phase 3 — Win-Back | Social media + comeback offer for Lost Customers | Q3 2025 | Win-back rate 25–30% |
| Phase 4 — Continuous Improvement | Monthly RFM recalculation; CLV prediction integration | Q4 2025 onwards | Sustained 80%+ engagement |

---

## Technologies Used

| Tool | Purpose |
|---|---|
| PDF generation with custom page templates |
| Excel | Data generation, Final dashboard generation and viewed in Excel |

---

## About

Built by: Debarati

---

*Customer Segmentation using RFM Model | Portfolio Project | June 2025*
