# Zepto Product Data Analysis

This project uses SQL to explore, clean, and analyze product-level data from **Zepto**. The dataset includes product categories, prices, discounts, weights, and stock availability, enabling valuable retail insights.

## Features
- **Table Creation**: Builds a `zepto` table with fields for SKU ID, category, name, MRP, discount, stock, and weight.
- **Data Exploration**: 
  - Row counts, sample records, and NULL checks
  - Unique categories and stock status (in-stock vs out-of-stock)
  - Duplicate product detection
- **Data Cleaning**:
  - Removes products with zero price
  - Converts paise to rupees for pricing accuracy
- **Analysis Queries**:
  - Top 10 best-value products by discount
  - High-MRP but out-of-stock products
  - Estimated revenue per category
  - Price per gram ranking
  - Weight-based category grouping (Low, Medium, Bulk)
  - Inventory weight distribution

## Tech Stack
- **PostgreSQL** (or any SQL-compatible DB)
- SQL for data cleaning & analytics

## Usage
1. Create the `zepto` table and insert data.
2. Run exploration, cleaning, and analysis queries.
3. Use results to derive pricing, stock, and category-level insights.

