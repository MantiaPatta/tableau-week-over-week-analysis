
# Week-over-Week Analysis | Interactive Tableau Dashboard

## Project Overview

This project presents an interactive Tableau dashboard designed to analyze week-over-week (WoW) changes in order demand and delivery performance across 8 cities.

The analysis is based on a synthetic dataset containing 13 months of daily order data.

Users can select any week to compare with the previous one and explore key performance metrics by city or weekday.

## Live Dashboard

🔗 **[Explore the interactive dashboard on Tableau Public] https://public.tableau.com/views/WoWOrdersAnalysisInteractiveDashboard/Demand?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

**Viewing tip:** Use the scrollbars to locate the Full Screen button in the bottom-right corner. Then adjust your browser's zoom level (Ctrl + / Ctrl -) to fit the dashboard to your screen.


## Dataset

The project uses a synthetic dataset containing 13 months of daily order and delivery performance data across 8 cities.

The dataset consists of the following 7 columns:

| Column | Description |
|---|---|
| `CITY` | City where orders were placed |
| `YEAR` | Year of the recorded data |
| `MONTH` | Month of the recorded data |
| `DAY` | Day of the month |
| `ORDERS_COUNT` | Total number of orders |
| `AVG_DELIVERY_TIME_MINUTES` | Average delivery time in minutes |
| `ORDERS_LATE_PERCENTAGE` | Percentage of orders delivered late |

These fields are used to calculate and visualize week-over-week changes in order demand and delivery performance.


## Key Metrics

The dashboard focuses on three main areas:

**1. Order Demand**
- Total orders per week
- Week-over-week percentage change in orders
- Demand trends by city and weekday

**2. Delivery Time**
- Average delivery time
- Week-over-week changes in delivery time
- Delivery time comparisons by city and weekday

**3. Late Deliveries**
- Late order rate
- Week-over-week changes in late order rate
- Late delivery comparisons by city and weekday

## Dashboard Features

- Dynamic week selection for WoW comparisons
- Interactive KPI cards
- City and weekday filters
- Parameters and calculated fields
- Dashboard actions and interactive visualizations
- Order-weighted calculations for average delivery time and late order rate
- Dynamic comparisons across different time periods

## Dashboard Screenshots

### 1. Demand Analysis

Explore week-over-week changes in order volume and identify demand patterns across cities and weekdays.

![Demand Analysis](screenshots/01-Demand.png)

### 2. Delivery Time by City

Compare average delivery times across cities and identify changes in delivery performance between consecutive weeks.

![Delivery Time by City](screenshots/02-Time%20by%20City.png)

### 3. Delivery Time by Weekday

Analyze delivery time patterns throughout the week and compare performance between consecutive weeks.

![Delivery Time by Weekday](screenshots/03-Time%20by%20Weekday.png)

### 4. Late Orders by City

Examine late order rates across cities and identify week-over-week changes in delivery reliability.

![Late Orders by City](screenshots/04-Late%20Orders%20by%20City.png)

### 5. Late Orders by Weekday

Explore late delivery patterns by weekday and compare late order rates between consecutive weeks.

![Late Orders by Weekday](screenshots/05-Late%20Orders%20by%20Weekday.png)

## Tools & Skills

**Tools:**
- Tableau Desktop
- Tableau Public

**Technical Skills:**
- Calculated Fields
- Parameters
- Dashboard Actions
- Interactive Filters
- Weighted Aggregations
- Week-over-Week Analysis
- Data Visualization
- KPI Development

## Project Purpose

The goal of this project was to develop a flexible, interactive BI dashboard that enables users to monitor changes in order demand and delivery performance.

By combining dynamic week selection, interactive filters, and multiple analytical views, the dashboard allows users to identify trends, compare city-level performance, and explore potential areas for operational improvement.

*This project was developed using synthetic data for portfolio and educational purposes.*
