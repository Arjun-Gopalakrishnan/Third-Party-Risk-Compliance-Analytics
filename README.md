# Third-Party Risk Analytics & Vendor Due Diligence Framework

## 🎯 Project Overview
This project outlines an end-to-end data pipeline designed to automate compliance screening for global vendor onboarding and anti-money laundering (AML) protocols. It transitions traditional, error-prone manual corporate screening into a dynamic, programmatic architecture.

## 🛠️ Tech Stack
* **Data Engineering & Processing:** Python 3, Pandas
* **Business Intelligence & Visualization:** Power BI Desktop, DAX
* **Data Layer:** Relational client compliance profiles and international watchlists

## 🚀 Key Framework Features
1. **Algorithmic Risk Engine:** A custom Python workflow evaluating entities across critical risk dimensions: active sanction list matches (OFAC), Politically Exposed Person (PEP) status, jurisdictional risk indexes (FATF), and inherent sectoral risk.
2. **Interactive Executive Dashboard:** Built-in dynamic cross-filtering allowing risk officers to isolate portfolio-wide threats instantly by risk tier, country coordinates, and entity types.
3. **Operational Audit Trail:** A conditionally formatted ledger flagging maximum-threat third parties automatically to prioritize governance escalations.

## 📁 Repository Structure
* `Riks_Analysis.ipynb`: Jupyter Notebook containing raw data cleaning, logical transformations, and risk score weight calculations.
* `Third_Party_Risk_Compliance_Dashboard.pbix`: Master interactive Power BI design file.
* `Third_Party_Risk_Compliance_Dashboard.pdf`: Static layout overview displaying final corporate visual hierarchy.
