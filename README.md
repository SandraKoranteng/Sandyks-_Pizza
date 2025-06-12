# Sandyks-_Pizza
Power BI dashboard and analysis for Sandyks'_Pizza (Mavern Pizza Challenge)

**Project Objectives**
Sandyks'_Pizza, a Greek-inspired restaurant in New Jersey, collected transactional data for the past year and needed help using it to improve operations. As a Data Analyst, my role is to analyze the data and answer the following key questions:
1. How many customers do we have each day? Are there any peak hours?
2. How many pizzas are typically in an order? Do we have any bestsellers?
3. How much money did we make this year? Can we identify any seasonality in the sales?
4. Are there any pizzas we should take off the menu, or any promotions we could leverage?

**Methodology**
1. Data Import. Cleaned in Excel and loaded into Power BI
2. Data Transformation
a. Extracted date and time elements (hour, day, month)
b. Created calculated columns and measures using DAX
3. Data Modeling
a. One main table used: order_details
b. Relationships established as needed between order_details and Caledendar
4. Visualizations Created
a. KPI Cards (Revenue, Orders, Avg Pizzas per Order)
b. Line charts (Orders per Hour, Monthly Revenue)
c. Bar charts (Best/Worst Selling Pizzas)
d. Slicers for interactivity

**Dashboard Overview**
![Dashboard Preview](Dashboard.png)

**Dashboard Features**
Total Revenue and Orders KPIs
Peak Hour Analysis
Orders Per Day and Weekly Trends
Best and Worst Selling Pizzas
Monthly Revenue Trends & Seasonality
Interactive slicers for date and pizza type

**Insights & Recommendations**
1. Orders peak around 12 PM, suggesting targeted lunch promotions.
2. Top-selling pizzas such as the Thai Chicken Pizza could be bundled for combo deals.
3. Low-performing pizzas such as The Brie Carre Pizza could be reviewed for removal or marketing.
4. Revenue spikes in May and July, indicating seasonal patterns.

**How to Use**
1. Download the pizza project file.
2. Open it in Power BI Desktop.
3. Interact with slicers and visuals to explore trends and patterns.

**Credits**
Data source: Maven Analytics - Maven Pizza Challenge
Dashboard built by: **Sandra Koranteng**
Tools: Excel, Microsoft Power BI, DAX, GitHub

