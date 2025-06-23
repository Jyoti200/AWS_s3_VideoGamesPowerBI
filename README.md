# 🎮 Video Games Dashboard

##  Problem Statement

This dashboard provides actionable insights into the global video game industry by analysing trends in sales across various genres, platforms, and regions. It enables stakeholders—including developers, publishers, marketers, and analysts—to make data-driven decisions by highlighting:

* The most successful publishers
* Popular game categories
* Regional preferences and performance
* Sales patterns over time

---

## Steps Followed

**Step 1: Data Connection**
Connected Power BI to AWS S3 using Amazon Athena via the ODBC connector. Queried multiple CSV files stored in S3 using SQL through Athena.

** Step 2: Data Integration**
Appended multiple datasets (e.g., sales by region or time) into a unified table using Power Query.

**Step 3: Data Cleaning & Transformation**

* Standardized column names and data types
* Removed rows with missing values in critical fields (e.g., `Year`, `Publisher`, `Global_Sales`)
* Removed duplicates and trimmed inconsistent text entries

** Step 4: Data Quality Checks**
Enabled column profiling and verified quality using:

* Column Distribution
* Column Profile
* Column Quality

**Step 5: Interactive Visualizations**
Created a range of visuals for exploration and analysis:

* **Bar Charts**: Top 10 games, top publishers
* **Line Charts**: Game release trends across years
* **Waterfall Charts**: Regional sales by genre
* **Card Visuals**: KPIs like total sales, number of games, top publisher
* **Slicers**: Platform, Publisher, Year, Genre, Region

**Step 6: UX Enhancements**
Applied custom themes, titles, and explanatory text boxes to improve user experience and storytelling.

---

## 📸 Snapshots

*Power BI Desktop Visuals*
Link: https://youtu.be/fJg3IIQ0vP4

##  Key Insights

### Top Games

* **Global Bestseller**: *Wii Sports* (80M+ units)
* **Top in NA & EU**: *GTA V*, *Call of Duty* series
* **Top in Japan**: *Pokémon Red/Blue/Green*

###  Platform Trends

* Most Lucrative Platforms:

  * **PS2** (Highest number of bestsellers)
  * **Xbox 360**, **Wii**

### Genre Preferences

* **Globally**: Action, Shooter, Sports
* **Japan**: Role-Playing Games (RPGs)
* **NA & EU**: Shooter and Sports

### Publisher Performance

* Leading Publishers by Global Sales:

  * **Nintendo**
  * **Electronic Arts**
  * **Activision**

### Time Trends

* **Peak Release Years**: 2006–2010
* **Sales Trend**: Noticeable decline after 2012 (based on dataset availability)

---

## Summary

This Power BI dashboard integrates video game sales data via AWS S3 and Amazon Athena, transforming it into a dynamic tool for industry analysis. With comprehensive filters and engaging visuals, it answers:

* What games and genres dominate globally and regionally?
* Which publishers consistently release hits?
* Which platforms yield the highest returns?
* How have game sales evolved over the years?

Whether you're a **game developer**, **investor**, **marketer**, or simply a **curious gamer**, this dashboard offers valuable insights into the evolving video game landscape.

