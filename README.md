# Grocery Sales Analysis Dashboard (Tableau + Power BI + Excel)

Interactive dashboards to analyze grocery sales trends, KPIs, and customer segments.  
Built in **Tableau** and **Power BI**, with supporting **Excel** data prep.  
Includes monthly/weekly trends, category-level performance, and customer behavior insights.

## Demo

### Tableau Demo
- **Live dashboard**: _(add Tableau Public link)_
- **Preview image**: see `/images/tableau_overview.png`

### Power BI Demo
- **Live dashboard**: _(add Power BI Service link or screenshot)_
- **Preview image**: see `/images/powerbi_overview.png`

## Highlights
- KPI tiles: Revenue, Profit, Avg. Order Value, Units
- Time-series trends with YoY comparison
- Category & sub-category breakdowns with Pareto
- Customer segmentation and top 10 customers
- Filters: date, region, channel, category

## Repo Structure
```
grocery-sales-bi-dashboard/
├─ data/                 # Sample/cleaned CSVs (no PII)
├─ tableau/              # Tableau .twb/.twbx files
├─ powerbi/              # Power BI .pbix files
├─ excel/                # Excel prep files (Power Query, pivots)
├─ images/               # Screenshots (Tableau + Power BI)
├─ docs/                 # One-pager, notes, decisions
└─ scripts/              # Optional: small helpers (Python/R)
```
> Avoid pushing raw/confidential data. Share only anonymized and small samples in `/data`.

## How to Use

### Tableau
1. Open the `.twbx` file in `/tableau` (contains embedded extracts).  
2. If using `.twb`, place CSVs from `/data` in the same relative paths and refresh extracts.

### Power BI
1. Open `.pbix` file in `/powerbi`.  
2. Refresh connections to point to CSVs in `/data`.  
3. Optional: publish report to Power BI Service.

### Excel
- Supporting transformations (Power Query) and pivot tables in `/excel/`.

## Data Notes
- Data is simulated/anonymized for portfolio demonstration.
- Add a short data dictionary in `/docs/data_dictionary.md`.
- Include any cleaning steps performed in Excel (Power Query) or scripts.

## Results (example)
- +7.8% MoM sales growth in July
- Beverages & Produce drive ~52% of revenue (Pareto 80/20 holds)
- Online channel AOV ≈ 1.3× higher than In-Store
- Friday shows peak units; Wednesday lowest

> Replace the above with your actual numbers/screenshots.

## Project Background
This project showcases **dashboard design, KPI storytelling, and self-service BI**.  
Built by **Rutuja A. Bhatankar** using Tableau, Power BI, and Excel.

## License
MIT — see `LICENSE`.
