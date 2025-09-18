# 📊 Sales Analysis Dashboard - SQL & Power BI

A comprehensive sales analytics solution built using SQL Server and Power BI, designed to provide actionable insights into sales performance, customer behavior, and product trends.

## 🎯 Project Overview

This project transforms raw sales data from AdventureWorks into a powerful, interactive dashboard that helps business stakeholders make data-driven decisions. The solution includes data cleaning, transformation, and visualization components.

## 🚀 Key Features

- **Interactive Sales Dashboard** - Real-time insights into sales performance
- **Customer Analytics** - Deep dive into customer demographics and purchasing patterns  
- **Product Performance** - Analysis of top-performing products and categories
- **Budget vs Actual** - Comparison of sales targets against actual performance
- **Geographic Analysis** - Sales performance across different regions
- **Time Series Analysis** - Trend analysis with seasonal patterns

## 🛠️ Technology Stack

- **SQL Server** - Data extraction and transformation
- **Power BI Desktop** - Data visualization and dashboard creation
- **AdventureWorks DW** - Sample data warehouse
- **T-SQL** - Data cleaning and preparation

## 📁 Project Structure

```
SalesAnalysis_SQL_PowerBI/
├── 📋 Business Requirements/
│   ├── Business Demand Overview & User Stories.docx
│   └── Example Business Request.docx
├── 🗄️ Data Sources/
│   └── Sent Over Data - SalesBudget.xlsx
├── 🔧 SQL Scripts/
│   ├── DIM_Calendar_Clean.sql
│   ├── DIM_Customer_Clean.sql
│   ├── DIM_Product_Clean.sql
│   └── FACT_InternetSales_Clean.sql
├── 📊 Data Exports/
│   ├── DIM_Calendar_Export.csv
│   ├── DIM_Customer_Export.csv
│   ├── DIM_Product_Export.csv
│   └── FACT_InternetSales_Export.csv
└── 📈 Power BI Dashboard/
    ├── Sales Report.pbix
    └── Sales Report.pdf
```

## 🏗️ Data Model

The solution follows a star schema design with:

### Dimension Tables
- **Calendar** - Date hierarchy for time-based analysis
- **Customer** - Customer demographics and geographic information
- **Product** - Product catalog with categories and subcategories

### Fact Table
- **Internet Sales** - Sales transactions with key metrics

## 🔧 Setup Instructions

### Prerequisites
- SQL Server (SQL Express or higher)
- Power BI Desktop
- AdventureWorks DW database

### Installation Steps

1. **Database Setup**
   ```sql
   -- Restore AdventureWorks DW database
   -- Follow instructions: https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure
   ```

2. **Data Preparation**
   ```sql
   -- Run the SQL cleaning scripts in order:
   -- 1. DIM_Calendar_Clean.sql
   -- 2. DIM_Customer_Clean.sql  
   -- 3. DIM_Product_Clean.sql
   -- 4. FACT_InternetSales_Clean.sql
   ```

3. **Power BI Setup**
   - Open `Sales Report.pbix` in Power BI Desktop
   - Refresh data connections to point to your SQL Server
   - Explore the interactive dashboard

## 📊 Dashboard Components

### Key Visualizations
- **Sales Overview** - Total sales, growth trends, and KPIs
- **Customer Analysis** - Demographics, top customers, and geographic distribution
- **Product Performance** - Best-selling products, category analysis, and inventory insights
- **Budget Analysis** - Variance analysis between budgeted and actual sales
- **Time Intelligence** - Year-over-year comparisons and seasonal trends

### Interactive Features
- Cross-filtering between visualizations
- Drill-down capabilities
- Dynamic date range selection
- Export functionality for reports

## 📈 Business Impact

This dashboard enables stakeholders to:
- **Identify Sales Opportunities** - Spot trends and growth areas
- **Optimize Product Mix** - Focus on high-performing products
- **Improve Customer Targeting** - Understand customer segments
- **Monitor Performance** - Track progress against targets
- **Make Data-Driven Decisions** - Base strategies on real insights

## 🔍 Key Insights Discovered

- Sales performance trends over time
- Top-performing product categories
- Customer demographic patterns
- Geographic sales distribution
- Budget variance analysis
- Seasonal sales patterns

## 📝 Usage

1. **For Business Users**: Open the Power BI dashboard for interactive analysis
2. **For Developers**: Review SQL scripts for data transformation logic
3. **For Analysts**: Use exported CSV files for additional analysis

## 🤝 Contributing

This project was developed as a comprehensive sales analytics solution. Feel free to fork and adapt for your specific business needs.

## 📞 Contact

For questions or collaboration opportunities, please reach out through GitHub.

---

*Built with ❤️ using SQL Server and Power BI*
