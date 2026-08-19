# UPI & Digital Payment Growth in India

**How has India's digital payment ecosystem grown, and what demographic and regional factors drive or hinder UPI adoption?**

An end-to-end data analytics project examining the growth of India's Unified Payments Interface (UPI) from 2016 to 2026, and the regional factors — internet penetration and urbanization — that influence adoption across Indian states.

📄 **[Full Report (PDF)](./UPIs_adoption_report_final.pdf)**

---

## Key Findings

- UPI has grown from a niche payment method in 2016 to India's dominant digital payment mode, with **over 797.77 billion cumulative transactions** recorded from April 2016 through June 2026
- Bank participation grew from **21 to 731 banks**, with growth plateauing from 2024 onward as most eligible institutions joined the ecosystem
- Average transaction value declined from ~₹1,500 (2018) to under ₹1,000 (2025–26), reflecting a shift from occasional large transfers to everyday small-value payments
- At the regional level, **internet penetration (r = 0.78)** showed a stronger and more consistent relationship with UPI adoption than **urbanization (r = 0.71)**
- Telangana recorded the highest per-capita UPI adoption in the sample despite only moderate urbanization — suggesting internet access is a more direct enabler of adoption than urbanization alone

## Project Components

| Component | Description | File |
|---|---|---|
| Full Report | Complete write-up with methodology, findings, and limitations | `UPIs_adoption_report_final.pdf` |
| Python Analysis | Trend analysis, correlation calculations, geographic visualization | `UPI_Analysis.ipynb` |
| Power BI Dashboard | 4-page interactive dashboard (National Trend, Transaction Behaviour, Regional Drivers, Map View) | `PowerBI_Dashboard_final.pbix` |
| Cleaned Dataset | Master NPCI transaction dataset after cleaning and validation | `NPCI_CLEANED_MASTER.csv` |
| Merged Regional Data | TRAI, UPI, and Census data merged for regional analysis | `3_files(TRAI,UPI,Merged).xlsx` |

## Methodology

A mixed-method approach combining:
- **Time-series analysis** of national UPI transaction trends (volume, value, bank participation)
- **Cross-sectional correlation analysis** across a 9-state purposive sample (5 high-adoption states, 4 low-adoption states), examining internet penetration and urbanization as regional adoption drivers

Full methodology, data sources, and limitations are detailed in the report.

## Tools Used

- **Python** (pandas, seaborn, matplotlib, folium) — data analysis and geographic visualization
- **Microsoft Power BI** — interactive dashboard development
- **Microsoft Excel / Power Query** — data cleaning and integration

## Data Sources

- National Payments Corporation of India (NPCI) — year-wise UPI transaction statistics
- Telecom Regulatory Authority of India (TRAI) — state-wise internet penetration data
- Factly / Dataful — state-wise UPI per-capita transaction figures
- Census of India (2011) — state-wise urbanization data

## Limitations

This analysis is descriptive and correlational, not causal. The 9-state regional sample was purposively selected (not random), so correlation coefficients may overstate the true strength of these relationships at a national level. Full limitations are documented in the report (Section 6).

---

**Author:** Mahmud Alam
📧 mahmudalam0506@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/mahmud-alam-4871a2354)
