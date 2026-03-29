# Product Performance Analytics Dashboard

## 📌 Project Overview
This project focuses on building a **"data-first"** analytical tool to transform raw business datasets into a high-performance dashboard. Using **Power BI**, I engineered an automated pipeline that moves beyond static reporting to provide **predictive insights** and **scenario simulations** for data-driven decision-making.

## 🛠️ Technical Stack
*   **Analytics Platform:** Power BI Desktop
*   **Data Transformation:** Power Query (M Language)
*   **Data Modelling:** Star Schema (Fact & Dimension tables)
*   **Logic & Calculations:** DAX (Data Analysis Expressions)

## 🚀 Key Features & Implementation

### 1. Automated ETL Pipeline (Data Transformation)
*   **Action:** Architected a repeatable workflow in **Power Query** to ingest and structure raw datasets.
*   **Implementation:** Applied automated steps for data unpivoting, null-handling, and type standardisation.
*   **Outcome:** Created a "one-click" refresh system that ensures a reliable foundation for all downstream analytics.

### 2. Interactive Business Intelligence
*   **Action:** Developed multi-page reports focused on translating complex datasets into **actionable insights**.
*   **Implementation:** Utilised cross-filtering, slicers, and drill-through actions to allow stakeholders to identify regional and product-level performance trends.

### 3. Scenario Simulation & Predictive Analysis
*   **Action:** Integrated **What-If parameters** and **Trend Forecasting** to support future-state hypothesising.
*   **Implementation:**
*   DAX – Adjusted Sales = SUM('superstore_dataset'[Sales]) * (1 + SELECTEDVALUE('Price Change %'[Price Change %])/100)
    *   **What-If:** Created dynamic sliders to simulate variable changes, and view real-time impacts on profit.
    *   **Forecasting:** Applied built-in exponential smoothing models to project sales trends based on historical data.

### 4. Performance Optimisation
*   **Action:** Optimised data pipelines to ensure accuracy under varying data loads.
*   **Implementation:** Reduced model size through column pruning and implemented a Star Schema to enable efficient **Query Folding**.

## 📊 Business Impact
*   **Proactive Strategy:** Identified potential seasonal revenue dips through trend forecasting, allowing for simulated marketing shifts.
*   **Efficiency:** Automated 100% of the manual data-cleaning process, providing a "single source of truth" for business performance.
