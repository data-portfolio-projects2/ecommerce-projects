# E-commerce Analytics Engineering & Data Forensics

| 01 | Airbnb Price Prediction | Classification | [![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-blue.svg)](https://github.com/KalyanMurapaka45/End-to-End-Airbnb-Price-Prediction) |

This repository showcases how common business reporting issues are created, detected, and fixed using **SQL** and **Python**.

Instead of perfect demo data, the project intentionally generates messy e-commerce data and then reverse-engineers the problems — the same way analysts troubleshoot broken dashboards in real companies.

### What this project demonstrates

*   **Aggregation errors:** How they distort revenue and customer metrics.
*   **Broken joins & mapping issues:** How they create misleading KPIs.
*   **Business rule validation:** (e.g., verifying one order → one customer).
*   **Root-cause analysis:** Tracing dashboard problems back to specific data defects.

### Scope & Positioning

This is **analytics engineering**, not system-level data engineering. 

**The focus is on:**
*   Analytics tables
*   KPI logic
*   Metric consistency
*   Order-to-customer mapping errors
*   Downstream reporting accuracy

### Techniques Used

*   **SQL validation patterns**
*   **Python / Pandas** forensic analysis
*   **Business-rule checks** & data contracts
*   **Metric sanity testing**
*   **Root-cause tracing** from dashboard → table → record

### Why this matters

Most reporting problems aren’t caused by broken systems — they’re caused by **silent data mistakes** that go unnoticed.

This repo shows how to:
1.  **Detect** them
2.  **Explain** them
3.  **Fix** them
4.  **Prevent** them from happening again

---

### Disclaimer

This project does not focus on pipelines, orchestration, or infrastructure. It focuses on what analytics teams deal with every day: 
- **Messy business data, broken assumptions, and KPIs that quietly stop making sense.**
```
repo-name/
│
├── README.md
├── data/
│   ├── raw/
│   └── processed/
│
├── analysis/
│   ├── problem_and_solution.ipynb  # includes problem, solution, and dashboard integration
│
├── dashboard/
│   ├── dashboard.ipynb             # interactive dashboard (Plotly, Streamlit, or Tableau export)
│   └── screenshots/                # PNG/JPG of before vs after dashboards
│
├── sql/
│   ├── validation_checks.sql
│   └── aggregation_queries.sql
│
├── scripts/
│   ├── data_generation.py
│   ├── data_cleaning.py
│   └── pipeline_runner.py
│
├── docs/
│   └── business_impact.md
│
└── requirements.txt
```
