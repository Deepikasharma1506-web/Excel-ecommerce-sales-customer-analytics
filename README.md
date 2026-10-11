# E-commerce Sales & Customer Analytics Dashboard (Excel)

## Overview
Excel portfolio project using a synthetic 2025 e-commerce order dataset to analyze delivered revenue, estimated profit, category performance, sales channels, regions, and order outcomes.

## Dataset
- 500 synthetic order records
- Five product categories, five regions, and five sales channels
- Currency: INR
- Educational practice data only; not real customer or business records

## Features
- Raw and cleaned data worksheets
- Formula-driven revenue and estimated profit
- Region selector for KPI cards
- KPI cards: delivered revenue, estimated profit, delivered orders, profit margin
- Monthly revenue/profit trend
- Revenue by category and sales channel
- Region, payment method, and order status summaries
- Data dictionary and usage guide

## Data cleaning
- Missing sales channels are labeled `Not specified`.
- Leading/trailing spaces are removed from text fields.
- Raw records are preserved in `Raw_Data`.
- Revenue = `Quantity × Unit_Price_INR × (1 - Discount_Rate)`.
- Estimated profit = `Revenue_INR - Estimated_Cost_INR`.
- Dashboard KPI revenue and profit include only orders marked `Delivered`.

## Workbook tabs
- `Dashboard`: KPI cards and charts; select region in B4.
- `Raw_Data`: original synthetic records.
- `Clean_Data`: cleaned records and calculated fields.
- `Analysis`: formula-driven summary tables.
- `Data_Dictionary`: column definitions.
- `Start_Here`: instructions and assumptions.

## Limitations
The dataset is synthetic. Costs and profit are estimated. Returned and cancelled orders are excluded from delivered revenue KPI cards, but shown in order-status analysis. Charts show overall dataset summaries; only KPI cards respond to the region selector.

## How to use
Open `workbook/Ecommerce_Sales_Customer_Analytics_Dashboard.xlsx` in Excel and allow formulas to recalculate. On Dashboard, change `B4` to All, North, South, East, West, or Central.
