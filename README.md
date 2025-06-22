## Supply-Chain-Risk-Management_Power-BI-Dashboard_Analysis

> **An End-to-End Data Analytics Project using Power BI for GlobalLogiX**  
> 🧠 Built to assess and mitigate supply chain risks using DAX, Power Query, KPI metrics, and interactive visuals

---
## 🧾 Project Overview

This Power BI project simulates a real-world challenge from **GlobalLogiX**, a multinational logistics and supply chain company. As part of a **Power BI skill test**, this dashboard focuses on solving key supply chain problems like supplier risk assessment, delayed shipments, inventory inefficiencies, and return analysis.

---

## 🎯 Objectives

- 🚚 Visualize key logistics and supplier risk metrics
- 🛠️ Use Power Query to clean and shape supply chain data
- 📊 Build advanced visuals: heatmaps, drill-throughs, and forecasts
- 🧮 Create DAX measures for dynamic KPIs and composite scores
- 📈 Enable decision-makers to interactively filter and slice data

---

## 🗃️ Datasets Used

| Dataset          | Description                                                             |
|------------------|-------------------------------------------------------------------------|
| `Suppliers`      | Risk score, region, reliability, defect rates                           |
| `Shipments`      | Delivery status, delay reasons, shipping dates, regions                 |
| `Orders`         | Past orders, delivery timelines, demand trends                          |
| `Warehouses`     | Inventory levels, replenishment status, thresholds                      |
| `Returns`        | Return reasons, costs, frequencies, shipment links                      |

---

## 📊 Key Visualizations & Scenarios

### 🔰 Beginner-Level Dashboards
- **High-Risk Suppliers Table**: Risk > 80, Reliability < 3
- **Shipment Delays Line Chart**: Last 6 months of delay trends
- **Inventory Bar Chart**: Stock per warehouse with conditional highlights

### 🔄 Intermediate-Level Dashboards
- **Return Reason Pie Chart**: % distribution of top return causes
- **Region-wise On-Time Delivery**: Stacked column (On-time vs Delayed)
- **Supplier Performance Matrix**: Filter by region, reliability, risk
- **Dynamic KPIs**:
  - Avg. Delivery Time
  - % Late Shipments
  - Avg. Supplier Risk Score
- **Demand Forecast Chart**: Based on historical orders

### 🔬 Advanced-Level Analysis
- **Composite Supply Chain Risk Score**:
  - Supplier Risk (40%)
  - Shipment Delays (30%)
  - Defect Rate (20%)
  - Inventory Shortages (10%)
- **Heatmap Visualization**: Risk score by region

---

## 🧠 Power BI Techniques Used

| Area              | Features Applied |
|-------------------|------------------|
| **Data Modeling** | Star schema, normalized relationships |
| **Power Query**   | Data cleaning, column transformations |
| **DAX Measures**  | KPIs, time-intelligence, forecasting |
| **Visuals**       | Line, Bar, Pie, Matrix, Forecast, Heatmap |
| **UX Features**   | Slicers, Drill-throughs, Conditional Formatting, Tooltips |

---

## 📁 Folder Structure

```bash
📁 Supply-Chain-Risk-PowerBI/
├── 📊 Supply Chain Risk Management.pbix
├── 📄 README.md
