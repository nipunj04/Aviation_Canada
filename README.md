# Canadian General Aviation & Pilatus PC-12 Market Analysis

A data-driven market intelligence briefing and analytical framework evaluating the Canadian general aviation landscape from 1999 to 2026. This project focuses on the fleet dynamics of the **Pilatus PC-12**, tracks historical corporate registration data from the **Transport Canada Civil Aircraft Register (CCAR)**, and resolves data paradoxes regarding manufacturer-to-distributor market share.


---

## 📋 Project Overview

The business aviation market often presents data discrepancies due to regulatory registration rules. A surface-level query of public aviation databases can obscure the true market reach of an exclusive distributor. This project aggregates, cleans, and analyzes longitudinal registry data to surface true market characteristics, macroeconomic catalysts, and distributor footprints.

### Key Objectives:
* **Macro Trend Analysis:** Track the growth and structural shifts within Canadian General Aviation over a 27-year lookback period (1999–2026).
* **Micro-Market Deep Dive:** Model the annual registration velocity, fleet distribution, and ownership concentration of the Pilatus PC-12 in Canada.
* **Regulatory Reconciliation:** Resolve the "Custody and Control" paradox where raw public datasets understate dealer transaction volume.

---

## 📊 Core Data Insights & Findings

### 1. General Aviation Trends (1999–2025)
* **Total Fleet Growth:** Total registered aircraft in Canada expanded by **49.9%**, growing from 25,114 in 1999 to 37,654 in 2025.
* **The 2020 Pivot:** Total aircraft growth remained net-positive every year except for 2020, where registrations contracted by **-0.012%** due to global pandemic disruptions. Post-pandemic recovery has been conservative, capping under 0.5% annually.
* **Up-Gauging Fleet Share:** Light aircraft continue to command over 90% of the fleet, but are on a structural downward trajectory. Meanwhile, heavier multi-engine/turbine airframes (>12,500 lbs) expanded their market share from **4.51% to 6.38%**, driven by escalating corporate utility demands.

### 2. Pilatus PC-12 Fleet Dynamics
* **The 2024–2025 Acquisition Surge:** The Canadian market experienced an unprecedented, highly correlated spike in corporate PC-12 registrations (15 units in 2024; 17 units in 2025—the highest historical year on record). 
* **Macroeconomic Catalyst:** This influx was driven by impending US tariff shifts on Swiss-manufactured goods, pushing Canadian buyers to rapidly clear inventory and register airframes locally through Levaero's dealer network.
* **Ownership Consolidation:** As of May 2026, there are 130 active historically registered PC-12s in Canada. The Government of Canada (Royal Canadian Mounted Police) represents the largest individual fleet operator with 16 units.

### 3. Resolving the Distributor Data Paradox
* **The Problem:** A raw query of the active Transport Canada registry shows only 2 PC-12s registered directly under *Levaero Aviation Inc.*
* **The Solution:** By conducting a historical name reconciliation across Levaero's three historical corporate iterations (*V. Kelner Pilatus Center*, *Pilatus PC-12 Centre Canada*, and *Levaero Aviation*), the data proves Levaero has directly touched **80 unique airframes (61.5% of the historical market)**, with 40 remaining actively registered today.
* **Business Logic Layer:** The remaining gap is explained by standard aircraft distribution mechanics. Exclusive distributors rarely assume operational "custody and control" during direct factory-to-client transactions. Consequently, Transport Canada issues the initial Certificate of Registration directly to the end-buyer, bypassing distributor nomenclature in public registries and artificially deflating raw market share calculations.

---

## 🛠️ Repository Structure

```text
├── Data/
│   ├── raw_tc_registry_export.csv       # Raw transactional data extracted from Transport Canada
│   └── cleaned_aviation_market_data.xlsx # Structured dataset with pivot tables, data cleaning, and chart pipelines
├── Delivery/
│   └── Nipun_Jaiswal_Market_Brief.pdf   # Final executive-ready PDF market briefing note
└── README.md                            # Portfolio documentation and project overview
