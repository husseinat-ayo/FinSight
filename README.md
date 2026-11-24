# FinSight — Finance & Transaction Analytics (Power BI)

An interactive **Power BI** business intelligence solution built to analyze financial transactions, customer segments, regional performance, fee/tax generation, and transaction reliability across multi-year data (2023–2026).

---

## Executive Summary & Business Value

Financial teams and product leaders often struggle to balance high-volume retail activity with high-margin segments and payment reliability. **FinSight** brings transaction volume, monetary value (₹), fee/tax performance, status outcomes (`Success`, `Failed`, `Pending`), and granular transaction logs into a single intuitive interface—helping stakeholders quickly spot growth pockets, operational friction, and segment behavior.

---

## Key Features & Dashboard Views

* **Overview Analysis View:**
  * **KPI Summary Cards:** Tracks **Total Amount**, **Total Transactions**, **Avg Transaction**, **Total Fees**, and **Total Tax** alongside **vs Previous Year** comparisons.
  * **Dynamic Metric Switching:** Allows users to dynamically switch primary visual metrics across **Total Amount**, **Total Fees**, **Total Tax**, and **Total Transactions**.
  * **Trend & Reliability Visuals:** Monthly trend lines, `Transaction_Status` donut breakdowns (`Success`, `Failed`, `Pending`), **Customer Segment** rankings (`Retail`, `Premium`, `SME`, `Corporate`, `Wealth`), **State-level** comparisons, **Transaction Type Analysis** matrix, and **Gender** breakdowns.
  * **Interactive Slicers & Drill-Through:** Filter by **Year**, **Dynamic Metrics**, **Occupation**, and **Category**, and drill through from state/visual points into detailed records.
* **Transaction Detail View:**
  * Granular transaction table displaying `Transaction_Id`, `Transaction_Date`, `Customer Name`, `Transaction_Type`, `Transaction_Status`, `Gender`, `Customer_Segment`, `State`, `Total Amount`, `Total Fees`, and `Total Tax` for root-cause investigation and auditing.

---

## Key Insights Uncovered

* **Retail Drives Scale; EMI & Transfers Drive Value:** Across broad views, **Retail** leads customer segment volume/value, while **Loan EMI**, **Transfer**, and **Deposit** represent major pillars of transaction amount and fee revenue.
* **Reliability Is Strong Yet Improvable:** Successful transactions account for roughly **82%–88%** across examined views, while **Failed** and **Pending** transactions consistently merit targeted operational review to reduce friction and drop-offs.
* **Cohort & Metric Shifts Matter:** Filtering by specific combinations (such as **Occupation** and **Category** across years) reveals distinct regional leaders and shifts in fee contribution across customer segments and genders.

---

## Tools & Techniques Used

* **Power BI Desktop:** Interactive report layout, custom navigation buttons (`Overview Analysis` / `Transaction`), slicers, dynamic metric selection, and drill-through configuration.
* **Data Modeling & DAX:** KPI measures, period-over-period (`vs Previous Year`) comparisons, dynamic metric measures, and multi-dimensional slicing across time, geography, customer attributes, and transaction types.
* **Data Storytelling & UX Design:** Clean left-rail navigation, scannable KPI cards, conditional color formatting in breakdown tables, and progressive disclosure from summary KPIs to transaction-level records.

---

## Project Structure

```text
finsight-powerbi/
├── README.md
├── FinSight_Finance_Analysis.pbix      # [Add your Power BI file]
├── data/                               # [Sample or anonymized dataset, if shareable]
└── screenshots/
    ├── overview_2024.png
    ├── overview_filtered_metrics.png
    └── transaction_detail.png
