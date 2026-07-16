# Coffee Orders Sales Dashboard (Excel)

An end-to-end Excel analytics project covering data cleaning, multi-table lookups, pivot analysis, and an interactive sales dashboard built on a coffee orders dataset.

---

## Tools & Technologies
- **Microsoft Excel** — data cleaning, XLOOKUP, pivot tables, dashboard

---

## Dataset
**Source:** Coffee orders dataset with 3 related tables — orders, customers, products  
**Key fields:** Order ID, Order Date, Customer, Country, Coffee Type, Roast Type, Size, Unit Price, Sales

---

## Project File

📊 **[View Full Excel Dashboard (Google Drive)](https://docs.google.com/spreadsheets/d/1l3Eq_ODl7kCps_jXxJlXpMdQDadUqozi/edit?usp=sharing)**

> File is too large for GitHub — hosted on Google Drive. Download or open directly in Excel/Google Sheets.

**Workbook Sheets:**
- `orders` — raw orders data
- `customers` — customer master table
- `products` — product details with pricing
- `worksheetorders` — cleaned and enriched orders (XLOOKUP applied)
- `PIVOT1`, `PIVOT2` — pivot table analysis
- `COFFEE DASHBOARD` — final interactive dashboard with slicers

---

## What Was Done

**Data Cleaning:**
- Standardized date formats and coffee type/roast type codes
- Handled missing values in customer and product fields
- Removed inconsistencies across order records

**Data Enrichment (XLOOKUP):**
- Pulled Customer Name, Email, Country from the customers table into orders
- Pulled Coffee Type, Roast Type, Size, Unit Price from the products table
- Calculated Sales = Quantity × Unit Price

**Pivot Analysis:**
- Sales by coffee type and roast type
- Sales trend over time
- Top customers by revenue
- Sales breakdown by country

**Dashboard:**
- Interactive slicers for Coffee Type, Roast Type, Size, and time period
- Visual summary of key sales metrics

---

## How to Open
- Download and open `coffeeOrdersData.xlsx` in Microsoft Excel
- Navigate to the **COFFEE DASHBOARD** sheet to explore the interactive dashboard
- Use slicers to filter by coffee type, roast, size, or time period

---

## Author
**Sanskriti Kesharwani** | B.Tech Mechanical Engineering, MANIT Bhopal  
Aspiring Data & Business Analyst | Sales & Operations Analytics
