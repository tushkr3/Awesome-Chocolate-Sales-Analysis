# Awesome Chocolate Sales Dashboard  

This repository contains an analysis of chocolate sales, shipments, and product performance using **Excel (Power BI data model)**. It includes an Excel workbook with raw and dimension data, and a Power BI dashboard for visualization of key metrics.  

---

## Repository Contents  

### 1. Excel Workbook: `ac-sample-data.xlsx`  
This file contains three sheets:  

#### **Shipment Data**  
- Contains transactional shipment details such as:  
  - Order Number  
  - Delivery Dates  
  - Quantities Shipped  
  - Related Costs  

#### **Dimension Data**  
- Provides contextual information, including:  
  - Product: Chocolate item names.  
  - Category: Bars, Bites, and Others.  
  - Cost per Box: Base cost for profitability analysis.  
  - Geo & Region: Country and region details (India, USA, Canada, UK, Australia, etc.).  
  - Sales Person & Team: Individual sales representatives and their assigned teams.  
  - Picture URLs: Representative profile pictures for visualization.  

#### **Calendar Table**  
- Date reference table used for time intelligence and trend analysis.  

---

### 2. Power BI Dashboard  
This dashboard leverages the above data to provide:  
- KPIs such as **Total Sales**, **Items Sold**, **Shipments**, and **Customers**.  
- Monthly trend analysis (Sales, Costs, Boxes Sold, Profits).  
- Sales performance by category (Bars, Bites, Others).  
- Shipments by country and region.  
- Sales personnel and product-level performance with profit margins.  
- Achievement vs Target gauge.  

---

## Key Analysis  

The dashboard answers the following questions:  

1. **What are the overall sales, shipments, and customers served?**  
   - Total Sales: $34M  
   - Total Items Sold: 2M  
   - Total Shipments: 6,000  
   - Total Customers: 14M  

2. **Which product categories are most popular?**  
   - Bars are the top-selling category, followed by Bites and Others.  

3. **Which regions and countries drive the most shipments?**  
   - Australia leads in shipments, followed by Canada, India, UK, and USA.  

4. **Who are the top-performing sales personnel?**  
   - Conditional formatting highlights high achievers such as *Kein Walkden* and *Rafschta Blaksland*.  

5. **What products generate the highest profit margins?**  
   - *Peanut Butter Cubes*: $2,029K sales with 87.1% profit margin.  
   - *99% Dark & Pure*, *Manuka Honey Choco*, *Smooth Silky Salty* also show strong performance.  

6. **How do sales, costs, and profits trend over time?**  
   - Monthly KPIs reveal seasonal peaks and troughs (2021–2024).  

---

## How to Use  

### Excel Workbook  
- Open `ac-sample-data.xlsx` to explore **Shipment Data**, **Dimension Data**, and the **Calendar Table**.  
- Use it for further calculations, pivot tables, or to extend Power BI dashboards.  

### Power BI Dashboard  
- Import the workbook into Power BI Desktop.  
- Explore dashboards with slicers, KPIs, and dynamic trends.  
- Use bookmarks, tooltips, and conditional formatting to analyze insights interactively.  

---

## Prerequisites  

- **Excel**: Microsoft Excel or equivalent to view `.xlsx` files.  
- **Power BI**: To open and interact with the dashboard.  

---

## Future Work  

- Enhance dashboard with **advanced DAX calculations**.  
- Add **Python/R scripts** for automated data processing and advanced analytics.  
- Extend analysis with **trend predictions** (forecasting).  
- Develop **interactive web dashboards** using Tableau/Plotly.  

---

## License  

This project is open-source and available under the **MIT License**.  
