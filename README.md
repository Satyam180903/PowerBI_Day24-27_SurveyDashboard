# PowerBI_Day24-27_SurveyDashboard
# Power BI Project: Day 24 to Day 27 – Survey Analysis Dashboard & Reporting

This repository contains all the essential work completed from Day 24 to Day 27 of the Power BI learning program. The focus is on data modeling, DAX calculations, Power BI visuals, paginated reports, and integrating SQL Server with Power BI.

Day 24 – Power BI DAX Techniques & Date-Time Functions

✅ Tasks Completed:
- Created and loaded data model using `Sales.xlsx` data.
- Implemented 15 DAX techniques, including:
  - Total Revenue
  - Filtered Totals
  - Percentage of Total
  - Running Total
  - Year-over-Year Change
  - Average, Count, Rank, Switch, etc.
- Used 5 date/time functions:
  - YEAR()
  - MONTH()
  - TODAY()
  - DATEDIFF()
  - TOTALYTD()

Visuals Included:
- Time-based trend charts
- KPI cards
- Tables and bar charts
- Slicers for Year and Category

 Day 25 – Advanced Reporting with Geo & Date-Time Context

✅ Tasks Completed:
- Worked on same Sales.xlsx data
- Implemented dynamic visuals and measures considering:
  - **Geographical filters** from `Geo` table
  - **Date-based filtering** from `Date/Calendar` table
- Created measures like:
  - `Total Revenue by State`
  - `YTD Sales`
  - `Revenue for Selected Location and Date`

Visuals Included:
- Line chart for revenue trends
- Map/area visual (optional)
- Multi-category bar charts (e.g., Geo[State] vs Revenue)
- Slicers for country, region, state

---

Day 26 – Power BI Licensing Research

 Documented:
- Types of Power BI Licenses:
  - Power BI Free
  - Power BI Pro
  - Power BI Premium (Per User and Per Capacity)
  - Power BI Embedded
  - Power BI Report Server (On-Premises)

- Differences between all license types
- Why Premium is better than Pro:
  - Larger datasets
  - More refreshes daily
  - Viewer access without additional licenses
  - Paginated reports
  - Dedicated cloud resources

 Included:
- Human-readable explanation of licensing
- Tables comparing features between Pro and Premium

---

 Day 27 – SQL Server Integration & Paginated Reports

✅ Tasks Completed:
- Installed and connected to SQL Server locally
- Created new database `CustomerSurveyDB`
- Imported Excel file `CustomerSurveyData.xlsx` using SQL Server Import Wizard
- Connected this database in Power BI Report Builder (Paginated Reports)

 Report Features:
- Used SQL Server as a data source
- Created calculated field:
  - `New Product Price = Product Price * 5`
- Created visuals:
  - Pie chart by Product or Brand
  - Table visual showing:
    - Brand Name
    - Customer Name
    - New Product Price
- Added parameters:
  - `SurveyType` (dropdown)
  - `Year` (dropdown)
- Enabled filters based on parameter inputs

 Tools & Technologies Used

- Power BI Desktop
- Power BI Report Builder
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Excel
- GitHub

 Author

Name: Satyam (SQL & Power BI Learner)  
Project: Survey Data Analysis & Reporting  
Location: Navi Mumbai, Maharashtra, India  
Period: Day 24 – Day 27  
Training Program: Power BI with SQL Server Reporting
