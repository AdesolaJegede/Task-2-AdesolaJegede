# Excel Exploratory Data Analysis — Orders Dataset
### Week 2 | Decode Lab Internship

## Project Overview
Exploratory Data Analysis performed on a cleaned 1,200-row
orders dataset using Microsoft Excel PivotTables, charts and
descriptive statistics. The goal was to identify patterns,
trends, distributions and outliers within the data.

**Tool:** Microsoft Excel
**Dataset:** 1,200 rows · 14 columns · Jan 2023 – Jun 2025
**Internship:** Decode Lab | Training: TS Academy

---

## Objectives
- Calculate basic statistics (mean, median, count, min, max)
- Identify trends and patterns across products, channels
  and time periods
- Summarise key business insights from the data

---

## Basic Statistics

| Metric | Value |
|---|---|
| Total Revenue | $1,264,761.96 |
| Total Orders | 1,200 |
| Total Quantity | 3,535 |
| Mean Order Value | $1,053.97 |
| Median Order Value | $823.62 |
| Max Order Value | $3,456.40 |
| Min Order Value | $11.39 |
| Mean Unit Price | $356.00 |

> Mean ($1,053.97) > Median ($823.62) confirms a
> right-skewed distribution driven by high-value bulk orders

---

## Analysis & Key Findings

### 1. Product Sales Performance
| Product | Orders | Total Revenue |
|---|---|---|
| Chair | 178 | $195,620.11 |
| Printer | 181 | $195,612.61 |
| Laptop | 173 | $192,126.56 |
| Tablet | 179 | $186,568.95 |
| Monitor | 163 | $175,651.41 |
| Desk | 170 | $167,459.93 |
| Phone | 156 | $151,722.39 |

**Observation:** Revenue is remarkably even across all 7
products. No single product dominates the business.

---

### 2. Order Status Distribution
| Status | Count | Percentage |
|---|---|---|
| Cancelled | 250 | 20.83% |
| Returned | 247 | 20.58% |
| Pending | 237 | 19.75% |
| Shipped | 235 | 19.58% |
| Delivered | 231 | 19.25% |

**Observation:** Only 19.25% of orders were successfully
delivered. A combined 41.4% were cancelled or returned —
the most significant operational concern in the dataset.

---

### 3. Revenue by Payment Method
| Payment Method | Orders | Total Revenue |
|---|---|---|
| Online | 258 | $262,442.94 |
| Credit Card | 234 | $263,847.63 |
| Cash | 246 | $259,786.29 |
| Gift Card | 230 | $246,323.92 |
| Debit Card | 232 | $232,361.18 |

**Observation:** Payment methods are uniformly distributed
at approximately 20% each — no dominant payment preference.

---

### 4. Sales by Referral Source
| Source | Orders |
|---|---|
| Instagram | 259 |
| Email | 250 |
| Google | 241 |
| Facebook | 228 |
| Referral | 222 |

**Observation:** Instagram leads but all channels are within
a 37-order range — a well-diversified marketing mix.

---

### 5. Coupon Usage Analysis
| Coupon | Orders | Avg Order Value |
|---|---|---|
| FREESHIP | 313 | $1,070.41 |
| No Coupon | 309 | $1,043.37 |
| WINTER15 | 292 | $1,035.90 |
| SAVE10 | 286 | $1,065.87 |

**Observation:** Minimal difference in avg order value
between coupon and non-coupon orders — coupons drive
volume more than they increase order value.

---

### 6. Revenue Trend
| Year | Orders | Total Revenue |
|---|---|---|
| 2023 | 510 | $552,643.24 |
| 2024 | 459 | $480,235.87 |
| 2025 (6 months) | 231 | $231,882.85 |

**Observation:** Revenue declined ~13% from 2023 to 2024.
Peak month was June 2024 ($68K). 2025 is trending upward.

---

## Tools & Techniques Used
- PivotTables for grouping and aggregation
- Descriptive statistics using AVERAGE, MEDIAN, MAX,
  MIN, COUNT, STDEV functions
- Bar charts, donut charts and line charts for visualisation
- Conditional formatting for pattern highlighting

---

## Next Steps
EDA findings replicated and validated using:
- Week 3: SQL Analysis in SQL Server
- Week 4: Power BI Dashboard

---

## Author
**Adesola Jegede**
Data Analytics Intern — Decode Lab
Student — TS Academy
🔗 [LinkedIn]([https://www.linkedin.com/in/your-linkedin-url](https://www.linkedin.com/in/jegede-adesola-562398244))
