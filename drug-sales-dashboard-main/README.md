💊 Drug Sales Dashboard
A comprehensive, interactive Power BI dashboard designed to analyze pharmaceutical sales data, enabling stakeholders to visualize key metrics, demographic breakdowns, and trends over time to support strategic decision-making.
<img width="959" height="541" alt="Drug Sales Dashboard" src="https://github.com/user-attachments/assets/41866f82-0eb8-4f92-b321-b6a21fce980e" />
📋 Table of Contents

Project Overview
Problem Statement
Dataset Description
Solution & Approach
Dashboard Features
Tech Stack
Usage Instructions
Key Insights & Findings
Recommendations
Getting Started
License
Contact

🎯 Project Overview
This project delivers a comprehensive analysis of pharmaceutical sales performance through an interactive Power BI dashboard. The solution integrates customer demographics, product information, and transaction data to provide actionable insights into sales trends, customer behavior, and profitability metrics.
Key Objective: Enable data-driven decision-making by visualizing sales performance across multiple dimensions (geography, products, customer segments, time periods).
🔴 Problem Statement
Stakeholders required visibility into pharmaceutical sales performance with the ability to answer critical business questions:

Which drugs are generating the highest revenue and profit?
What are the geographic and demographic patterns in sales?
How have sales trends evolved over time (year-over-year, seasonal patterns)?
Which customer segments offer the best profitability?
What are the top-performing sales channels and buyer types?

📊 Tech Stack
Show Image
Show Image
Show Image
Show Image
Show Image
Tools & Technologies

Power BI Desktop - Dashboard design and visualization
Power Query - Data extraction, transformation, and loading (ETL)
DAX (Data Analysis Expressions) - Advanced calculations and business logic
Microsoft Excel - Data preparation and validation
SQL - Data querying and manipulation (optional)

📂 Dataset Description
The project uses three interconnected CSV files representing a star schema:
1. Customers.csv – Customer Demographics

CustomerID - Unique customer identifier
Age - Customer age
Gender - Customer gender
Country - Geographic location
Additional demographic attributes

2. Drugs.csv – Product Information

DrugID - Unique drug identifier
DrugName - Name of the pharmaceutical product
UnitPrice - Selling price per unit
Cost - Cost of goods sold
Treats - Medical condition treated
Category and other product attributes

3. Sales.csv – Transaction Data

SaleID - Unique transaction identifier
DrugID - Reference to drug sold
CustomerID - Reference to customer
UnitsSold - Quantity purchased
SaleDate - Date of transaction
BuyerType - Channel (Hospital, Retail, etc.)
Revenue and profit information

🛠 Solution & Approach
Data Preparation

Load Data - Import CSV files into Power Query
Clean Data - Remove duplicates, correct data types, handle missing values
Transform Data - Create calculated columns and standardize formats
Validate Quality - Ensure data integrity and consistency

Data Modeling

Create Star Schema - Design dimensional model with fact and lookup tables
Establish Relationships - Link Customers, Drugs, and Sales tables
Define Hierarchies - Set up date hierarchies (Year → Quarter → Month → Day)
Build Measures - Create DAX calculations for KPIs and metrics

Dashboard Development

Design Pages - Create multiple dashboard pages for different analyses
Add Visualizations - Deploy charts, maps, tables, and KPI cards
Implement Slicers - Add filters for interactive exploration
Optimize Performance - Ensure fast loading and responsive interactions

📈 Dashboard Features
Page 1: Executive Overview
Key Performance Indicators (KPIs)

Total Sales Quantity
Total Revenue
Total Cost
Net Profit
Profit Margin %
Average Order Value

Top Performers

Top 10 Drugs - By revenue, profit, and units sold
Top Customers - By purchase value and frequency
Bottom Performers - Identify underperforming products

Trend Analysis

Revenue Trend by Year
Quarterly Performance
Monthly Breakdown
Growth Rate Indicators


Page 2: Customer & Demographics Analysis
Geographic Insights

Sales by Country - Interactive map visualization
Regional performance comparison
Country-level profitability

Demographic Breakdown

Revenue by Gender - Pie/doughnut chart
Revenue by Age Group - Bar chart with age cohorts
Revenue by Buyer Type - Hospital, Retail, Online, etc.
Customer segment profitability

Customer Metrics

Total Customers
Average Customer Value
Customer Distribution
Repeat Purchase Rate


Page 3: Time-Series & Trends
Temporal Analysis

Year-over-Year Growth - Compare performance across years
Monthly Trends - Revenue and profit patterns
Weekly Breakdown - Sales velocity by week
Day-of-Week Patterns - Identify peak sales days

Seasonality Insights

Seasonal peaks and troughs
Holiday impact analysis
Trend lines and forecasting

Comparative Analysis

Period-over-period comparison
Cumulative performance tracking
Variance analysis


Slicers & Filters

Year/Month/Quarter
Drug Name & Category
Customer Demographics
Buyer Type
Geographic Region
Date Range Selection

💡 Usage Instructions
Option 1: Local Power BI Desktop
1. Download the .pbix file from the repository
2. Open Power BI Desktop
3. File → Open → Select the .pbix file
4. Interact with slicers and visualizations
5. Drill down into specific dimensions for detailed analysis
Option 2: Power BI Service (Published)
1. Access the Power BI Service link (if published)
2. Log in with your Microsoft account
3. View the dashboard in your browser
4. Share and collaborate with team members
Navigation Tips

Use slicers to filter by year, month, drug, buyer type, etc.
Click on chart elements for cross-filtering
Hover over visuals for detailed tooltips
Use drill-down features for granular analysis
Bookmark custom views for quick access

🔍 Key Insights & Findings
Revenue Drivers

Identify top-performing drugs contributing to revenue
Analyze sales channels and their profitability
Understand customer segment contributions

Geographic Opportunities

High-performing regions vs. underperforming markets
Geographic expansion opportunities
Regional marketing effectiveness

Customer Patterns

Demographics of high-value customers
Buyer type profitability analysis
Age and gender segment insights

Temporal Trends

Seasonal patterns and peak sales periods
Year-over-year growth trajectories
Weekly and daily sales velocity

📋 Recommendations
Based on the dashboard analysis, consider:

Product Strategy

Increase inventory for top-performing drugs
Review and optimize underperforming products
Analyze drug combinations and cross-selling opportunities


Geographic Expansion

Target high-potential underperforming regions
Scale successful markets
Establish regional partnerships


Customer Targeting

Focus marketing on high-value demographics
Develop tailored strategies for each buyer type
Implement loyalty programs for key segments


Sales Operations

Optimize inventory based on seasonal patterns
Plan staffing around peak sales periods
Implement data-driven pricing strategies



🚀 Getting Started
Prerequisites

Microsoft Power BI Desktop (latest version)
Access to Power BI Service (optional, for cloud sharing)

Installation

Clone the Repository

bash   git clone https://github.com/Priyanshu-2725/DRUG-SALES-DASHBOARD-.git
   cd DRUG-SALES-DASHBOARD-

Open the Dashboard

Locate drug-sales-dashboard.pbix
Double-click to open in Power BI Desktop
Or, import into Power BI Service for cloud access


Customize with Your Data

Replace sample CSVs with your actual data
Update data source connections
Refresh the model
Publish to share with stakeholders



Data Connection Steps
1. Power BI Desktop → Get Data → Text/CSV
2. Select your data files (Customers, Drugs, Sales)
3. Transform in Power Query Editor (clean, rename, filter)
4. Load data into Power BI
5. Create relationships between tables
6. Refresh to see updated visualizations
📁 Repository Structure
drug-sales-dashboard/
├── drug-sales-dashboard.pbix      # Power BI dashboard file
├── data/
│   ├── Customers.csv              # Customer demographics
│   ├── Drugs.csv                  # Product information
│   └── Sales.csv                  # Transaction data
├── documentation/
│   ├── Data_Dictionary.md         # Field descriptions
│   ├── Methodology.md             # Analysis approach
│   └── Screenshots/               # Dashboard visuals
├── README.md                       # This file
└── LICENSE
📊 Dashboard Analytics Workflow
Raw Sales Data
      ↓
Data Cleaning & Validation (Power Query)
      ↓
Data Transformation & Enrichment
      ↓
Star Schema Data Modeling
      ↓
DAX Calculations & Measures
      ↓
Interactive Dashboard Development
      ↓
Stakeholder Analysis & Insights
      ↓
Strategic Recommendations
🎓 Learning Outcomes
By exploring this project, you'll learn:
✅ Building enterprise-grade Power BI dashboards
✅ Data modeling with star schemas
✅ Advanced DAX calculations and formulas
✅ Power Query data transformation techniques
✅ Interactive dashboard design best practices
✅ Performance optimization in Power BI
✅ Storytelling with data visualization
📄 License
This project is open source and available under the MIT License. See LICENSE file for details.
📞 Contact
Priyanshu Sharma

GitHub: @Priyanshu-2725
Project: Drug Sales Dashboard


🔗 Useful Resources

Power BI Documentation
DAX Function Reference
Power Query Guide
Data Modeling Best Practices