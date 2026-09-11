# Student Enrollment & Revenue Analysis (Tableau)

**Interactive Tableau dashboard analyzing a full year of student enrollments across 6 UAE branches.**
Built during a Data Science & Analytics internship at BLUEKWET (2024 data).

## Business Context

Leadership needed one view tying together enrollments, fee collection, and course/branch
performance — to see where revenue was concentrated and how much was still outstanding.

## Dataset

| | |
|---|---|
| **Volume** | 2,000 student enrollment records |
| **Period** | Full year 2024 |
| **Branches** | 6 UAE branches |
| **Course categories** | 12 |
| **Instructors** | 15 |
| **Nationalities** | 10 |

## Tools & Approach

- **Tableau** — single enrollment extract, calculated fields for Outstanding Fees and Collection Rate
- **10-worksheet dashboard** with a bento-grid layout — KPI cards, trend line, and bar charts, each tied to the extract
- **Bento-grid design** — iterative XML editing to achieve a non-scrolling, tightly aligned layout

## Key Findings

- **AED 13.9M in total course fees**, with AED 9.14M collected — a **65.7% collection rate**.
- **AED 4.78M still outstanding** — split almost evenly between Ongoing and Cleared status.
- **Completion rate sits at 49.7%** — just under half of enrolled students have completed their course.
- **ERP and IT Security lead the category mix** — together over AED 2.7M of the AED 9.14M collected.
- **All six branches contribute a close, even share** — Abu Dhabi leads narrowly at AED 1.65M.
- **A genuinely diverse student body** — 10 nationalities represented, with UAE, Nepal, and Philippines contributing the largest shares.

## Contents

```
├── README.md
├── Student_Enrollment_Revenue_Analysis - Final One.twbx   ← the live Tableau workbook
└── Student_Enrollment_Revenue_Presentation.pptx           ← full case-study deck
```

*Built by Vinitha Manoj — Data Science & Analytics Intern, BLUEKWET.*
