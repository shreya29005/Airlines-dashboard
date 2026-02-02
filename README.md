# Airline Operations & Revenue Analytics Dashboard

## ✈️ Project Overview
This project is a comprehensive **Power BI** solution designed to analyze the intersection of international flight operations, customer experience, and financial performance. By integrating workforce metrics (pilot shortages) with financial data and customer feedback, the dashboard provides a "stress-test" environment for evaluating pricing strategies and operational risk.

## 📊 Key Dashboards & Insights

### 1. Executive Summary (Home)
The landing page provides a high-level view of brand health and operational efficiency.
* **Customer Experience KPIs**: Tracks **Retention Rate (43.83%)**, **Net Promoter Score (-17.22)**, and **Delay Rate (30.94%)**.
* **Cost Composition Shift**: A stacked column chart visualizing the trend between Fuel Costs and Operational Costs across quarters.
* **Marketing ROI**: A dual-axis chart comparing Marketing Spend against NPS to identify inefficiencies in promotional spending.

### 2. International Scenario Analysis
A dedicated module for "What-If" analysis, allowing users to switch between four distinct pricing and operational scenarios:
* **International Base Case**: The current operational standard.
* **International Smart Pricing**: Optimized pricing strategy yielding the highest **INTL EBITDA per Flight (₹5.57M)**.
* **International Flat Pricing**: A simplified pricing model showing an EBITDA per flight of **₹4.92M**.
* **International Stress Case**: Simulates high-pressure environments, resulting in a lower EBITDA per flight of **₹4.27M**.

## 🛠️ Technical Implementation
* **Data Modeling**: Architected a robust data model integrating customer experience, flight operations, workforce capacity, and financial metrics.
* **DAX Calculations**: Developed complex measures for **EBITDA Margin %**, **Revenue at Risk**, and **Breakeven Load Factor (LF*)**.
* **Scenario Modeling**: Implemented a scenario selection toggle to compare **Yield per Seat** and **Cost per Flight** dynamically.
* **Data Visualization**: Utilized bar charts to identify the **Top Complaint Categories** (e.g., Refunds, Flight Delays) causing revenue leakage.

## 📈 Key Findings
* **Revenue at Risk**: Approximately **₹95.31M** is at risk due to customer dissatisfaction, with **Refunds** and **Flight Delays** being the primary drivers.
* **Operational Constraints**: A pilot shortage is estimated to cause a loss of **₹12.37M** in potential revenue.
* **Pricing Efficiency**: "Smart Pricing" improves the yield per seat to **₹36K**, compared to **₹31K** in a stress scenario.

## 📂 Tools Used
* **Power BI**: Dashboarding and Visualization.
* **Power Query / DAX**: Data transformation and advanced financial KPIs
