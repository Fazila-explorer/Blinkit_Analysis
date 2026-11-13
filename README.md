# Blinkit_Analysis
This project analyzes Blinkit grocery sales across outlet types, sizes, locations, and product categories to show where sales come from. It uses Excel for data review and Power BI for cleaning, KPIs, and an interactive dashboard. Key findings: sales are driven by volume (average sales per item are about $140 across all outlet types), Tier 3 locations lead at 39.3% of sales, and Fruits & Vegetables plus Snack Foods are the top categories.

Business Question

Which outlet types, locations, and product categories drive Blinkit's sales, and where should the business focus?

Dataset

BlinkIT Grocery Data.xlsx has 8,523 records and 12 columns:

Group	Columns
Item	Item Identifier, Item Type, Item Fat Content, Item Weight, Item Visibility
Outlet	Outlet Identifier, Outlet Establishment Year, Outlet Size, Outlet Location Type, Outlet Type
Performance	Sales, Rating

Tools
Tool	Purpose
Excel	Initial data review and inconsistency checks
Power BI	Data cleaning, KPI cards, visuals, and slicers

Data Preparation
Standardized Item Fat Content, which had inconsistent labels (for example "LF" and "low fat" next to "Low Fat" and "Regular"), into two categories: Low Fat and Regular.
Item Weight has missing values. It is not used in the dashboard metrics, so nothing was imputed.

Dashboard Features
KPI cards: Total Sales, Average Sales, Average Rating, Number of Items
Visuals: Sales by fat content, item type, outlet size, outlet location tier, outlet establishment year, and outlet type
Filters: Outlet Location Type, Outlet Size, Item Type

Key Results
KPI	Value
Total Sales	$1.20M
Average Sales per Item	$141
Average Rating	3.9
Number of Items	8,523
Supermarket Type1 generates 65.5% of sales ($787.55K), and it also holds 65.4% of the items. Average sales per item are about $140 across all outlet types, so sales are driven by volume, not price.
Tier 3 locations lead with $472.13K (39.3% of sales), ahead of Tier 2 ($393.15K) and Tier 1 ($336.40K).
Low Fat items account for 64.6% of sales ($776.32K), compared with $425.36K for Regular items.
Fruits and Vegetables and Snack Foods are the top categories at about $0.18M each, together close to 30% of sales.
Outlets established in 2018 sold the most ($205K), while most other years fall between $129K and $133K.
Item visibility shows no clear link to sales. Grocery Stores have the highest average visibility (0.10) but the same average sales per item as other outlet types.

Recommendations
Prioritize availability and promotions in Fruits and Vegetables and Snack Foods.
Treat Tier 3 locations and the Supermarket Type1 format as the strongest growth areas.
Investigate why 2018-established outlets outperform the rest.
Test shelf-visibility changes in a small pilot before investing.

Limitations
The data has no date column, so there is no time-trend or seasonality analysis.
Records are item-and-outlet level, not individual customer transactions.
The findings are descriptive and show association, not cause.

Repository Contents

File	                      Description
BlinkIT Grocery Data.xlsx  	Raw dataset
Blinkit_Analysis.pbix	Power BI dashboard file
dashboard_preview.png	      Dashboard screenshot
README.md	                  Project documentation

How to Open the Project?
Download or clone the repository.
Open Blinkit_Analysis.pbix in Power BI Desktop.
If Power BI asks for the data source, point it to BlinkIT Grocery Data.xlsx.

Author
Shaik Fazila Zainab LinkedIn | GitHub
