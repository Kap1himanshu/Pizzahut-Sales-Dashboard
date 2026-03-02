# 🍕 Pizza Sales Performance & Customer Behavior Analysis Dashboard

## 1. Project Title / Headline

Pizza Sales Performance & Customer Behavior Analysis Dashboard  

An interactive SQL + Power BI data analytics project built to analyze transactional pizza sales data — focusing on revenue drivers, product performance, seasonal trends, and customer ordering behavior.

---

## 2. Short Description / Purpose

The Pizza Sales Dashboard is a multi-page analytical Power BI report designed to explore one year of transactional sales data.  

The dashboard helps identify revenue trends, best and worst-performing products, seasonal demand spikes, and category-level performance insights.  

This tool is intended for business managers, marketing teams, and operations analysts who want to make data-driven decisions around inventory, promotions, and product strategy.

---

## 3. Tech Stack

The dashboard was built using the following tools and technologies:

• 🗄 SQL – Used for data aggregation, revenue calculations, ranking queries (Top 5 / Bottom 5), and performance validation  
• 📊 Power BI Desktop – Main data visualization platform used for report creation  
• 🔄 Power Query – Data cleaning and transformation layer  
• 🧠 DAX (Data Analysis Expressions) – Used for calculated KPIs such as Total Revenue, Total Orders, and Average Order Value  
• 🔗 Data Modeling – Relationships established between orders, pizzas, categories, and sizes for cross-filtering and aggregation  
• 📁 File Format – `.pbix` for development and `.png` for dashboard previews  

---

## 4. Data Source

Source: Public Pizza Sales Dataset (2015)

The dataset contains one full year of transactional sales data, including:

- Order ID  
- Order Date & Time  
- Pizza Name  
- Category  
- Size  
- Quantity  
- Unit Price  

The dataset allows for time-based, product-level, and category-level analysis across the entire business cycle.

---

## 5. Features / Highlights

### • Business Problem

Sales transactions contain valuable insights, but raw data tables do not clearly answer critical business questions such as:

- Which products drive the highest revenue?  
- Which SKUs are underperforming?  
- When does customer demand peak?  
- How do category and size preferences impact sales?  
- Which months require promotional strategies?  

Management requires structured insights to optimize operations, marketing, and inventory decisions.

---

### • Goal of the Dashboard

To build an interactive analytical tool that:

- Tracks core revenue and order KPIs  
- Identifies top and bottom-performing products  
- Analyzes monthly and weekday demand trends  
- Evaluates category and size contribution  
- Supports data-driven operational and marketing strategies  

---

### • Walkthrough of Key Visuals

## 📊 Page 1 — Sales Overview & Trends

### Key KPIs (Top Section)
- Total Revenue: $817K  
- Total Orders: 21,350  
- Total Pizzas Sold: 49,574  
- Average Order Value  

### Total Orders by Weekday (Bar Chart)
Shows that Friday records the highest number of orders, highlighting strong weekend demand patterns.

### Monthly Trend of Total Orders (Line Chart)
Identifies seasonal peaks in July and January, with noticeable dips in February, September, and October.

### Sales by Category (Donut Chart)
Classic category leads overall contribution, followed by Supreme, Chicken, and Veggie.

### Sales by Size (Donut Chart)
Large size contributes the highest sales volume, indicating strong customer preference.

---

## 🏆 Page 2 — Best & Worst Sellers

### Top 5 Pizzas by Revenue (Bar Chart)
Thai Chicken Pizza consistently generates the highest revenue.

### Top 5 Pizzas by Quantity (Bar Chart)
Classic Deluxe leads in total orders and quantity sold.

### Bottom 5 Pizzas by Revenue & Quantity
Brie Carre Pizza underperforms across all key metrics — revenue, quantity, and total orders.

### Comparative Analysis
Side-by-side Top 5 vs Bottom 5 visualizations highlight product-level performance gaps and investment priorities.

---

## • SQL Analysis Performed

- Revenue aggregation using SUM()  
- Total orders and quantity calculations  
- GROUP BY analysis for category and size-level performance  
- Top 5 and Bottom 5 product ranking using ORDER BY and LIMIT / TOP  
- Monthly and weekday trend analysis using date functions  
- Validation of Power BI results through SQL aggregation queries  

---

## • Business Impact & Insights

• Inventory Optimization: Align stock levels and staffing with weekend demand spikes  
• Product Strategy: Promote high-performing SKUs strategically  
• SKU Rationalization: Re-evaluate or reposition underperforming items  
• Seasonal Campaign Planning: Focus marketing efforts around July & January  
• Promotional Timing: Use low-demand months for targeted discount campaigns  

---

## 🔁 Project Workflow

Raw Transaction Data → SQL Aggregation & Ranking → Insight Validation → Power BI Dashboard Development → Business Recommendations







[# Pizzahut-Sales-Dashboard](https://github.com/Kap1himanshu/Pizzahut-Sales-Dashboard/blob/main/Pizzahut%20Dashboard%20H.jpg)
