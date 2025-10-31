# 📊 Sales Analysis Dashboard – Power BI  

![Power BI](https://img.shields.io/badge/Power-BI-yellow)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-orange)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-blue)

---

## 🏆 Overview  
This **Sales Analysis Dashboard** is an interactive **Power BI project** that visualizes key sales performance indicators across **regions, product categories, and time periods**.  
It provides actionable insights for business decision-making, helping identify profitable regions, sales trends, and improvement opportunities.  

---

## 🖼️ Dashboard Preview  
![Dashboard Preview](https://github.com/Musaddiq485/sales_analysis-report/blob/1f5742bbe8ad8a88c1128acc801557046e08d395/Screenshot%202025-10-31%20172643.png)

---

## 🎯 Key Insights  

### 💰 Performance Summary  
| Metric | Value |
|--------|--------|
| **Total Sales** | 2.30M |
| **Total Profit** | 286K |
| **Total Cost** | 2.01M |
| **Product Returns** | 297 |

### 🌍 Regional Overview  
| Region | Sales | Profit |
|--------|--------|--------|
| West | 725,458 | 108,418 |
| East | 678,781 | 91,523 |
| Central | 501,240 | 39,706 |
| South | 391,722 | 46,749 |

### 📦 Product Category Insights  
- **Office Supplies** generated the highest sales volume.  
- **Technology** shows consistent year-over-year growth.  
- **Furniture** remains steady across all quarters.  

---

## 🚀 Features  
- 📈 **Quarterly Sales Trends** (2014–2017)  
- 🌍 **Regional and Segment Filtering**  
- 🔍 **Sub-Category Drilldowns**  
- 💡 **KPI Cards for Quick Metrics**  
- 📊 **Profit vs. Sales Visualization**  
- 🕒 **Time Intelligence for Yearly Trends**  

---

## 🛠️ Technical Details  

### 📂 Data Model (Star Schema)
```text
Fact_Sales ─┬─ Dim_Date
             ├─ Dim_Region
             ├─ Dim_Product
             └─ Dim_Customer
