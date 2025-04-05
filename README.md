# Market Share ETL & Dashboard Project

Overview
This project solves the problem of analyzing and visualizing market share data from 2019 to 2023. It uses a complete ETL pipeline to process raw data and build an interactive Power BI dashboard for exploring vendor, region, industry vertical, and time-based insights.

 *Technologies Used
- Python: For ETL (pandas, SQLAlchemy)
- PostgreSQL: Target database for cleaned data
- Power BI: Dashboard creation and visualization
- Jupyter Notebook: Data cleaning, transformation, and EDA



**ETL Pipeline**
 1.**Extract**
- Loaded multiple raw CSV files using pandas.

2. **Transform**
- Cleaned column names, removed duplicates.
- Handled missing values.
- Standardized revenue, vendor, and country data.
- Aggregated metrics by Vendor, Region, Country, Industry Vertical.

 3**Load**
- Loaded cleaned data into PostgreSQL using SQLAlchemy.

Power BI Dashboard Highlights
- **Market Share Trend (2019–2023)**  
- **Top Vendors by Revenue**  
- **Revenue by Region and Country (Drill-Down Treemap)**  
- **Revenue by Industry Vertical**  
- **Key KPIs**: Total Revenue, YoY Growth, Top Vendor  
- Interactive filters and slicers for deep dive analysis.


