# HR Attendance and Leave Analytics Dashboard-Power BI

A Power BI dashboard for analyzing employee attendance, 
leave patterns, and work-from-home trends across multiple months for 80+ employees of a company.

## Dashboard Preview
![Dashboard Preview](dashboard_preview.jpg)

## Tech Stack
- **Power Query** — Data transformation & automation.
- **Power BI Desktop** — Dashboard & visualizations.
- **DAX** — Measures and calculated columns.
- **Excel** — Source data.
  
## DAX Measures Created
- `Attendance %` — Present days / Office working days.
- `WFH %` — WFH count / Office working days.  
- `SL %` — SL count / Office working days.
- `LWP Count` — Total Leave Without Pay instances.
- `Leave Count` — Total leave days by type.
- `Present Days` — Count of P values.
- `Office Working Days` — Excluding weekends.
- `WFH Count` — WFH + HWFH combined.

## Key Insights
-  Overall attendance rate held strong at **91.9%** across 85 employees
-  **Friday** recorded highest WFH (13.1%) — employees prefer end-of-week remote work
-  **Monday** had best attendance (93.3%) — strong week-start presence
-  **Paid Leave (38.98%)** was the most consumed leave type
-  **70 LWP instances** flagged — key risk indicator for HR intervention
-  Attendance dipped to **75%** in mid-May — worth investigating for HR
-  Top 5 low-attendance employees all fell **below 76%** — potential HR action needed
-  Sick Leave(SL) % remained low at **1.1%** suggesting healthy workforce overall

##  How the Automation Works
1. Each month's data lives in a separate Excel sheet.
2. A Power Query **Parameter** stores the sheet name.
3. A **Custom Function** applies transformations to any sheet.
4. Adding a new month = one refresh click, zero manual work.

## Key Features
- Automated monthly data refresh using Parameters & Custom Functions in powerquery.
- Attendance %, WFH %, SL % KPI tracking.
- Employee attendance heatmap.
- Leave type breakdown. (PL, SL, WFH, LWP, BRL, ML, and more)
- Day-of-week attendance & WFH pattern analysis.
- Low-attendance employee identification.
- Monthly trend lines for Attendance, WFH, and Sick Leave.
  
##  Files
| File | Description |
|------|-------------|
| `HR Attendance & Leave Analytics Dashboard.pbix` | Main Power BI file |
| `Attendance-Sheet-2022.xlsx` | Source Excel data |
| `dashboard_preview.jpg` | Dashboard screenshot |

## By
Shubham Kumar Bhakta
