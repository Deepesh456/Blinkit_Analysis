# Blinkit Sales Performance Dashboard

## 1. Overview

- Comprehensive Power BI sales performance dashboard for Blinkit
- Focused on analyzing product sales, outlet characteristics, and customer purchasing patterns
- Enables data-driven decision making for revenue optimization and business growth

## 2. Features

- Interactive slicers:
  - Item Type
  - Outlet Type
  - Fat Content
  - Outlet Location Type
- KPI cards summarizing:
  - Total Sales
  - Average Item MRP
  - Average Sales per Transaction
  - Distinct Outlets
- Advanced visuals:
  - Average Sales by Year line chart
  - Sales by Outlet Size donut chart
  - Total Sales by Fat Content and Location Type stacked column chart
  - Top 5 Selling Item Types clustered bar chart
  - Average Item Weight vs Average Sales by Item Type scatter plot

## 3. Data Preparation

- Cleaned raw data using Power Query:
  - Removed duplicate records
  - Replaced missing `Outlet_Size` values with "Unknown"
  - Standardized `Item_Fat_Content`:
    - Replaced "LF" with "Low Fat"
    - Replaced "reg" with "Regular"
    - Applied proper case formatting
  - Standardized numeric data types
  - Validated and corrected date fields
- Applied consistent column naming for clarity

## 4. Data Modeling

- Created DAX measures:
  - Total Sales
  - Average Sales
  - Median Sales
  - Average Item MRP
  - Distinct Outlet Count
  - Average Sales per Year
  - Average Sales per Transaction
  - Percent of Total Sales
- Applied Indian Rupee (₹) formatting to all currency measures
- Standardized decimal and thousand separators for readability

## 5. Design Elements

- Used Blinkit brand colors (yellow and green)
- Segoe UI font for a modern, business-oriented style
- Snap-to-grid alignment for consistent layout
- Clean, descriptive chart titles
- Page resolution set to 1920x1080 for high-quality display
- Structured layout progressing from high-level KPIs to detailed analysis

## 6. Tools Used

- Power BI Desktop
- Power Query for ETL transformations
- DAX for calculations and metrics

## 7. Repository Contents

- `BLINKIT.pbix` : fully interactive Power BI report file  
- `Blinkit_Analysis.png` : high-resolution exported PNG of the final dashboard  
- `Blinkit_Analysis.xlsx` : cleaned and prepared dataset used for the report  
- `README.md` : this documentation file describing the project

## 8. Summary

This project demonstrates end-to-end skills in data cleaning, data modeling, Power Query transformations, DAX measure building, and dashboard storytelling with Power BI. It simulates a real-world retail business case and is designed to highlight interactive business intelligence for portfolio and professional networking.
