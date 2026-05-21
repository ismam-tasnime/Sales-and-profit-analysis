# Sales-and-profit-analysis
This project was created in Excel to analyze business performance across multiple dimensions such as sales, profit, customers, services, departments, countries, and subscription packages. The dashboard was designed with a clean interface and dynamic visualizations to provide quick business insights and support data-driven decision-making.
# Sales & Profit Analysis Dashboard | Excel Business Intelligence Project 📊

## Project Overview

This project is an interactive *Sales & Profit Analysis Dashboard* built in Microsoft Excel to analyze the performance of a service-based business. The main objective of this project was to transform raw business transaction data into a professional dashboard that can help management understand overall sales performance, profitability, customer behavior, service performance, department contribution, customer acquisition channels, and package-based business trends.

The dashboard was designed using Excel Pivot Tables, Pivot Charts, slicers, KPI cards, and interactive filters. It provides a clear business overview for decision-makers by showing total sales, total profit, new customers, repeat customers, service-wise performance, department-wise profit, country/city-wise sales and profit, and customer type by source.

This project demonstrates my ability to clean, organize, analyze, and visualize business data in Excel while applying practical business analysis thinking to identify problems and recommend business solutions.

---

## Business Objective

The goal of this project was to answer key business questions such as:

- What is the total sales performance of the business?

- How much profit is generated from overall sales?

- Which services generate the highest profit?

- Which department contributes most to profitability?

- Which customer type performs better: company or individual?

- Are repeat customers stronger than new customers?

- Which country or city generates the highest sales and profit?

- Which customer source brings more customers?

- Which package type performs better?

- How can the business improve sales, profit, and customer retention?

---

## Dataset Description

The dataset contains sales transaction records for a service-based company.

Main fields used in the analysis:

- Date

- Month

- Year

- Customer Name

- Customer Type

- Service

- Department

- City

- Sales Amount

- Margin %

- Margin Amount

- Sale Type

- Customer Source

- Package Type

The data was used to create Pivot Tables and dashboard visuals for business decision-making.

---
## Dashboard 

![Dashboard](images/dashboard.png)

---

## Key Performance Indicators

The dashboard highlights the most important business KPIs:

| KPI | Value |
|---|---:|
| Total Sales | BDT 3,120,241 |
| Total Profit | BDT 952,132 |
| New Customers | 189 |
| Repeat Customers | 309 |
| Total Records / Transactions | 498 |
| Unique Customers | 32 |

These KPI cards provide a quick executive-level view of business performance.

---

## Dashboard Pages / Workbook Structure

The Excel workbook contains multiple sheets for analysis and reporting.

### 1. Data Sheet

The *Data* sheet contains the original transaction-level business data. This sheet was used as the source table for building Pivot Tables and dashboard visuals.

### 2. Pivot/rpivot Sheet

The *Pivot* sheet contains summarized Pivot Table analysis, including customer type performance, sales amount, profit amount, average sales, and average margin.



The *rpivot* sheet contains the major Pivot Table calculations used for the dashboard visuals. It includes service-wise profit, customer type sales, customer source analysis, city/country sales and profit, and customer type by source.

### 3. Dashboard / rdash Sheet

The dashboard page presents the final visual report using KPI cards, charts, slicers, and interactive business visuals.

---

## Dashboard Features

### Executive KPI Cards

The dashboard includes KPI cards for:

- Total Sales

- Total Profit

- New Customer

- Repeat Customer

These cards allow business users to quickly understand the company’s overall performance without going through raw data.

---

### Customer-Wise Sales Analysis

A pie chart was created to compare sales between customer types:

| Customer Type | Sales | Profit | Transactions |
|---|---:|---:|---:|
| Company | BDT 1,588,057 | BDT 479,646.55 | 249 |
| Individual | BDT 1,532,184 | BDT 472,485.90 | 249 |

Company customers generated slightly higher sales and profit than individual customers. However, both customer types contributed almost equally to total transaction volume.

---

### Service-Wise Profit Analysis

A horizontal bar chart was used to analyze profit by service.

| Service | Sales | Profit | Transactions |
|---|---:|---:|---:|
| Web Dev | BDT 646,215 | BDT 226,175.25 | 102 |
| App Dev | BDT 547,870 | BDT 219,148.00 | 91 |
| SEO | BDT 821,707 | BDT 205,426.75 | 121 |
| Social Media | BDT 505,404 | BDT 151,621.20 | 86 |
| Ads | BDT 599,045 | BDT 149,761.25 | 98 |

SEO generated the highest sales, but Web Development generated the highest profit. This indicates that the highest revenue service is not always the most profitable service.

---

### Department-Wise Profit Analysis

A pie chart was used to compare department-wise profit contribution.

| Department | Sales | Profit | Transactions |
|---|---:|---:|---:|
| Design | BDT 1,194,085 | BDT 445,323.25 | 193 |
| Marketing | BDT 1,104,449 | BDT 301,382.45 | 184 |
| Copywriting | BDT 821,707 | BDT 205,426.75 | 121 |

The Design department generated the highest profit, followed by Marketing and Copywriting. This shows that Design-related services are the strongest profit contributor in this business.

---

### Service-Wise Sales vs Profit

A line chart was created to compare sales and profit across different services and customer types.

This visual helps identify whether a service is generating strong sales but low profit, or lower sales with higher profit efficiency.

Key finding:

- SEO has the highest sales.

- Web Dev and App Dev generate stronger profit margins.

- Ads has good sales volume but comparatively lower profit.

- Social Media has the lowest service-level sales and profit contribution.

---

### Country / City-Wise Sales vs Profit

The dashboard includes a country/city-wise sales and profit comparison.

| City | Sales | Profit | Transactions |
|---|---:|---:|---:|
| Dubai | BDT 922,311 | BDT 282,819.85 | 145 |
| Abu Dhabi | BDT 806,990 | BDT 244,221.55 | 133 |
| Ajman | BDT 493,303 | BDT 150,156.30 | 79 |
| Al Ain | BDT 487,337 | BDT 151,262.35 | 77 |
| Sharjah | BDT 410,300 | BDT 123,672.40 | 64 |

Dubai is the strongest sales and profit market, followed by Abu Dhabi. Sharjah has the lowest sales and profit contribution, which may require additional business attention.

---

### Customer Type vs Source

A clustered column chart was created to compare customer source performance between company and individual customers.

| Customer Type | Ads | Organic | Walk-in |
|---|---:|---:|---:|
| Company | 80 | 84 | 85 |
| Individual | 75 | 84 | 90 |

Walk-in customers are slightly stronger, especially for individual customers. Organic source is stable for both company and individual customers. Ads performs reasonably well but is slightly lower than walk-in and organic sources.

---

### New vs Repeat Customer Analysis

The dashboard compares new and repeat customer performance.

| Sale Type | Sales | Profit | Transactions |
|---|---:|---:|---:|
| Repeat Sale | BDT 1,948,754 | BDT 593,244.35 | 309 |
| New Sale | BDT 1,171,487 | BDT 358,888.10 | 189 |

Repeat customers generate significantly higher sales and profit compared to new customers. This indicates strong customer retention and recurring business potential.

---

### Package Type Analysis

Package type slicers were added to filter the dashboard by:

- Annual

- Bi Annual

- Monthly

- Quarterly

Package-wise performance:

| Package Type | Sales | Profit | Transactions |
|---|---:|---:|---:|
| Monthly | BDT 840,505 | BDT 251,240.50 | 131 |
| Annual | BDT 768,510 | BDT 235,090.15 | 122 |
| Quarterly | BDT 764,274 | BDT 225,789.00 | 120 |
| Bi Annual | BDT 746,952 | BDT 240,012.80 | 125 |

Monthly packages generated the highest sales and profit, while Bi Annual packages also performed strongly in profit.

---

## Business Problems Identified and Business Solutions

### Problem 1: SEO generates the highest sales, but not the highest profit

SEO produced the highest sales amount, but Web Development generated the highest profit. This means SEO has strong demand, but its profit efficiency is lower compared to Web Dev and App Dev.

### Business Solution

The business should review SEO pricing, delivery cost, employee workload, and campaign management cost. SEO packages can be redesigned with premium pricing tiers, add-on services, and performance-based pricing to improve profitability.

---

### Problem 2: Ads service has good sales but comparatively low profit

Ads generated strong sales, but the profit is lower than Web Dev, App Dev, and SEO. This suggests that Ads may have higher operating costs or lower margin pricing.

### Business Solution

The company should evaluate the cost of ad campaign management, client servicing time, and platform-related expenses. Ads packages should be bundled with SEO or Social Media services to increase average order value and improve margin.

---

### Problem 3: Social Media service is the weakest service category

Social Media generated the lowest sales and profit among all services. This indicates either low demand, weak pricing, or underdeveloped service positioning.

### Business Solution

The company can redesign Social Media packages by offering monthly content calendars, paid boosting support, branding packages, and performance reports. It can also be promoted as an add-on with Ads and SEO services.

---

### Problem 4: Business depends heavily on repeat customers

Repeat customers generated 309 transactions compared to 189 new customers. This is positive for retention, but it also shows that new customer acquisition is relatively lower.

### Business Solution

The business should continue retention efforts but also increase new customer acquisition through referral campaigns, digital marketing, lead magnets, and targeted B2B outreach. A balanced growth strategy should focus on both retention and acquisition.

---

### Problem 5: Dubai and Abu Dhabi dominate sales and profit

Dubai and Abu Dhabi are the strongest cities, while Sharjah has the lowest contribution. This creates location-based performance imbalance.

### Business Solution

The company should use Dubai and Abu Dhabi as benchmark markets. For Sharjah, the business can run local promotions, improve sales follow-up, create city-specific offers, and analyze whether the service demand is weaker or marketing effort is lower.

---

### Problem 6: Company and individual customers perform almost equally

Company and individual customers have almost the same transaction count, but company customers generate slightly higher sales and profit.

### Business Solution

The business should create separate strategies for both customer types. Company customers can be targeted with long-term contracts and annual packages, while individual customers can be targeted with affordable monthly or quarterly service plans.

---

### Problem 7: Walk-in and Organic sources perform strongly

Walk-in and Organic sources bring more customers than Ads. This means the business has strong natural demand and customer trust, but paid acquisition may not be fully optimized.

### Business Solution

The company should strengthen organic marketing through SEO, social media content, client testimonials, and referral programs. Paid ads should be reviewed to improve targeting, conversion rate, and cost efficiency.

---

### Problem 8: Monthly package has the highest sales and profit

Monthly packages are performing better than Annual, Quarterly, and Bi Annual packages. This indicates that customers may prefer flexible short-term commitments.

### Business Solution

The business should keep Monthly packages attractive but also encourage upgrades to Quarterly or Annual packages through discounts, added services, or loyalty benefits. This can improve cash flow and customer lifetime value.

---

## Key Business Insights

- Total sales reached *BDT 3.12M, with total profit of **BDT 952K*.

- Repeat customers generated more revenue and profit than new customers.

- Company and individual customers contributed almost equally, but company customers had slightly stronger profitability.

- SEO generated the highest revenue, but Web Development generated the highest profit.

- Design was the most profitable department.

- Dubai was the strongest performing city in both sales and profit.

- Sharjah had the lowest revenue and profit contribution.

- Walk-in and Organic sources performed better than Ads in customer acquisition.

- Monthly packages generated the highest package-level sales and profit.

- The business has strong retention but should improve new customer acquisition.

---

## Tools Used
- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- KPI Cards

- Pie Charts

- Bar Charts

- Line Charts

- Conditional Formatting

- Dashboard Design

- Data Cleaning

- Business Analysis

---

## Excel Techniques Applied

### Data Cleaning

The raw transaction data was organized and structured to make it suitable for Pivot Table analysis.

### Pivot Table Analysis

Pivot Tables were created to summarize sales and profit by customer type, service, department, city, source, package type, and sale type.

### Dashboard Development

An interactive dashboard was created using Pivot Charts, slicers, KPI cards, and business-focused visuals.

### Interactive Filtering

Slicers were used for:

- Year

- Month

- Package Type

These filters allow users to dynamically update dashboard visuals and analyze performance from different perspectives.

### Comparative Analysis

Sales and profit were compared across service categories, cities, departments, and customer types to identify business strengths and weaknesses.

### Customer Behavior Analysis

New and repeat customer analysis was performed to understand customer retention and acquisition performance.

---

## Business Value of This Project

This dashboard helps the business:

- Track total sales and profit performance

- Understand which services generate the most profit

- Identify strong and weak departments

- Compare company and individual customer performance

- Monitor new customer and repeat customer behavior

- Identify high-performing cities

- Evaluate customer acquisition sources

- Improve pricing, marketing, and package strategy

- Make data-driven business decisions

---

## Recruiter-Focused Project Highlights

This project demonstrates practical skills in:

- Excel dashboard design

- Pivot Table reporting

- Business performance analysis

- KPI development

- Sales and profit analysis

- Customer segmentation

- Service profitability analysis

- Data visualization

- Business problem identification

- Strategic business recommendation

The project reflects real-world business analysis thinking by not only visualizing data but also identifying business problems and suggesting actionable solutions.

---


## Conclusion

The Sales & Profit Analysis Dashboard provides a complete view of business performance across customers, services, departments, cities, sources, and package types. It helps management understand where revenue is coming from, which areas are most profitable, and where improvement opportunities exist.

Through this project, I applied Excel-based business intelligence techniques to convert raw sales data into meaningful insights and business recommendations. This project is suitable for demonstrating skills in Excel analytics, dashboard reporting, business intelligence, and data-driven decision-making.
