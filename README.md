 🌿Godrej-Consumer-Products-Ltd.-Environmental-Decarbonization-Dashboard-BRSR-Core
 
 📌 Executive Summary
An audit-ready corporate sustainability model built in Microsoft Excel mapping **100+ SEBI BRSR (Principle 6) environmental disclosures** across a 4-year period (**FY 2022-23 to FY 2025-26**).

 📊 Key Operational Metrics & Decarbonization Highlights
* **Scope 1 Emission Reduction:** Quantified a **~62.7% drop in direct emissions** in FY 25-26 (from 29,544 MtCO₂e down to 11,018 MtCO₂e), driven by biodiesel boiler substitution.
* **Energy Savings:** Modeled **3.78 Million kWh** in targeted energy efficiency projects across 21 initiatives.
* **Circular Economy Leadership:** Maintained a **~98.08% waste recovery rate** in FY 25-26 (recycled 6,189 MT out of 6,310 MT total waste).
* **Water Stewardship:** Tracked **36,300 KL** of reclaimed/reused water, reducing groundwater dependency.

## 🏛️ Architecture & System Design
The model is engineered using a decoupled 4-tab structure:
1. `Executive_Summary`: Front-end executive UI with dynamic KPI cards, year-level drop-down engines, and trend visualization layouts.
2. `Raw_BRSR_Data`: Back-end master database containing 117 audit-verified disclosure rows.
3. `Calculations`: Central aggregation engine utilizing `=SUMIFS()` and `=INDEX(MATCH())` lookup logic to prevent corruption during year shifts.
4. `Initiatives_Tracker`: Detailed log tracking plant-level energy, water, and fuel conservation projects.
