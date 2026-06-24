# US Superstore Executive Sales Performance Dashboard

## 📊 Project Overview
This repository contains an interactive **Executive Sales Performance Dashboard** built entirely in Microsoft Excel. The project analyzes a multi-year retail dataset from a prominent US Superstore to evaluate regional performance, uncover macro seasonal trends, dissect logistics fulfillment modes, and identify core customer segments. 

The primary objective of this analysis is to transform raw sales data into actionable business strategies, providing corporate stakeholders with the insights necessary to optimize supply chain efficiency and maximize regional revenue.

---

## 🛠️ Tech Stack & Architecture
* **Data Processing:** Power Query (Data cleaning, type casting, transformation)
* **Data Modeling:** Power Pivot / Excel Data Model (Star schema configuration, relationships)
* **Analytics Engine:** Advanced Pivot Tables, custom DAX measures, and time-intelligence calculations
* **Visualization Interface:** Dynamic timelines, interactive multi-slicers (Region, Segment, Category), geographical heat mapping (Bing Maps integration), and custom distribution donut charts.

---

## 🖥️ Dashboard Interface Layout

The interactive user interface is structurally divided into four core areas to enable seamless data drilling:

1. **Executive KPIs:** Real-time tracking of Overall Revenue, Average Shipping Time (Days), and Region-Wise Sales.
2. **Temporal Trends:** A dynamic "Sales Volume over Time" column chart mapped with a moving average trendline to isolate growth spikes.
3. **Product & Customer Analytics:** Side-by-side breakdowns of category-wise sales alongside order counts grouped by customer segments (Consumer, Corporate, Home Office).
4. **Geographical Distribution:** An integrated US map displaying regional revenue density at a glance.

![Executive Sales Performance Dashboard](DashBoard.png)

---

## 💡 Executive Insights & Strategic Recommendations

### 1. Regional Dominance & Market Penetration (West Region)
* **The Finding:** The West region consistently generated the highest revenue over the 4-year analysis period. Within this territory, California serves as the primary anchor, single-handedly driving over 50% of all Western sales.
* **CEO Strategy:** Establish a secondary distribution hub or dedicated fulfillment center within or adjacent to California. This reduces transit distances, drastically lowers regional carrier fees, and secures optimal inventory velocity for the store's highest-volume market.

### 2. Shifting Logistics & Consumer Fulfillment Trends
* **The Finding:** Demand for the "Standard Class" delivery mode has steadily declined year-over-year, dropping from 63% to 54% by the final year. Conversely, expedited tiers (First Class, Second Class, Same Day) have captured a combined 46% share of orders.
* **CEO Strategy:** Shift supply chain resources to accommodate faster delivery expectations. Expedite warehouse handling processing and negotiate aggressive volume-based rates with expedited freight carriers to protect profit margins against rising shipping costs.

### 3. Macro Cyclicality & Seasonality Trends
* **The Finding:** Sales follow a rigid, highly predictable seasonal pattern: Quarter 1 (Q1) consistently marks the lowest revenue generation period of the fiscal year, while Quarter 4 (Q4)—specifically November and December—experiences massive demand spikes.
* **CEO Strategy:** Implement data-driven demand planning and inventory throttling. Scale down warehouse staffing and logistics capacity in Q1 to minimize operational overhead, and ramp up operations by late Q3 to prevent stockouts and fulfillment bottlenecks during the peak holiday surge.

### 4. Shipping Efficiency vs. Revenue Correlation
* **The Finding:** Data indicates that fulfillment latency (average shipping time) directly correlates with customer retention and total revenue growth within lagging territories. 
* **CEO Strategy:** Tie logistics Service Level Agreement (SLA) performance directly to regional sales targets. Prioritize shipping pipeline optimization in slower zones to bridge the revenue gap and ensure operational friction doesn't cap market expansion.

---

