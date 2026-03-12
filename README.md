# mtc-sales-dashboard-tableau

Tableau dashboard and business report analysing 2023 sales performance for Mega Transportation Company (MTC) — a B2B vehicle company operating across five continents.

**Grade: 90%** | Macquarie University — BUSA1000 Introduction to Data, Analytics and People (S1 2024)

---

## Project Overview

Built a 9-visualisation Tableau dashboard to analyse MTC's full-year 2023 sales dataset, then delivered a 2,000-word executive report with data-driven recommendations for senior management. The brief simulated a real consulting engagement — analysing sales by product line, geography, customer, timing, and order status.

---

## Dataset

- **File:** `MTC_Dataset.xlsx`
- **Content:** MTC 2023 sales transactions — order details, product lines, customer info, country, deal size, order status, revenue
- **Scope:** Full-year 2023, B2B customers across the USA, Europe, Asia-Pacific, and Middle East

---

## Dashboard (Tableau)

**File:** `Dashboard_assignment.twbx`

9 visualisations covering:
- Monthly and quarterly sales trend line (with min/max annotations)
- Sales by country (geographic breakdown)
- Sales by product line (bar chart)
- Top 10 customers — Pareto chart with cumulative % line
- Customer heatmaps for top 2 clients (Euro Shopping Channel, Mini Gifts Distributors)
- Order status breakdown (shipped vs. in-process vs. cancelled vs. on-hold)
- Price distribution by deal size (boxplots — Small / Medium / Large)
- Sales volume vs. revenue correlation (scatter plot with regression line)
- Quarterly sales performance (bar chart)

---

## Key Findings

### Sales Performance
| Period | Revenue |
|--------|---------|
| Full Year 2023 | $8,291K |
| Q1 | $1,954K |
| Q2 | $1,702K |
| Q3 | $1,448K |
| Q4 | $3,187K ← peak |

Q4 more than doubled any single prior quarter — driven by year-end strategic sales activity and seasonal demand.

### Geography
| Country | Revenue |
|---------|---------|
| USA | $2,986K (top) |
| EMEA (combined) | ~$1,000K |
| Canada | $194K |
| Japan | $153K |

### Product Lines
| Product | Revenue |
|---------|---------|
| Classic Cars | $2,969K (top) |
| Vintage Cars | $1,644K |
| Motorcycles | $971K |
| Trucks & Buses | $947K |
| Planes | $878K |
| Ships | $678K |
| Trains | $204K |

### Customers
- **Euro Shopping Channel** — top client at $766K, primarily Classic Cars
- **Mini Gifts Distributors Ltd.** — second at $531K
- Top 2 clients account for ~16% of total annual revenue (Pareto concentration)

### Order Status
- **Shipped:** 92% of revenue ($7,651K) — strong logistics efficiency
- **Cancelled:** 2% ($171K) — opportunity for improvement
- **On-Hold / In-Process:** ~1% each

### Pricing
- Strong positive correlation between quantity ordered and revenue (linear regression)
- Outlier identified: product S18_3232 — $176K revenue at 1,774 units ordered (bulk discount or special promotion)
- Deal size pricing: Small (~$26.88 median/unit), Medium (~$84.52), Large (~$93.28)

---

## Recommendations

1. **Intensify Q4 marketing** — replicate the conditions driving the Q4 peak in earlier quarters to smooth revenue volatility
2. **Double down on Classic Cars and the USA market** — highest-performing product and geography
3. **Strengthen key account relationships** — Euro Shopping Channel and Mini Gifts Distributors warrant dedicated account management
4. **Reduce order cancellations and on-hold rates** — operational improvements in logistics and fulfilment could recover ~3% of lost revenue

---

## Files

```
mtc-sales-dashboard-tableau/
│
├── README.md
├── Dashboard_assignment.twbx       # Tableau packaged workbook (interactive dashboard)
├── BUSA_1000_report_assignment.docx # Full 2,000-word business report
└── MTC_Dataset.xlsx                # Raw 2023 sales dataset
```

---

## Tools

- **Tableau Desktop** — dashboard design, all 9 visualisations, interactivity
- **Microsoft Word** — business report with executive summary, analysis, recommendations
