# Job Market Intelligence Dashboard (Excel)

An interactive Excel dashboard analyzing job market trends — built using Power Query–style data modeling, Pivot Tables, Slicers, Pivot Charts, and KPI cards on a 5,000-record job postings dataset.

## Overview

This project demonstrates end-to-end Business Intelligence workflow in Excel: from raw tabular data to a fully interactive, decision-ready dashboard. It covers skill demand analysis, salary benchmarking, location-wise hiring trends, and remote vs onsite job distribution.

> **Note on data:** This project uses a self-generated sample dataset (5,000 synthetic job postings) modeled on realistic Indian job market patterns — Indian cities, companies, skills, and salary bands (INR LPA). It is built for demonstrating Excel BI techniques (Power Query, Pivot Tables, Slicers, dashboard design) and is not scraped from any live job portal.

## Dashboard Preview

![Dashboard Preview](dashboard_preview.jpg)

## Features

- **KPI Cards** — Total Job Postings, Active Companies, Unique Skills, Avg Salary (LPA), Remote Jobs
- **Job Postings Trend** — Monthly posting volume over the last 12 months
- **Top 10 In-Demand Skills** — Skill frequency analysis across all roles
- **Experience-Level Breakdown** — Distribution of postings by experience band (0-1, 1-3, 3-5, 5-10, 10+ yrs)
- **Location Analysis** — Top 10 hiring cities in India
- **Company Type Analysis** — Product-based, Service-based, Startup, MNC, Others
- **Salary Analysis** — Average salary by experience level, salary range distribution
- **Top Hiring Companies** — Ranked by job posting volume
- **Remote vs Onsite Split** — Work mode distribution
- **Pivot Tables & Slicers** — Interactive filtering by Location, Experience Level, Company Type, Job Type, and Fresher Eligibility
- **Skill Gap Analysis** — Top 5 in-demand skills per job role with average salary benchmarks

## Tools & Techniques Used

| Technique | Application |
|---|---|
| Data Modeling | Structured 5,000-row dataset across 15 attributes (title, company, location, skills, salary, experience, work mode, etc.) |
| Pivot Tables | Location × Experience Level, Company Type × Work Mode cross-tabulations |
| Slicers | Interactive filters for Job Type, Fresher Eligibility |
| Pivot Charts | Auto-generated visualizations from pivot data |
| Charts | Line, Bar, Column, Pie, Doughnut charts for KPI visualization |
| Formulas | COUNTA, COUNTIF, AVERAGE, SUMPRODUCT for dynamic KPI calculations |
| Conditional Formatting & Styling | Custom KPI cards, color-coded sections, clean grid layout |

## File Structure

```
├── Job_Market_Intelligence_Dashboard.xlsx   # Main Excel workbook
├── dashboard_preview.png                     # Dashboard screenshot
└── README.md
```

## Workbook Sheets

1. **Dashboard** — Main visual dashboard with KPI cards and 9 charts
2. **Raw Data** — 5,000-row source dataset
3. **Summary Data** — Aggregated tables powering the dashboard charts
4. **Skill Gap Analysis** — Role-wise top skills and salary benchmarks
5. **Pivot - Location-Exp** — Pivot Table + Slicers (Location × Experience Level)
6. **Pivot - CompanyType-Mode** — Pivot Table + Slicers (Company Type × Work Mode)

## Key Insights

- Excel, SQL, and Python are the most in-demand skills across roles.
- Bengaluru and Delhi NCR together account for roughly 40% of job postings.
- Average salary increases sharply with experience, especially beyond the 5-year mark.
- Remote jobs make up roughly a quarter of all postings, concentrated in tech and product roles.
- Product-based and service-based companies dominate overall hiring volume.

## How to Use

1. Download `Job_Market_Intelligence_Dashboard.xlsx`
2. Open in Excel (2019 or later)
3. Navigate using sheet tabs at the bottom
4. Use Slicers on the Pivot sheets to filter data interactively
5. All charts on the Dashboard sheet update automatically based on the Summary Data sheet

## Author

Built as a self-driven Excel BI practice project to demonstrate dashboard design, data aggregation, and interactive reporting skills.

---

*If you found this useful, feel free to star the repo or connect on LinkedIn.*
