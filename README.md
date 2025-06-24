# Sales-Data-Analysis
#  Vrinda Store - 2022 Excel Sales Dashboard

##  Project Objective

Vrinda Store aims to analyze its 2022 annual sales performance to understand customer behavior, identify top-performing products and cities, track monthly sales trends, and use these insights to drive more sales in 2023. This project delivers an interactive Excel dashboard that summarizes key metrics and trends.

---

##  Tools & Techniques Used

| Tool             | Purpose                                           |
|------------------|---------------------------------------------------|
| **Microsoft Excel** | Data analysis and dashboard creation              |
| **Power Query**     | Data cleaning, transformation, and ETL           |
| **Pivot Tables**    | Aggregated calculations and modeling             |
| **Pivot Charts**    | Visual representation of trends and KPIs         |
| **Slicers**         | Interactive filters for dynamic analysis         |
| **Conditional Formatting** | Highlighting trends and exceptions         |

---

##  Step-by-Step Implementation

### 1️. Data Cleaning (Power Query)
- Imported raw dataset into Power Query
- Removed unnecessary columns and duplicates
- Ensured correct data types for fields like `Date`, `Qty`, `Amount`
- Created calculated columns:
  - `Year` → `= Date.Year([Date])`
  - `Month` → `= Date.MonthName([Date])`
- Loaded clean data into Excel Data Model

### 2️. Creating Pivot Tables
Generated pivot tables for:
- Monthly Sales Trends
- Top 5 Cities by Total Sales
- Sales by Channel (Retail, Export, Distributor, etc.)
- Top Products Performance
- Customer-wise Sales Comparison

### 3️. Building the Dashboard
- Created a new dashboard worksheet
- Designed KPI Cards:
  -  Total Sales
  -  Products Sold
  -  Profit Margin (assumed)
  -  Customer Count
- Added Pivot Charts:
  - Clustered Column for Monthly Sales (2022 vs 2021)
  - Pie Chart for Top 5 Cities
  - Bar Chart for Top Products (YoY % change)
  - Area Chart for Product Trends
  - Bar Chart for Customer Sales Comparison
- Inserted Slicers:
  - City
  - Month
  - Channel
  - Category

### 4️. Styling and Formatting
- Unified fonts, layout, and color scheme
- Applied conditional formatting for YoY changes
- Added chart titles, axis labels, and slicer headers

---

## 5. Dashboard Insights

| Metric              | Value (Sample)       |
|---------------------|----------------------|
| Total Sales         | ₹48.5M               |
| Products Sold       | 21.4K Units          |
| Profit Margin       | 37.8%                |
| Top Cities          | Christchurch, Hamilton, Waitakere |
| Key Sales Channels  | Distributor, Wholesale, Export   |

---

## 6. Insights found

-  Women are more likely to buy compared to men (~65%)
-  Maharashtra, Karnataka, and Uttar Pradesh are the top 3 contributing states
-  Adult age group (30–49 years) contributes the most (~50%)
-  Amazon, Flipkart, and Myntra are the top-performing sales channels

---

## 7. Final Conclusion to Improve Vrinda Store Sales

 **Target women customers aged 30–49 years**  
 Living in: **Maharashtra, Karnataka, and Uttar Pradesh**  
 Promote via: **Amazon, Flipkart, and Myntra**  
 Use personalized ads, offers, and coupons across these platforms to boost 2023 sales.

---

## 8. Dashboard Preview

Below is the complete Excel dashboard built for Vrinda Store:

![Dashboard Preview](https://github.com/Rudranee-1/Sales-Data-Analysis/blob/main/Final%20Report.jpg?raw=true)




---




