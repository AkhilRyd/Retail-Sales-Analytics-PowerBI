# Retail Sales Analytics — Power BI Dashboard

## 📊 Project Overview

This project uses **Microsoft Power BI** to transform retail sales data into an interactive three-page business intelligence dashboard.

The dashboard provides a consolidated view of **sales performance, revenue, costs, profitability, products, customers, salespersons, categories, and geographic performance**.

The objective is to help management identify major revenue drivers, understand profitability, monitor performance across locations and customers, and identify areas requiring further investigation.

---

## 🎯 Business Problem

The retail business has transactional sales data across multiple dimensions, but raw data alone makes it difficult to identify performance trends and business drivers.

Management needs answers to questions such as:

- Which months generate the highest and lowest revenue?
- Which product categories drive revenue and profit?
- Which locations perform best?
- Which products and salespersons contribute most to sales?
- Which customers and customer types generate the most revenue?
- Which categories provide the strongest profit margins?
- Where are the major opportunities and risks?

This project addresses these questions through an interactive Power BI dashboard.

---

## 🎯 Project Objectives

The main objectives were to:

1. Analyze overall sales and profitability.
2. Identify revenue trends across time.
3. Compare performance across product categories and locations.
4. Identify top-performing products, customers and salespersons.
5. Analyze customer and geographic performance.
6. Compare category-level profitability.
7. Provide actionable business recommendations based on the analysis.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX**
- **Microsoft Excel**
- Data modeling
- Interactive slicers
- Cross-page filter synchronization
- Power BI page navigation

---

## 🗂️ Data Model

The project uses a relational data model centered around the sales transaction data.

### Main tables

**Sales**
- Order ID
- Order Date
- Product ID
- Customer ID
- Salesperson ID
- Location ID
- Quantity
- Discount %

**Product**
- Product ID
- Product Name
- Category
- Brand
- Unit Cost
- Unit Price

**Customer**
- Customer ID
- Customer Name
- Customer Type
- City

Additional supporting tables contain salesperson and location information.

The primary product relationship used in the model is:

**Products (1) → Sales (*)**

This allows transaction-level sales to be analyzed using product attributes.

---

## 📐 Key DAX Measures

The dashboard uses measures including:

- Total Orders
- Total Quantity
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin
- Total Customers
- Average Revenue per Customer

These measures are used throughout the dashboard to provide dynamic calculations based on user selections.

---

# 📑 Dashboard Structure

## 1. Executive Overview

The Executive Overview provides a high-level summary of business performance.

### Key KPIs

| KPI | Value |
|---|---:|
| Total Orders | 5K |
| Total Quantity | 27K |
| Total Revenue | ₹591M |
| Total Cost | ₹489M |
| Total Profit | ₹102.32M |
| Profit Margin | 17.31% |

The page also includes:

- Monthly Revenue Trend
- Revenue by Category
- Top 10 Products by Revenue
- Interactive navigation

---

## 2. Sales Analysis

The Sales Analysis page focuses on performance across:

- Locations
- Salespersons
- Product categories
- Time periods

The page includes synchronized slicers for:

- Category
- Location
- Order Date

These filters are synchronized across all three dashboard pages, allowing users to investigate the same business question from different perspectives.

---

## 3. Customer Analysis

The Customer Analysis page focuses on customer-level performance.

It includes:

- Average Revenue per Customer
- Total Customers
- Top Customers by Revenue
- Revenue by Customer Type
- Revenue by Customer City

The analysis identified **Tech World** as the highest-revenue customer and **Retail** as the highest-revenue customer type in the dataset.

---

# 🔎 Key Business Insights

### 1. Electronics is the dominant revenue category

Electronics contributes approximately **91% of category revenue**, making it the primary revenue driver in the dataset.

This indicates significant dependence on Electronics for overall sales performance.

### 2. March was the strongest month

March recorded the highest monthly revenue, while September recorded the lowest.

The leading March locations were:

- Hyderabad — ₹9.0M
- Kolkata — ₹8.5M
- Chennai — ₹7.6M

### 3. Electronics explains most of the March–September decline

Electronics revenue declined from approximately **₹53M in March to ₹37M in September**.

This represents a decline of **₹16M**.

Across the four analyzed categories, the total decline was approximately **₹17.42M**, meaning Electronics accounted for roughly **92% of that decline**.

### 4. Electronics is the main profit contributor

Electronics generated approximately **₹93M in profit**, making it by far the largest contributor to total profit.

However, high total profit does not mean the category has the highest margin.

### 5. Accessories has the highest profit margin

| Category | Profit Margin |
|---|---:|
| Accessories | **27.86%** |
| Storage | 18.48% |
| Electronics | 17.18% |
| Furniture | 15.46% |

Accessories has the strongest profit margin despite contributing a much smaller absolute amount of profit.

### 6. Customer concentration

The dataset contains **10 customers**.

**Tech World** is the highest-revenue customer, while the average revenue per customer is approximately **₹59.10M**.

### 7. Geographic performance varies by analytical view

Hyderabad was the highest-revenue location in the March analysis, while Bangalore was the highest-revenue customer city in the Customer Analysis.

The synchronized filters allow these differences to be explored by time period, category and other dimensions.

---

# 💡 Business Recommendations

### 1. Reduce dependence on Electronics

Electronics dominates both revenue and total profit.

Management should continue supporting this category while gradually developing other categories to reduce concentration risk.

### 2. Explore growth opportunities in Accessories

Accessories has the highest profit margin at **27.86%**.

Potential strategies include:

- Cross-selling with Electronics
- Product bundling
- Targeted promotions
- Improving product visibility

### 3. Investigate the Electronics revenue decline

The ₹16M decline between March and September should be investigated further.

Potential areas for deeper analysis include:

- Product-level performance
- Location-level Electronics sales
- Salesperson performance
- Quantity trends
- Discount levels

### 4. Study high-performing locations

Management can investigate the products, customers and salespersons driving strong locations and determine whether successful practices can be replicated elsewhere.

### 5. Monitor high-value customers

High-revenue customers such as Tech World should receive appropriate monitoring because significant customer concentration can create revenue risk.

### 6. Use the dashboard for recurring performance reviews

The dashboard can be used as an ongoing management tool to monitor:

- Revenue
- Profitability
- Category performance
- Location performance
- Customer performance
- Product performance

---

# 📌 Conclusion

This project demonstrates how retail transaction data can be transformed into an interactive business intelligence solution using Power BI.

The analysis shows that the business generates **₹591M in revenue and ₹102.32M in profit**, with an overall profit margin of **17.31%**.

The most significant finding is the strong dependence on Electronics, which contributes approximately 91% of category revenue and the majority of total profit.

At the same time, Accessories demonstrates the strongest profit margin at **27.86%**, highlighting a potential opportunity for improving the overall profitability mix.

The dashboard allows users to investigate these patterns dynamically through synchronized **Category, Location and Order Date** filters across three analytical pages.

Overall, the project demonstrates the use of **data modeling, DAX, interactive visualization, cross-page filtering and business analysis** to turn raw retail data into actionable insights.

---

## 🚀 Future Improvements

Potential future enhancements include:

- Customer lifetime value analysis
- Product-level profitability analysis
- Sales forecasting
- Year-over-year performance analysis
- Discount vs profitability analysis
- More detailed regional analysis
- Automated data refresh
- Additional KPI targets and variance analysis

---

## 👤 Project Author

**Akhil R S**

Data Analytics / Business Intelligence Portfolio Project

### Skills demonstrated

**Power BI · DAX · Excel · Data Modeling · Data Visualization · Business Analysis · KPI Development · Interactive Dashboards**