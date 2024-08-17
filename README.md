# Global Electronics Data Analysis Project

## Overview

This project focuses on analyzing data from Global Electronics to extract key insights that will enhance marketing strategies, optimize inventory management, and improve sales forecasting. The project involves data cleaning and preparation, SQL database creation, and the development of interactive dashboards using Power BI.

## Project Workflow

### 1. Data Collection
- **Source Files:**
  - CSV Files: `sales.csv`, `customers.csv`, `products.csv`, `stores.csv`, `exchange_rates.csv`

### 2. Data Cleaning and Preparation
- Checked for missing values and handled them.
- Converted data types (e.g., dates, numeric fields).
- Merged datasets (e.g., linking sales data with product and customer data).
- Ensured data integrity before loading into the database.

### 3. Database Creation
- **Database:** dataspark
  - Created tables for `sales`, `customers`, `products`, `stores`, `exchange_rates`.
  - Loaded preprocessed data into tables.
  - Established relationships between tables.

- **Star Schema:**
  - **Fact Table:** `sales`
  - **Dimension Tables:** `products`, `customers`, `exchange_rates`, `stores`

### 4. SQL Queries
- Customer Analysis: Gender, age, location, and purchase behavior.
- Sales Trends: Performance over time.
- Product Performance: Top-selling products and profitability.
- Store Performance: Sales by region and store.

### 5. Power BI Dashboard Creation
- **Data Import:**
  - Connected to the MySQL database and imported data into Power BI.
  - Defined relationships between tables in the Model view.

- **Visualizations:**
  - Customer distribution by region (Pie Chart).
  - Sales trends over time (Line Chart).
  - Top 5 best-selling products (Pie Chart).
  - Store performance by region (Map).

## Tools and Technologies
- **Python & Pandas:** Data cleaning and preparation.
- **MySQL:** Database management.
- **Power BI:** Interactive dashboard creation.

## Installation and Setup

### Prerequisites
- MySQL Workbench
- Power BI Desktop
- Python (with Pandas and MySql)

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Shabanabacker/globalelectronics-data-analysis.git