# Retail Sales Performance Dashboard (Power BI)

## Project Overview
This project presents an interactive **Power BI dashboard** built to visualize and communicate business insights derived from a retail sales dataset. The dashboard translates SQL-based analysis into clear, actionable visualizations for stakeholders, covering sales performance, profitability, customer behavior, and regional trends.

---

## Dataset
- **Source:** OpenDataBay – Retail Sales Analytics Dataset  
- **Total Records:** 1,195  
- **Key Fields:**  
  Order Date, Category, Sub-Category, Sales Amount, Profit, Quantity,  
  Customer Name, City, State, Payment Mode

---

## Tools & Technologies
- **Power BI Desktop**
- **Power Query** (data cleaning and transformation)
- **DAX** (KPIs and calculated measures)
- **PostgreSQL** (upstream SQL analysis)

🔗 **Related SQL Analysis Repository:**  
[Retail-Sales-SQL-Analytics](https://github.com/Sreenivasan05/Retail-Sales-SQL-Analytics)

---

## Dashboard Structure
The dashboard consists of **5 analytical pages**, each designed to answer specific business questions:

### Executive Overview
- Total Sales, Total Profit, Quantity Sold, Profit Margin
- Category-wise sales and profit comparison
- High-level performance snapshot

### Sales & Profit Trends
- Monthly sales and profit trends
- Identification of best and worst performing periods
- Seasonal pattern analysis

### Category & Sub-Category Analysis
- Sales distribution across categories and sub-categories
- Profitability comparison at sub-category level
- Identification of high-margin and underperforming products

### Customer Analytics
- Top 10 customers by revenue
- Repeat vs one-time customer analysis
- Customer contribution and ranking

### Geography & Payment Insights
- State-wise sales performance
- Cities with high sales but low profitability
- Payment mode preference analysis

---

## Key Business Insights
- Revenue and profit are **balanced across major categories**, reducing reliance on a single product line.
- Certain sub-categories contribute **disproportionately high profit margins**, making them strategic focus areas.
- Sales show **consistent growth with seasonal fluctuations**.
- **Repeat customers (~58%)** contribute significantly to overall revenue.
- Some high-sales cities exhibit **lower profit margins**, indicating optimization opportunities.

---

## Data Preparation
- Verified and corrected data types in Power Query
- Created calculated measures for:
  - Total Sales
  - Total Profit
  - Profit Margin
  - Customer segmentation
- Applied slicers for dynamic filtering by year, category, and region

