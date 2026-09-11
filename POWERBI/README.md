# Restaurant Performance Dashboard (Power BI)

**Interactive Power BI report analyzing a full month of restaurant transactions across 3 Dubai branches.**
Built during a Data Science & Analytics internship at BLUEKWET (September 2025).

## Business Context

Restaurant leadership wanted a single, filterable view of how the business performed in a
month — across branches, order channels, payment methods, and menu items — to guide
staffing, menu, and channel-investment decisions.

## Dataset

| | |
|---|---|
| **Volume** | 3,600 orders / 8,622 covers |
| **Period** | September 2025 (30 days) |
| **Branches** | 3 (Jumeirah, Deira, Downtown Dubai) |
| **Menu items** | 10 |
| **Model** | Star schema — 1 fact table (Orders) + 5 dimension tables |

## Tools & Approach

- **Power BI** — relational data model with 6 tables and defined relationships (star schema)
- **DAX** — 13 measures covering totals, averages, rankings, and time intelligence
- **Report design** — a single interactive page: 4 KPI cards, 6 charts, and 3 slicers (Branch, Channel, Date)

## Key Findings

- **Total net sales: AED 295.9K** across 3,600 orders — average spend of AED 34.32 per cover.
- **Branches run neck-and-neck** — Jumeirah (AED 100.6K), Deira (AED 98.2K), and Downtown Dubai (AED 97.1K).
- **No single channel dominates** — Dine-In leads at 36%, Delivery 34%, Takeaway 31%.
- **Digital payments have taken over** — Card, Wallet, and Online together make up ~78% of sales.
- **Mixed Grill is the standout dish** — AED 66,105 in revenue, ~24% of item-level sales.
- **A clear double-peak trading day** — surge at 10–11 AM, then steady through a 6–10 PM dinner window.

## Contents

```
├── README.md
├── Restaurant_Daily_Sales_Transaction_Analysis.pbix   ← the live Power BI file
└── Restaurant_Dashboard_Presentation.pptx             ← full case-study deck
```

*Built by Vinitha Manoj — Data Science & Analytics Intern, BLUEKWET.*
