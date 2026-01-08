# Amazon Global E-Commerce Dashboard - Power BI

## Overview
A Power BI dashboard analyzing Amazon's global e-commerce operations, including sales performance, customer insights, and regional analysis.

## Project Description
An interactive business intelligence dashboard that transforms Amazon's e-commerce data into actionable insights through dynamic visualizations and KPIs. Enables stakeholders to monitor sales trends, analyze customer behavior, and make data-driven decisions across global markets.

## Features
- Interactive sales dashboard
- Geographic sales distribution
- Product category analysis
- Customer demographics insights
- Time-series trend analysis
- Revenue and profit metrics
- Regional performance comparison

## Technology Stack
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Excel/CSV data sources

## Dashboard Components

### Key Performance Indicators
- Total Revenue
- Total Orders
- Average Order Value
- Customer Count
- Profit Margins
- Growth Rate

### Visualizations
- Sales trends (line charts)
- Geographic map (regional sales)
- Category performance (bar charts)
- Customer demographics
- Top products
- Monthly comparisons

### Interactive Features
- Date range slicers
- Regional filters
- Category drill-through
- Dynamic tooltips
- Cross-filtering

## Installation

```bash
git clone https://github.com/Ropriya/Analysis_Amazon_Global_E-Commerce_Dashboard_Power-BI.git
cd Analysis_Amazon_Global_E-Commerce_Dashboard_Power-BI
```

1. Open Power BI Desktop
2. Open the `.pbix` file
3. Refresh data connections
4. Explore dashboard using filters

## File Structure
```
Analysis_Amazon_Global_E-Commerce_Dashboard_Power-BI/
├── Amazon_Dashboard.pbix
├── data/
│   ├── sales_data.csv
│   └── products.csv
└── README.md
```

## Key DAX Measures
```DAX
Total Revenue = SUM(Sales[Amount])
Average Order Value = DIVIDE([Total Revenue], [Total Orders])
Profit Margin = DIVIDE([Total Profit], [Total Revenue])
YoY Growth = ([Current Year] - [Previous Year]) / [Previous Year]
```

## Dashboard Pages
1. **Overview**: High-level KPIs and trends
2. **Sales Analysis**: Revenue breakdown
3. **Product Performance**: Category analysis
4. **Customer Insights**: Demographics and behavior
5. **Regional Analysis**: Geographic performance

## Key Insights
- Best-performing regions and products
- Seasonal trends and patterns
- Customer purchase behavior
- Revenue growth opportunities

## Requirements
- Power BI Desktop (Free version)
- Windows 10 or later
- 4GB RAM minimum

## Future Enhancements
- Live data integration
- Predictive analytics
- Mobile-optimized version
- Automated reporting

## Author
**Rohit Ranjan**
- GitHub: [github.com/Ropriya](https://github.com/Ropriya)
- LinkedIn: [linkedin.com/in/contact-rohit-ranjan](https://linkedin.com/in/contact-rohit-ranjan)

---

*Transform data into insights!* 📊