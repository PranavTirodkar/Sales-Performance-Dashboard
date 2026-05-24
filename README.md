# Global Sales Performance Dashboard

An interactive Power BI dashboard designed to analyze and track key retail performance indicators, including sales revenue, cost distributions, overall profitability, and regional sales trends across multiple fiscal years.

![Dashboard Preview](Screenshot(1052).png)

## 📊 Executive Summary
This dashboard provides a comprehensive macro-level view of organizational performance. It highlights key financial figures such as total sales, operational costs, profit margins, and categorizes performance by product type, sales channel, and geographic region.

### Key Performance Indicators (KPIs)
* **Total Sales:** \$109.81M
* **Total Cost:** \$97.26M
* **Total Profit:** \$12.55M
* **Overall Profit Margin:** 11.43% *(Calculated as Profit / Total Sales)*

---

## 🔍 Visualizations & Insights Breakdown

### 1. Fiscal Year Filter
* Located at the top of the canvas, users can dynamically slice data across multiple years (**FY2018, FY2019, FY2020, and FY2021**).

### 2. Financial Performance Metrics (Cards)
* Displays high-level summaries for immediate status visibility: Sales, Cost, Profit, and Profit Margin.

### 3. Total Sales by Year (Line Chart)
* Evaluates historical performance trends over time. 
* Sales peaked sharply in **2019 at \$43M**, followed by a decline leading into **2020 (\$24M)**.

### 4. Sales by Category (Horizontal Bar Chart)
* Identifies which product categories generate the most revenue.
* **Bikes** dominate the revenue stream by a massive margin, accounting for **\$95M** of total sales, followed remotely by **Components (\$12M)**, **Clothing (\$2M)**, and **Accessories (\$1M)**.

### 5. Global Sales Distribution (Geographic Map)
* Tracks revenue spread across international markets. 
* Key transaction hubs are visible across North America (United States, Canada) and Europe (United Kingdom, France, Germany).

### 6. Slicers (Left Sidebar)
* **Category Filter:** Allows deep-dives into Accessories, Bikes, Clothing, or Components.
* **Channel Filter:** Segments data by **Internet** (B2C) and **Reseller** (B2B) sales avenues.

---

## 🛠️ Data Architecture & Modeling
The project utilizes a clean Star Schema design structure comprising the following tables (visible in the data pane):
* **Fact Tables:** `Sales_data`
* **Dimension Tables:** `Customer_data`, `Date_data`, `Product_data`, `Reseller_data`, `Sales Order_data`, `Sales Territory_data`

---

## 🚀 How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have **Power BI Desktop** installed.
3. Open the `.pbix` file included in this repository.
4. *(Optional)* If data paths are broken, re-map the data sources to the included dummy datasets or your local database.

---

## 🛠️ Tech Stack Used
* **Business Intelligence Tool:** Microsoft Power BI Desktop
* **Data Source mapping:** Star Schema Architecture
* **Mapping API:** Bing Maps Integration
