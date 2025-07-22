# Mexico_Toys

✅ Objective:
- To analyze toy sales data in Mexico to uncover key revenue drivers, optimize inventory, and make data-backed business recommendations.

![image alt](https://github.com/SarthakUdavant/Mexico_Toys/blob/main/Screenshots/Toysss..png)

📌 Key Areas of Analysis:
- Sales performance by region and channel
- Product-wise revenue and profit
- Customer segmentation & purchasing patterns
- Inventory levels vs. demand
- Seasonal and monthly trends

📊 Data Sources:
- Sales Transactions Table
- Product Master Table
- Customer Demographics
- Regional/Store Information
- Inventory Levels

🛠️ Tools Used:
- Power BI Desktop (for data modeling & visualization)
- DAX (for calculated columns/measures)
- Power Query (for ETL)

![image alt](https://github.com/SarthakUdavant/Mexico_Toys/blob/main/Screenshots/Screenshot%202025-07-22%20221906.png)

![image alt](https://github.com/SarthakUdavant/Mexico_Toys/blob/main/Screenshots/Screenshot%202025-07-22%20221930.png)


🧹 Data Cleaning (ETL Process):
- Removed null and duplicate values
- Standardized column names
- Merged lookup tables (Product, Region, Customer)
- Transformed date formats
- Created date table for time intelligence

🏗️ Data Modeling:
- Star schema with fact table (Sales)
- Dimensions: Date, Product, Region, Customer
- Relationships defined via keys (1:Many)
- Created KPIs using DAX (Revenue, Units Sold, Profit Margin)

🌟 Key Highlights:
- Most profitable category: Educational Toys
- Best performing region: Central Mexico
- Highest sales in Q4, peaking in December
- Online sales channel outperformed in revenue vs. retail

🔍 Top Insights:
- 20% of products generate 80% of revenue (Pareto principle)
- Customer segment "Parents with kids under 10" shows highest repeat purchase
- Certain SKUs frequently go out of stock, affecting potential sales

💵 Sales & Revenue Recommendations:
- Focus marketing on top 3 product categories
- Introduce promotions during Q2 to balance revenue distribution
- Expand online sales channel further due to strong performance

📦 Inventory & Product Recommendations:
- Increase inventory buffer for top 10 selling products
- Phase out underperforming SKUs with <5% contribution
- Align procurement with seasonal trends to reduce overstock
