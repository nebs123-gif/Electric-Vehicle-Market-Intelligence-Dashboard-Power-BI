 Electric-Vehicle-Market-Intelligence-Dashboard-Power-BI
This project delivers a comprehensive Electric Vehicle Market Intelligence Dashboard built in Power BI, designed to surface actionable insights across EV adoption trends, brand performance, geographic distribution, and market maturity. The dashboard draws on a rich dataset of registered EVs across the United States.


 Electric Vehicle Market Intelligence Dashboard 

 Overview

This project delivers a comprehensive Electric Vehicle Market Intelligence Dashboard built in SQL and Power BI, designed to surface actionable insights across EV adoption trends, brand performance, geographic distribution, and market maturity. The dashboard draws on a rich dataset of registered EVs across the United States, segmented by make, model, county, vehicle type, and model year.


 Dashboard Pages

 1. Electric Vehicle Market Intelligence Dashboard 
The top-level command center providing a snapshot of the entire EV landscape:

- 247K Total EVs registered across all years
- 79.71% Battery Electric Vehicles (BEV) vs. Plug-in Hybrid Electric Vehicles (PHEV)
- Average Electric Range of 44.65 miles
- 5.98% EV penetration as a share of total utility vehicles
- A time-series line chart tracking Total EV Registered by Year — showing exponential growth peaking around 2022–2023, followed by a sharp data cutoff suggesting recency of the dataset snapshot
- A choropleth map (EV Distribution by County) highlighting concentration in the Pacific Northwest, Texas, and the Northeast corridor
- A Top EV by Make horizontal bar chart, with Tesla dominating, followed by Volvo, Ford, Chevrolet, BMW, Audi, Hyundai, and Kia
- An EV Utility by Type donut chart confirming the BEV majority at 61.86% vs. PHEV at 38.14%


 2. EV Market Structure and Brand Performance Analysis
A deeper drill-down into brand and model-level performance:

- EV Registered (VIN) by Make — Tesla leads with nearly 2,000 registrations in the filtered view, followed by Volvo, Ford, Chevrolet, BMW, Audi, Hyundai, Kia, and Porsche
- Average Electric Range by Make — Jaguar and specialty brands (TH!NK, Wheego) show interesting range profiles; Chevrolet and Nissan appear in the mid-range tier; Tesla sits near the top with Porsche
- EVs Registered per County by Model — Model 3 and Model Y lead all models, followed by the RAV4 Prime (PHEV), Model S, Pacifica, Wrangler, LEAF, and ID.4 — reflecting consumer preference for SUVs and Tesla sedans


3. Electrification Maturity and Market Transition Report
A longitudinal view examining how the EV market has evolved over two decades:

- Average Electric Range Over Time — Steady upward trajectory from near zero in the early 2000s to over 200 miles by the early 2020s, validating battery technology advancement
- % BEV by Year — Shows a gradual increase in pure BEV share over time, crossing above 80% in recent years as PHEVs lose relative market share
- Total EV Registered by Year — Mirrors the overview chart, confirming the dramatic acceleration post-2018 and a spike around 2022
- Average MSRP, Electric Range, and EV Registered (Bubble Chart) — A multi-variable scatter plot comparing brands across price, range, and volume. Tesla occupies a dominant position with high volume and strong range, while Jaguar and Wheego are outliers on the range axis

 Tools & Skills Used

| Tool | Application |
| SQL (data shaping and transformation)
| Power BI Desktop | Dashboard design, data modelling, DAX measures |
| DAX | KPI calculations (%BEV, Avg Electric Range, % EV by Utility) |
| Power Query (M) | Data cleaning, type transformations, date normalization |
| Map Visual | County-level geographic distribution |
| Bubble Chart | Multi-metric brand comparison (MSRP × Range × Volume) |

 Key Insights

Tesla's dominance is structural, not just numerical. Across every page — registration volume, average range, and model-level county data — Tesla consistently outperforms every other manufacturer by a wide margin. This reflects not just sales success but infrastructure investment (Supercharger network) and brand loyalty.

BEV is winning the long game. The % BEV by Year trend line tells a clear story: Plug-in Hybrids were an important transitional technology, but pure electric vehicles have steadily overtaken them. The market is consolidating around BEV.

Geographic concentration creates policy and infrastructure risk. The county distribution map shows EV adoption clustering heavily in Washington State, parts of Texas, and the Northeast. Rural and central U.S. counties remain largely untouched — pointing to charging infrastructure gaps as a key adoption barrier.

Range anxiety is being solved — but unevenly. Average electric range has grown significantly over the dataset period, but the brand bubble chart shows the gains are not evenly distributed. Budget and legacy brands still trail Tesla and luxury competitors like Jaguar and Porsche on range.

The 2022 registration spike warrants investigation. The sharp peak followed by an apparent drop in the time-series likely reflects either a data snapshot cutoff or a real slowdown tied to macroeconomic conditions (rising interest rates, EV tax credit eligibility changes in 2023). Either way, it's a pattern worth tracking.


 Data Source

This dashboard was built using publicly available electric vehicle registration data. The dataset includes registered EVs with fields for make, model, model year, electric range, MSRP, county, legislative district, electric utility provider, and vehicle type (BEV vs. PHEV). : [Electric Vehicle Population Data — Washington State DOL via data.wa.gov](https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2)

 About

Built as part of a Business Intelligence & Data Analytics portfolio. This project demonstrates end-to-end BI development: from raw data ingestion and transformation through to executive-ready dashboard design with multi-page narrative structure.

Skills demonstrated: Power BI · DAX · Data Modelling · KPI Design · Geospatial Visualisation · Time-Series Analysis · Market Analysis · Storytelling with Data

---

*If you found this useful, feel free to ⭐ the repo and connect on [LinkedIn](#).*
