# Blinkit Sales Performance Analysis — Portfolio Documentation

## Executive Summary

I built an interactive **Power BI dashboard** to analyze **Blinkit’s sales performance, customer satisfaction, and inventory distribution**. The report helps stakeholders quickly identify which product attributes (e.g., fat content and item type) and **outlet characteristics** (e.g., establishment year/type) drive sales and ratings, and where to optimize stock allocation.

## Objectives

* Conduct a comprehensive analysis of sales performance, customer satisfaction, and inventory distribution.
* Identify optimization opportunities using KPIs and visual analytics.

## Data & Model Overview

* **Data source**: Blinkit sales dataset (imported into Power BI).
* **Core entities** : Items, Outlets, Sales/Transactions, Ratings.
* **Granularity**: Item × Outlet level (row-level transactions or aggregated records depending on source).
* **Relationships**: Star-schema layout (FactSales ↔ Dimension tables like Items, Outlet). (See relationship diagram summary exported.)


## KPIs

* **Total Sales**
* **Average Sales**
* **Number of Items** (sold or catalog count, depending on measure definition)
* **Average Rating**

## Analysis Modules

### 1) Total Sales by Fat Content

**Goal:** Understand how fat content influences sales and customer perception.

* **What to look at:**

  * Total Sales by fat content category.
  * **Average Sales**, **Number of Items**, and **Average Rating** by fat content.
* **Key takeaways (from dashboard):**

  * Top fat content category by **Total Sales**: **\[fill after reading dashboard]**
  * Highest **Average Rating** fat content: **\[fill]**
  * Notable variance in **Average Sales**: **\[fill]**

### 2) Total Sales by Item Type

**Goal:** Identify top-performing product categories.

* **What to look at:**

  * Total Sales by item type.
  * Supporting KPIs (Average Sales, Number of Items, Average Rating).
* **Key takeaways:**

  * Top 3 item types by sales: **\[#1]**, **\[#2]**, **\[#3]**
  * Item type with highest rating: **\[fill]**

### 3) Fat Content by Outlet — Total Sales Comparison

**Goal:** Compare outlet performance segmented by fat content.

* **What to look at:**

  * Matrix/clustered bar: Outlet × Fat Content → Total Sales
  * Compare Average Rating and Average Sales by intersection.
* **Key takeaways:**

  * Best outlet-fat content combination by sales: **\[fill]**
  * Outlets with consistently higher ratings: **\[fill]**

### 4) Total Sales by Outlet Establishment

**Goal:** Evaluate how age/type of outlet influences sales.

* **What to look at:**

  * Total Sales by establishment year/type.
  * Trend vs. age bucket (e.g., ≤5 years, 6–10 years, >10 years).
* **Key takeaways:**

  * Top-performing establishment year/type: **\[fill]**
  * Observed pattern vs. age: **\[fill]**

## Visual Design & Navigation

* **Homepage KPIs:** Card visuals for Total Sales, Average Sales, Items, and Average Rating.
* **Interactive filters:** Slicers for Date/Period , Outlet, Item Type, Fat Content.
* **Charts used:** Clustered bar/column, Matrix, Cards, Tooltips, Conditional formatting.
* **UX details:** Consistent color palette, aligned grid, legible labels, responsive layout.

