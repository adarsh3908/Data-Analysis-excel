# 🚲 Bike Sales Analysis

This folder contains an end-to-end Excel analysis and dashboard built from a bike buyers dataset. The analysis demonstrates Excel data cleaning, pivot table modeling, slicers for interactive filtering, and a polished dashboard with multiple charts.

## Files

- `Excel Project Dataset(bike_buyers).csv` — Original raw dataset (bike buyers)
- `Excel Project Dataset(Working Sheet).csv` — Preprocessed CSV used for pivot tables and charts
- `Excel Project Dataset (1).xlsx` — Full Excel workbook containing three sheets: raw data, preprocessed data, and the dashboard with PivotTables and Slicers

## Images

The `images/` folder includes three screenshots:

### 1. Complete Dashboard View
![Complete Dashboard](./images/Screenshot%202025-10-05%20221351.png)
*Complete dashboard showing all KPIs and visual layout*

### 2. Interactive Filters and Slicers
![Filters and Slicers](./images/Screenshot%202025-10-05%20221405.png)
*Filters and Slicers used for interactive analysis*

### 3. Dashboard Charts Detail
![Three Charts](./images/Screenshot%202025-10-05%20221415.png)
*Detail view showing the three charts used on the dashboard*

## How it was built

- Data cleaning and preprocessing done in Excel (filters, text-to-columns where needed, basic calculations)
- PivotTables created from the preprocessed sheet to aggregate sales, counts and KPIs
- Slicers connected to PivotTables to enable interactive filtering by customer demographics and purchase attributes
- Charts (bar, line, donut/pie) formatted for presentation and placed on a dashboard sheet

## How to use

1. Open `Excel Project Dataset (1).xlsx` in Microsoft Excel (desktop recommended for slicer interactivity).
2. Go to the `Dashboard` sheet to view KPIs, charts, and use the slicers to interactively filter the analysis.
3. Inspect the `Preprocessed` sheet to see cleaning steps and calculated fields used by the PivotTables.

## Notes

- The workbook uses standard Excel PivotTables and Slicers — no macros or VBA.
- If you want a CSV-only workflow, use `Excel Project Dataset(Working Sheet).csv` as the source for other tools.

---

If you'd like, I can:

- Add a short summary of key insights from the bike analysis to this README
- Create a small preview image (thumbnail) for the dashboard
- Add a simple script to convert the CSV into a cleaned CSV programmatically (Python)

Tell me which of these you'd like next.