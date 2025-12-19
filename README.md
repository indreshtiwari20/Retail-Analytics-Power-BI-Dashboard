# 🛒 Retail Analytics Power BI Dashboard

**Interactive dashboard providing comprehensive overview of sales performance, profitability, and customer behavior for online retail business.**

---

## 📋 Overview

A full-featured e-commerce analytics dashboard built with Power BI that enables deep-dive analysis of key retail metrics including total sales, profit margins, order volume, average order value, and customer segmentation. Perfect for retail managers and business analysts tracking performance across regions and time periods.

**Key Insight:** Track sales trends, identify top-performing regions, analyze customer behavior patterns, and optimize inventory based on data-driven insights.

---

## 📊 Project Structure

```
Retail-Analytics-Power-BI-Dashboard/
├── README.md                        # Project documentation
├── Ecommerce Project pbi.pbix       # Power BI dashboard file
├── ecommerce_data.csv              # Sales transaction data
├── us_state_long_lat_codes.csv      # Geographic coordinates
└── Dashboard.png                     # Dashboard screenshot
```

---

## 🎯 Key Performance Indicators (KPIs)

- **Total Sales** - Aggregate revenue across all transactions
- **Profit Margins** - Percentage profitability by product and region
- **Order Volume** - Number of transactions and order frequency
- **Average Order Value (AOV)** - Mean transaction value
- **Customer Lifetime Value** - Revenue contributed by each customer
- **Regional Performance** - Sales breakdown by geographic location
- **Product Category Performance** - Revenue and profit by product type
- **Customer Segmentation** - Classification by purchase behavior

---

## 🛠️ Tools & Technologies

| Category | Tools |
|----------|-------|
| **Business Intelligence** | Power BI Desktop |
| **Data Transformation** | SQL, Power Query (M) |
| **Data Analysis** | DAX Calculations |
| **Geospatial** | Map Visualizations |
| **Data Source** | CSV, Excel |

---

## 📈 Dashboard Features

✅ **Sales Performance Cards** - Real-time KPI metrics and trends
✅ **Geographic Heatmap** - Sales performance by US state
✅ **Time Series Analysis** - Monthly and quarterly sales trends
✅ **Product Category Analysis** - Revenue and profit by product type
✅ **Customer Segmentation** - Behavioral clustering and lifetime value
✅ **Interactive Filters** - Period selection, region, and product filters
✅ **Drill-Down Capabilities** - Detailed transaction-level analysis
✅ **Mobile Optimized** - Responsive design for all devices

---

## 🚀 How to Use

### Prerequisites
- Power BI Desktop (Latest Version)
- Basic understanding of e-commerce metrics

### Steps to Run

1. **Download the Power BI file**
   ```
   Download: Ecommerce Project pbi.pbix
   ```

2. **Open in Power BI Desktop**
   - Launch Power BI Desktop
   - Open `Ecommerce Project pbi.pbix`

3. **Review the Data**
   - Check ecommerce_data.csv for transaction records
   - Review geographic mapping in us_state_long_lat_codes.csv

4. **Explore the Dashboard**
   - Use filters to segment data by time period and region
   - Click on visuals for drill-down into details
   - Analyze trends and patterns

---

## 📊 Data Dictionary

**ecommerce_data.csv** contains:
- Order ID and Date
- Product Category
- Quantity and Unit Price
- Sales Amount
- Profit
- Region and State
- Customer Segment
- Shipping Mode

**us_state_long_lat_codes.csv** contains:
- State codes and names
- Longitude/Latitude coordinates for mapping

---

## 💡 Key Insights Delivered

1. **Regional Performance** - Identified top 5 performing states and regions
2. **Product Analysis** - Category-wise profit contribution and trends
3. **Customer Behavior** - Segmentation by purchase frequency and value
4. **Seasonal Trends** - Monthly and quarterly sales patterns
5. **Profitability Analysis** - Margin analysis by product and region
6. **Growth Opportunities** - Underperforming segments for improvement

---

## 🔧 Technical Highlights

### DAX Measures
- Total Sales = SUM(Sales[Amount])
- Profit Margin (%) = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Amount]))
- YoY Growth = VAR CurrentYear Sales - CALCULATE(..., SAMEPERIODLASTYEAR)
- Customer LTV = CALCULATE(SUM(Sales), ALL(Dates))

### Visualizations
- Filled Map for geographic analysis
- Line Charts for trend analysis
- Clustered Bar Charts for comparisons
- Donut Charts for category distribution
- Scatter Plot for customer segmentation

---

## 📸 Dashboard Screenshots

See `Dashboard.png` for visual overview of the analytics dashboard.

---

## 👨‍💼 My Role & Outcomes

**Responsibilities:**
- Analyzed 5000+ e-commerce transactions
- Designed interactive dashboard for retail stakeholders
- Developed DAX calculations for custom metrics
- Created geographic visualizations for regional analysis

**Outcomes:**
- ✅ Provided actionable insights for inventory optimization
- ✅ Enabled regional performance comparison
- ✅ Identified top and bottom performing products
- ✅ Reduced reporting time by 80%
- ✅ Improved decision-making for marketing campaigns

---

## 🎓 Skills Demonstrated

- Power BI dashboard design and visualization
- Advanced DAX formula development
- E-commerce domain knowledge
- Geographic data visualization
- Customer analytics and segmentation
- Performance optimization
- Business intelligence best practices

---

## 📞 Contact & Links

**Indresh Tiwari**
- LinkedIn: [linkedin.com/in/indreshtiwari](https://www.linkedin.com/in/indreshtiwari/)
- Email: tiindresh@gmail.com
- Portfolio: [GitHub Profile](https://github.com/indreshtiwari20)

---

**Last Updated:** December 2025 | **Status:** ✅ Completed | Production Ready
