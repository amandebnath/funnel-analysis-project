# E-Commerce Funnel Analysis & Performance Dashboard

## Executive Summary
This project analyzes the customer journey of an e-commerce platform—from the initial landing (Browse) to the final transaction (Purchase)—to identify where potential customers drop off. By processing a synthetic dataset of **Session IDs** and **User IDs**, the project provides a comprehensive look at conversion rates, revenue attribution, and temporal session patterns. 

**Key Objectives:**
* **Quantify Conversion:** Measure the efficiency of the marketing funnel across four key stages: Browse, Search, Add to Cart, and Purchase.
* **Identify Friction:** Pinpoint specific stages with the highest "Drop-off Rates" to suggest UI/UX or marketing improvements.
* **Revenue Correlation:** Analyze how session duration and time-of-day impact total revenue and conversion likelihood.
* **Data-Driven Trends:** Provide 30-day performance trends to help stakeholders understand traffic fluctuations and purchase behavior.


---

## Technical Stack
* **Python 3.13+**: Core programming language.
* **Pandas**: Used for complex data aggregation, grouping by `Date` and `Hour`, and calculating unique session counts.
* **Plotly**: Used for the interactive 2x2 Comprehensive Dashboard (Funnel Conversion, Drop-offs, Revenue, and Duration).
* **Matplotlib**: Utilized for daily and hourly performance trend plotting.
* **Seaborn**: Used for advanced statistical visualizations, such as correlation heatmaps and distribution analysis of session metrics.
* **Power BI**: The primary tool for the final multi-page interactive Business Intelligence dashboard, utilizing DAX for advanced measures.

---

## Key Features & Visualizations

### 1. Comprehensive Funnel Analysis (Plotly)
A 4-pane interactive dashboard showing:
* **Funnel Conversion Rates**: Total sessions reaching each stage.
* **Stage-to-Stage Drop-off**: Percentage of users lost at each step.
* **Revenue by Stage**: Total financial value associated with sessions reaching specific funnel depths.
* **Average Session Duration**: Insights into user engagement during different stages of the purchase intent.

### 2. Daily & Hourly Performance (Matplotlib)
* **Traffic Trends**: A line chart showing unique `Session_ID` counts over a 30-day period.
* **Conversion Heat**: Bar charts showing which hours of the day yield the highest conversion rates.

### 3. Power BI Dashboard Features
The final phase of this project involves a professional-grade Power BI report consisting of two key analytical pages:

* **Page 1: Executive Overview**: High-level KPIs including Total Revenue, Unique Sessions, and Overall Conversion Rates.
* **Page 2: Funnel Deep Dive**: Interactive funnel charts that track user movement from 'Browse' to 'Purchase', highlighting stage-to-stage drop-off.
<!--
* **Page 3: Category & Temporal Analysis**:
    * **Revenue by Product Category**: A detailed table breakdown of financial performance across different stock segments.
    * **Daily Session Trends**: A time-series line chart tracking unique visitor volume over a 30-day period.
    * **Interactive Navigation**: Integrated buttons and slicers for dynamic filtering of data.
-->
---

## Preview

| Page 1 | Page 2 |
| :--- | :--- |
| ![Preview 1](https://github.com/amandebnath/funnel-analysis-project/blob/f28bad47732858a67c95b663ddf0870037645727/preview/Preview%201.png) | ![Preview 2](https://github.com/amandebnath/funnel-analysis-project/blob/f28bad47732858a67c95b663ddf0870037645727/preview/Preview%202.png) |
