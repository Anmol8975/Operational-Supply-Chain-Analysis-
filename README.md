# End-to-End Supply Chain & Sales Analytics Dashboard | Power BI
### Project Overview

I built an End-to-End Supply Chain & Business Performance Dashboard in Power BI to analyze and monitor different operational areas of a business including Logistics, Procurement, Inventory Management, and Sales Performance.

The goal of this project was to transform raw operational data into actionable business insights using interactive dashboards and advanced Power BI features.

The dashboard enables stakeholders to easily track KPIs, analyze trends, and drill into detailed insights across multiple years and global regions.

 ### Business Problem

Supply chain and sales operations generate large volumes of data across different functions such as logistics, procurement, inventory, and sales.

Without a centralized analytics solution, it becomes difficult to:

* Track shipment performance

* Evaluate supplier efficiency

* Monitor inventory levels

* Analyze regional revenue contribution

* Identify operational bottlenecks

This dashboard solves these problems by providing a unified analytics platform for operational and strategic decision making.

## Dashboard Modules

The project is divided into four major analytical modules:

  ### 1. Sales & Revenue Performance

This section evaluates overall business performance from a revenue and profitability perspective.

#### Key insights include:

* Revenue vs Target

* Profit vs Goal

* Total Orders

* Average Order Value

* Analysis includes:

* Revenue contribution by region

* Profit trends over time

* Brand-level revenue performance

* Customer tier distribution (Gold, Silver, Bronze)

A scatter analysis of Discount vs Profit helps identify the relationship between promotional discounts and profitability.

### 2. Inventory Analytics

The inventory module focuses on warehouse capacity, stock levels, and inventory movement.

#### Key metrics:

* Capacity Utilization

* Total Inventory Value

* Safety Stock Level

* Units on Hand

* Units in Transit

### Analysis includes:

* Warehouse-level inventory distribution

* Units currently in transit across warehouses

This helps businesses optimize inventory planning and warehouse management

### 3. Procurement & Supplier Performance

This section evaluates supplier efficiency and procurement operations.

#### KPIs monitored:

* Average Delay Time

* Average Delivery Time

* On-Time Delivery %

* Total Purchase Orders

* Total Purchase Cost

#### Analysis includes:

* Freight cost trends across years

* Supplier-wise order distribution

* Monthly procurement spending patterns

#### This page helps identify:

* Reliable suppliers

* Procurement bottlenecks

* Cost trends in supply chain operations

#### 4. Logistics & Order Fulfillment Performance

This page focuses on shipment efficiency and logistics operations.

#### Key metrics analyzed:

* Total Shipment Orders

* Total Quantity Shipped

* Fill Rate %

* Average Shipment Time

* Insights include:

* Yearly shipment trends

* Quantity ordered vs quantity shipped

* Carrier performance comparison

* Shipment method analysis (Road, Sea, Air)

* Warehouse shipment distribution

Interactive features allow users to drill down into yearly logistics performance and warehouse-level shipment data.

## Technical Implementation
#### Data Cleaning & Transformation

 Data preprocessing was performed using Power Query, including:

* Handling missing values

* Data type corrections

* Removing duplicates

* Column standardization

* Creating calculated columns


## Data Modeling

A relational data model was created to connect different datasets such as:

* Order Fullfilment (Facts Table)

* Sales (Facts Table)

* Inventory Snapshots (Facts Table)

* Procurement Purchasing (Facts Table)

* Suppliers (Dimension Table)

* Warehouses (Dimension Table)

* Customers (Dimension Table)

* Geography (Dimension Table)

* Products (Dimension Table)

This improved performance, scalability, and filtering across reports.

## DAX Measures

Custom DAX calculations were created to generate business KPIs such as:

* Fill Rate %

* Average Shipment Time

* On-Time Delivery %

* Revenue

* Profit

* Average Order Value

* Capacity Utilization

* Year-over-Year (YoY %) growth metrics

These measures enabled deeper analytical insights across the dashboard.


## Interactive Features

To enhance user experience and analytical exploration, several Power BI features were implemented:

#### Drill Down / Drill Up

Allows users to navigate between different levels of data such as:

Year → Month → Detailed metrics.

#### Drill Through

Enables users to move from summary dashboards to detailed views for deeper analysis.

#### Bookmarks

Used to create interactive navigation and dynamic report views.

#### Slicers

Users can dynamically filter the dashboard by:

* Year

* Region

This enables flexible analysis across multiple geographic markets.


## Key Insights from the Dashboard

Some major insights that can be derived from the dashboard include:

* Road transport accounts for the majority of shipments compared to sea and air.

* Asia Pacific generates the highest revenue contribution among all regions.

* Certain suppliers consistently receive higher order volumes, indicating strong supplier partnerships.

* Inventory levels show seasonal fluctuations across months.

* Discount levels appear positively correlated with profit growth in several cities.

## Tools & Technologies Used

* Power BI

* Power Query

* DAX (Data Analysis Expressions)

* Data Modeling

* Interactive Dashboard Design

* Bookmarks & Navigation

* Drill Down / Drill Through Analysis

## Skills Demonstrated

* Data Cleaning & Transformation

* Data Modeling

* Business Intelligence Development
 
* KPI Development using DAX

* 8Supply Chain Analytics

* Interactive Dashboard Design

* Business Insight Generation

## Conclusion

 This project demonstrates how Power BI can be used to build a comprehensive business intelligence solution for supply chain and sales analytics.

By combining data modeling, DAX calculations, and interactive visualizations, the dashboard provides a holistic view of operations and enables data-driven decision making.


#### Author 

Anmol Verma | Power BI | SQL | Data Analyst
