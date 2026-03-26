🛍️ Sales Performance Dashboard

Turning Sales Data Into Actionable Decisions

📌 Business Problem
A retail sportswear company selling across multiple retailer channels
(Franchise, Local Store, Supermarket, Small Chain Store)
needed to:
- Track revenue, profit, and cost performance over 4 years (2018–2021)
- Identify top-performing products, categories, and retailer channels
- Analyze return patterns to reduce losses
- Compare current year profit vs last year to spot growth or decline

📁 Dataset
215K total order quantity | 8K orders |1K+products
Fields: Product Name, Category, Size, Color, Gender,
Retailer Channel, Order Date, Sales Amount, Cost, Profit, Return Status

🛠️ Tools Used
Power BI — Data Modeling, DAX Measures, Interactive Dashboards

🧹 Data Cleaning & Transformation
✅ Removed duplicate records to ensure data accuracy
✅ Standardized product sizes and unified units across columns
✅ Unified format for each column (text, numbers, currency)
✅ Converted date columns from numeric format to proper Date type
✅ Handled blank values in Return and Gender fields
✅ Standardized product SKUs and category names

⚙️ DAX Functions Used
 📌 Top One Product Dax Function
 📌 Profit YTD TOTALYTD() for year-to-date profit tracking
 📌 Profit QTD TOTALQTD() for quarter-to-date analysis
 📌 LY ProfitSAMEPERIODLASTYEAR() to compare vs previous year
 📌 Gross Profit %calculated measure for margin analysis
 📌 ROIcustom DAX measure for return on investment
 📌 Growth % DIVIDE() to calculate YoY growth safely
 📌 Avg Cost/Unitnaverage cost per product unit
 📌 Avg Profit Margin calculated measure per month and year
 📌 Drill Through Page 
 📌 ToolTip Page

📊 Dashboard Pages
🏠 Sales Project Cover & navigation page 
📦 Product Analysis 1 Top products by sales, profit matrix (YTD, QTD, LY), order quantity by gender & color 
📈 Product Analysis 2 Revenue vs COGS by category, profit & margin trends by month/year 
🗺️ Product Analysis 3 Sales KPIs, order quantity by retailer channel, sales amount by area (map visual) 
📋 Order Analysis 1 Orders summary table, sales vs COGS scatter, avg price vs quantity 
📊 Order Analysis 2 Order quantity by retailer & category, profitability matrix by year/quarter 
🔄 Returns Analysis Returns by channel, gender, category & trend over time 
💡 InsightsnKey findings summary page 
🔍 Tooltip Page Custom tooltip showing orders count, total profit & LY profit by gender 
 🔎 Drill Through Page Profitability breakdown by product category (YTD vs LY Profit)

💡 Key Insights
- Total Sales £7M | Net Sales £6M | Profit £4M | Cost £3M | Gross Profit 65% | ROI 85%
- Top Product: Hyperion Elements Jacket — highest sales & profit
- Best Category by Revenue:Hoodies & Sweatshirts (£2.8M revenue)
- Top Retailers: Franchise (77K orders) & Local Store (53K orders)
- Best Size in Local Store: Size "S" — 15K orders (29%)
- Best Month for SalesMayBest Profit Months: August & September
- LY Profit > YTD Profitperformance declining vs previous year
- Women don't purchase Lavender dead inventory, optimize stock
- Most Returned Category: Hoodies & Sweatshirts (29% of 548 returns)
- Men return more than Women (57% vs 42%)
- 2021 has the highest returnsquality or sizing issue needs investigation
- Men generate more LY Profit (58%) vs Women (42%)

 ✅ Recommendations
- Focus marketing budget on Franchise & Local Store highest volume channels
- Stock more Size S in Local Stores consistently top seller
- Investigate 2021 returns spike possible quality or sizing issue
- Remove or redesign Lavender for Women's line zero purchases
- Invest more in Hoodies & Jackets top revenue categories
- Address LY Profit > YTD gap review pricing strategy or reduce COGS
- Use **Drill Through** insights to reallocate budget per category performance

📸 Dashboard Preview
![Overview](dashboard%20preview.png/Project%20overview.png)
![Product Analysis 1](dashboard%20preview.png/Product%20Analysis%201.png)
![Product Analysis 2](dashboard%20preview.png/Product%20Analysis%202.png)
![Product Analysis 3](dashboard%20preview.png/Product%20Analysis%203.png)
![Order Analysis 1](dashboard%20preview.png/Order%20Analysis.png)
![Order Analysis 2](dashboard%20preview.png/Order%20Analysis%202.png)
![Returns Analysis](dashboard%20preview.png/Returns%20Analysis.png)
![Insights](dashboard%20preview.png/INSIGHTS.png)
![Tooltip Page](dashboard%20preview.png/ToolTip%20Page.png)
![Drill Through Page](dashboard%20preview.png/Drill%20Through%20Page.png)

