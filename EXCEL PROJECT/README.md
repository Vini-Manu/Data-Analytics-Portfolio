# Perfume Retail Sales & Profitability Dashboard (Excel)

**Excel-based BI dashboard analyzing FY2024 retail performance across 5 UAE branches.**
Built during a Data Science & Analytics internship at BLUEKWET.

![Dashboard](./Perfume%20Retail%20Dashboard.png)

## Business Context

A UAE perfume retailer wanted visibility into where revenue and profit were actually coming
from across its branch network — by brand, region, payment method, and time of year — to
support pricing, stocking, and promotional decisions for 2025.

## Dataset

| | |
|---|---|
| **Volume** | ~392,800 transactions |
| **Period** | Jan – Dec 2024 |
| **Branches** | 5 (Nesto, Madeena, Safari, West Zone, Tilal) |
| **Regions** | Dubai Mainland, Premium Zone, Sharjah Side |

## Tools & Approach

- **Excel** — data cleaning and validation on the full transaction table
- **Pivot tables** — revenue and profit broken out by brand, branch, region, payment method, channel, and month
- **Formula-driven KPI layer** — every headline number recalculates live from the data, nothing hardcoded
- **Dashboard sheet** — KPI cards, pie/donut breakdowns, a monthly revenue/profit trend chart, ranked bar charts, and slicers for live filtering by branch, transaction type, and brand

## Key Findings

- **Total FY2024 net revenue: AED 108.6M**, at a consistently ~30.1% profit margin every month.
- **Card is the dominant payment method (55.0%** of revenue), ahead of Cash (25.1%) and Digital Wallet (19.9%).
- **International brands out-earn local brands 57:43** — Ajmal (AED 16.1M) is the top-earning brand.
- **In-store still drives ~90% of revenue**; online is only 10.1% — a clear digital growth opportunity.
- **Dubai Mainland accounts for ~80% of total revenue**, flagging geographic concentration risk.

## Contents

```
├── README.md
├── Perfume Retail Dashboard.png     ← the dashboard as built
└── Perfume_Sales_Analytics_2024 - PPT.pptx   ← full presentation deck
```

*Built by Vinitha Manoj — Data Science & Analytics Intern, BLUEKWET.*
