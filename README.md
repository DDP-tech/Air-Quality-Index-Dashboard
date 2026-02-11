# India Air Quality Index Dashboard

## Project Overview

This project presents an interactive **India Air Quality Index (AQI) Dashboard** built using **Power BI**. The dashboard analyzes air quality patterns across Indian cities using a large-scale AQI dataset (800k+ records), focusing on trends, pollutant contribution, seasonal variation, meteorological impact, and health-based AQI categories.

The dashboard applies time-series analysis, categorical aggregation, and DAX-based measures to explore air quality variations across time, location, and environmental factors.

![AQI Dashboard](https://i.ibb.co/RGBSXbXz/AQI-Dashboard.png)

---

## Key Objectives

* Assess overall air quality levels across Indian cities
* Identify locations with consistently high AQI
* Analyze seasonal and time-based AQI patterns
* Compare year-over-year AQI trends
* Understand pollutant and wind impact on AQI
* Present health-based AQI category distribution using official standards

---

## Dataset Summary

* Geographic coverage: Indian cities
* Time span: Multi-year (2022–2025)
* Granularity: Hourly observations
* Size: 842,015 records

### Dataset Source

The dataset used in this project is publicly available on [Kaggle – Air Quality Dataset (Indian Cities 2022–2025)](https://www.kaggle.com/datasets/bhautikvekariya21/air-quality-dataset-indian-cities-2022-2025).

### Data Scope

* AQI standard used: **US AQI** (widely adopted in Indian AQI datasets)
* EU AQI metrics were intentionally removed to maintain a single, consistent AQI framework
* Dataset optimized by removing low-impact meteorological columns to reduce file size and improve performance

---

## Dashboard Features

### KPI Highlights

* Average AQI
* Maximum AQI recorded
* Average PM2.5 concentration
* Percentage of unhealthy AQI records
* Total AQI observations

### Core Visuals

* Average AQI by City
* AQI Trend Over Time (multi-line, year-over-year comparison)
* AQI by Time of Day
* Pollutant Contribution
* Wind Impact on Air Quality
* AQI Category Distribution

### Interactive Slicers

* Year
* Season

All visuals are fully interactive and respond dynamically to slicer selections.

---

## Data Modeling & DAX

The model follows Power BI best practices:

* **Calculated Columns** for categories, labels, and sorting (Month Name, AQI Category Display, AQI Category Order)
* **Measures** for aggregations, KPIs, percentages, and trends

DAX is used for:

* AQI aggregations and KPIs
* Percentage of unhealthy air quality records
* Year-over-year trend analysis
* Health-category–based filtering and sorting

---

## Tools & Technologies

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Power Query (data transformation and optimization)

---

## Future Improvements

* Expand the dashboard into a **multi-page Power BI report** for deeper analysis
* Add state-level drill-down and comparison pages
* Include map-based AQI visualizations for spatial analysis

---
**Created By :-** Divyadarshan Pattanayak\
**Date :-** December 2025
