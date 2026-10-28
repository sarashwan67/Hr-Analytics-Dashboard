# HR Analytics Dashboard (Excel)

An interactive 3-page Excel dashboard that answers one question: **why are employees leaving?**

Built on an HR dataset of **1,480 records and 38 attributes** (demographics, job role, income, satisfaction scores, overtime, tenure, and attrition).

## Dashboard Pages

| Page | What it shows |
|------|---------------|
| **Overview** | Headline KPIs and attrition at a glance |
| **Employee** | Employee-level breakdowns (age, tenure, satisfaction, work-life balance) |
| **Department** | Department and job-role comparisons (attrition, income, overtime, satisfaction) |

Slicers (Department, Salary Slab) filter every chart at once.

## KPIs Tracked

Total Employees · Attrition Rate · Overtime Rate · Satisfaction Score · Avg Monthly Income · Avg Age · Avg Tenure

## Key Insights

- Overall attrition rate is **16.1%**.
- Employees working **overtime** leave at **30.6%**, versus **10.4%** for those who don't.
- **Sales Representatives** have the highest attrition by role at **39.3%**.
- Employees aged **18-25** leave at **35.8%**, the highest of any age group.
- Attrition drops as income rises: **21.6%** for the "up to 5k" slab versus **3.8%** for 15k+.

**Takeaway:** attrition clusters around overtime, junior roles, and lower pay bands.

## How It Was Built

1. Reviewed the dataset and wrote a data dictionary (column meanings).
2. Planned the layout in a wireframe before building.
3. Built 23 PivotTables to calculate the KPIs and chart data.
4. Designed the dashboard pages with charts, KPI cards, and slicers.

## Tools

Microsoft Excel: PivotTables, PivotCharts, Slicers, dashboard design.

## Repository Structure

```
├── README.md
├── HR_Analytics_Dashboard.xlsx
├── data/
│   └── HR_Analytics.csv
└── screenshots/
    ├── overview.png
    ├── employee.png
    └── department.png
```

## Screenshots

### Overview
![Overview](screenshots/overview.png)

### Employee
![Employee](screenshots/employee.png)

### Department
![Department](screenshots/department.png)

## Author

**Sara** · Computer Science student, Helwan University
[LinkedIn](https://www.linkedin.com/in/YOUR-PROFILE)