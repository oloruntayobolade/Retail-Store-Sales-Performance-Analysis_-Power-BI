# 📊 Retail Store Sales Performance & Profitability Analysis | Power BI

**Turning retail sales data into actionable business insights through interactive dashboards, DAX-powered calculations, KPI monitoring, and performance analysis.**

## 📌 Project Overview

This project presents an interactive **Retail Store Sales Analysis Dashboard built with Microsoft Power BI**, designed to evaluate sales performance, profitability, product distribution, customer segments, order quantities, and operational efficiency.

The report features two complementary dashboard pages:
## 🖼️ Dashboard Preview

### 1. Retail Store Summary Dashboard

![Retail Store Summary Dashboard](https://github.com/oloruntayobolade/Retail-Store-Sales-Performance-Analysis_-Power-BI/blob/main/Overview%20KPI%20summary.png)
### 2. KPI Dashboard Overview

![Retail Store KPI Dashboard Overview](https://github.com/oloruntayobolade/Retail-Store-Sales-Performance-Analysis_-Power-BI/blob/main/KPI%20Overview.png)

This page provides an overview of sales performance, monthly order quantities, revenue trends, customer distribution, and manager-level revenue contributions.

- **KPI Dashboard Overview:** Examines sales revenue by manager and region, product category distribution, monthly order quantities, sales revenue trends, and customer segments.
- **Summary Dashboard:** Provides a consolidated view of revenue, cost, profit, average sales, average cost, order processing time, geographic distribution, and product sub-category performance.

Using **DAX (Data Analysis Expressions)** to develop calculations and analytical measures, the project transforms retail transaction data into interactive reports that help users monitor business performance, compare product categories, and identify trends that may inform management decisions.

The summary page highlights headline business metrics, product category distribution, geographic sales records, and product sub-category counts.

## 🎯 Project Objectives

- Evaluate overall retail sales revenue and profitability.
- Develop DAX measures for business calculations and performance reporting.
- Analyze monthly revenue and order quantity trends.
- Compare product categories and sub-categories by transaction count.
- Assess revenue contributions by sales manager and region.
- Examine customer segment distribution.
- Visualize geographic sales distribution across the United States.
- Monitor average sales, average cost, and order processing time.
- Present business performance through an interactive, management-friendly reporting interface.

## 🛠️ Tools & Technologies

| Tool / Technique | Application |
|---|---|
| Microsoft Power BI | Interactive dashboard development and reporting |
| DAX | Calculated measures, KPIs, and business analysis |
| Power Query | Data preparation and transformation, where applied |
| Data Visualization | Communicating trends, comparisons, and distributions |
| KPI Cards | Monitoring headline business metrics |
| Line & Area Charts | Analyzing monthly revenue and order quantity |
| Donut & Bar Charts | Comparing product categories and customer segments |
| Tables & Conditional Formatting | Presenting manager performance and product rankings |
| Map Visualization | Exploring geographic distribution across the United States |

## 📈 Key Performance Indicators

The summary dashboard presents the following business metrics:

| KPI | Dashboard Value |
|---|---:|
| Total Sales Revenue | $1.89M |
| Total Cost | $323.09K |
| Total Profit | $1.57M |
| Average Sale | $968.32 |
| Average Cost per item | $165.52 |
| Average Processing Time | 2 days |
| Total Records / Count Displayed | 1,952 |

*Figures are reproduced from the dashboard, and all monetary values are in US dollars ($). The definitions of the calculated measures and the exact meaning of the 1,952 count should be confirmed against the underlying dataset and DAX measures.*

## 🔍 Key Business Insights

### 1. Total sales revenue reached approximately $1.89 million

The dashboard reports total sales revenue of approximately **$1.89 million**, providing a high-level view of the business's recorded sales activity.

This KPI serves as a starting point for evaluating sales performance across managers, regions, products, and customer segments.

### 2. Erin generated the highest revenue among the displayed managers

The manager-level revenue table shows the following results:

| Manager | Region | Sales Revenue |
|---|---|---:|
| Erin | East | $574,325.47 |
| William | West | $525,854.04 |
| Chris | Central | $439,268.15 |
| Sam | South | $350,710.71 |

Erin recorded the highest sales revenue among the four displayed managers, followed by William.

Erin's revenue was approximately 64% higher than Sam's, highlighting a meaningful difference in recorded revenue contribution. Further analysis could explore product mix, customer distribution, sales volume, and other factors that may explain these differences.

### 3. Office Supplies dominated product category counts

The product category chart shows the following distribution across 1,952 counted records:

| Product Category | Count | Share |
|---|---:|---:|
| Office Supplies | 1,071 | 54.87% |
| Technology | 481 | 24.64% |
| Furniture | 400 | 20.49% |
| **Total** | **1,952** | **100%** |

Office Supplies accounted for more than half of the displayed category count.

This suggests that Office Supplies represents the largest category by the count used in the dashboard. However, category count should not be confused with revenue or profit contribution; those measures would be needed to determine which category generates the greatest financial return.

### 4. May recorded the highest monthly order quantity

The quantity-ordered chart shows these monthly values:

| Month | Quantity Ordered |
|---|---:|
| January | 3,368 |
| February | 4,220 |
| March | 3,592 |
| April | 3,955 |
| May | 5,813 |
| June | 4,320 |

May recorded the highest quantity ordered at **5,813**, while January recorded the lowest at 3,368.

The quantity ordered in May was approximately 72.6% higher than January's value. This difference highlights the importance of monitoring order volume when reviewing inventory requirements and monthly operational activity.

### 5. Monthly sales revenue fluctuated throughout the reporting period

The revenue chart displays the following monthly figures:

| Month | Sales Revenue |
|---|---:|
| January | $269K |
| February | $329K |
| March | $269K |
| April | $382K |
| May | $299K |
| June | $343K |

April recorded the highest displayed monthly sales revenue at approximately **$382K**, followed by June at $343K.

January and March both recorded approximately $269K, while revenue declined from April to May before recovering in June.

An important observation is that **May had the highest order quantity, but April had the highest sales revenue**. This illustrates why order volume and revenue should be analyzed separately: the number of items ordered does not, by itself, determine total sales value.

### 6. Corporate customers represented the largest customer segment

The customer segment chart reports the following distribution:

| Customer Segment | Count | Share |
|---|---:|---:|
| Corporate | 684 | 35.04% |
| Home Office | 470 | 24.08% |
| Consumer | 410 | 21.00% |
| Small Business | 388 | 19.88% |
| **Total** | **1,952** | **100%** |

Corporate customers represented the largest segment, accounting for approximately 35% of the displayed count.

Small Business represented the smallest segment at 19.88%. These differences offer an opportunity to examine customer purchasing behavior, segment-specific revenue, and potential opportunities for customer retention and growth.

### 7. Paper was the most frequently counted product sub-category

The sub-category summary identifies Paper as the leading category by count, with 284 records.

The next-highest displayed sub-categories were:

- Binders and Binder Accessories: 200
- Telephones and Communication: 194
- Office Furnishings: 185
- Computer Peripherals: 174

This breakdown helps identify frequently represented product sub-categories. Combining these counts with revenue, profit, and inventory information could provide a more complete view of product performance.

### 8. Geographic visualization supports regional exploration

The summary page includes a map showing geographic distribution across the United States.

This visual provides a spatial perspective on the records and creates an opportunity to investigate how sales activity varies across locations. Further comparisons using state-level revenue, profit, and order counts could help identify regional differences and support location-specific business planning.

### 9. Average processing time was two days

The dashboard reports an average processing time of **2 days**.

This KPI provides an operational benchmark that could be monitored alongside sales performance. Examining processing time by region, product category, or order volume could help identify areas for operational improvement, provided the underlying dates and processing-time calculation are validated.

## 🧮 DAX & Analytical Calculations

A major component of this project was the use of **DAX to create calculations and analytical measures** for the report.

The measures support KPI reporting and allow business metrics to be evaluated through Power BI visualizations.

The analysis covers:

- Total sales revenue.
- Total cost and total profit.
- Average sales and average cost.
- Average order processing time.
- Product category and sub-category counts.
- Monthly sales revenue and quantity comparisons.
- Customer segment distribution.
- Manager-level revenue comparisons.

These calculations help convert raw records into meaningful business metrics and support a consistent reporting experience across the dashboard.

**Key skill demonstrated:** Using DAX to support business-focused analysis rather than relying solely on default visualizations.

## 💼 Business Value

The dashboard demonstrates how Power BI can help retail businesses:

- **Monitor performance:** Review revenue, profit, cost, and operational KPIs in one report.
- **Evaluate sales contributions:** Compare recorded revenue across managers and regions.
- **Understand product distribution:** Identify categories and sub-categories with the highest counts.
- **Track monthly activity:** Compare sales revenue with order quantity to identify different performance patterns.
- **Understand customer segments:** Explore the distribution of records across customer groups.
- **Investigate geographic patterns:** Use map-based visualization to explore sales activity across locations.
- **Support operational planning:** Monitor processing time alongside sales metrics.

The report provides descriptive analysis of historical business data. Its findings can inform further investigation and planning but do not, on their own, establish the causes of performance differences or predict future results.

## 🧠 Skills Demonstrated

- Power BI report and dashboard development
- DAX calculations and analytical measures
- KPI design and performance monitoring
- Sales and profitability analysis
- Monthly trend analysis
- Product category and sub-category analysis
- Customer segmentation
- Manager and regional performance comparison
- Geographic data visualization
- Business intelligence and analytical storytelling
- Translating business data into actionable insights

## 🚀 How to Explore the Project

1. Clone or download this repository.
2. Download the Power BI report file (`.pbix`).
3. Open the report in Microsoft Power BI Desktop.
4. Explore the KPI Dashboard Overview and Summary Dashboard pages.
5. Review the revenue, profit, cost, and processing-time indicators.
6. Examine monthly order quantity and sales revenue trends.
7. Compare manager-level revenue, product categories, and customer segments.
8. Explore the geographic map and product sub-category summary.
9. Interact with any available report filters to investigate different data segments.

*If the report uses an external data source, the connection may need to be updated before refreshing the report.*

## 🔮 Potential Future Improvements

- Add monthly and year-over-year revenue growth measures.
- Calculate profit margins by product category, customer segment, and region.
- Compare order volume with average order value.
- Introduce sales targets and target-versus-actual performance indicators.
- Analyze processing time by region and product category.
- Develop drill-through pages for detailed manager and product analysis.
- Add interactive geographic comparisons using validated state-level metrics.
- Introduce forecasting as a separate extension if sufficient historical data is available.

## 👨‍💻 About This Project

This project demonstrates my interest in using data analytics and business intelligence to solve practical business problems. By combining Power BI visualizations with DAX calculations, I developed a reporting solution that brings sales performance, product distribution, customer segments, and operational indicators into a unified analytical view.

I am continually developing my skills in data analytics, business intelligence, and data-driven decision-making, with a focus on transforming raw data into insights that stakeholders can understand and use.
---

**Project Type:** Business Intelligence & Sales Analytics  
**Primary Tool:** Microsoft Power BI  
**Analytical Language:** DAX  
**Focus Areas:** Sales Performance, Profitability, Customer Segmentation, Product Analysis & Operational KPIs
