# 🛍️ Retail Sales Analysis Using Power BI

## 📖 Overview
This project focuses on analyzing retail sales data using **Power BI** to uncover insights about **product performance**, **customer behavior**, and **sales trends**.  
The goal is to build an **interactive dashboard** that helps stakeholders monitor key performance indicators (KPIs) in real-time and make data-driven decisions to improve business performance.

---

## 🎯 Problem Statement
Retail businesses often face challenges in tracking and understanding their sales performance due to fragmented and static reporting systems.  
This project aims to solve problems such as:

- Difficulty tracking sales performance across categories and regions.  
- Lack of insights into top-performing products and customer purchase patterns.  
- No real-time reporting or interactivity in existing reports.  
- Challenges in identifying profitability and forecasting future trends.  

📘 *Refer to [Problem Statement.pdf](Problem%20Statement.pdf) for detailed context and scope.*

---

## 🧭 Objectives
1. Visualize **total revenue, profit, and units sold** using KPIs.  
2. Analyze **sales trends over time** and identify seasonal spikes.  
3. Compare **sales performance by category and region**.  
4. Create **DAX-based custom metrics** such as profit margin and growth.  
5. Enable **interactive filtering** using slicers for date, product, and category.  

---

## ⚙️ Methodology

### 1. Data Preparation
- Collected or simulated sales and customer data.
- Cleaned and transformed data to ensure consistency.
- Established table relationships for effective analysis.
- Created hierarchies in **Product** and **Sales Territory** tables.

### 2. Dashboard Development
Built in **Power BI**, the dashboard includes:

#### 🔹 KPIs
- **Total Revenue:** $109.81M  
- **Total Products Sold:** 275K  
- **Profit:** $12.55M  
- **Profit Margin:** 11.43%

#### 🔹 Visualizations
| Visualization | Purpose |
|----------------|----------|
| **Line/Area Chart** | Quarterly and yearly sales trends |
| **Donut Chart** | Sales by product category |
| **Matrix Table** | Category-wise contribution to revenue and profit |
| **Bar Chart** | Regional sales performance |
| **Bookmark Feature** | View top 5 and bottom 5 selling products |
| **Navigation Buttons** | Easy movement between Dashboard and Subcategory pages |

📊 *Refer to [Retail_Sales_Analysis_dashbard_print.pdf](Retail_Sales_Analysis_dashbard_print.pdf) for visual snapshots.*

---

## 🧮 Example DAX Formulas

```DAX
-- Total Revenue
Total Revenue = SUM(Sales[SalesAmount])

-- Total Products Sold
Total Products Sold = SUM(Sales[OrderQuantity])

-- Profit
Profit = SUM(Sales[SalesAmount]) - SUM(Sales[TotalProductCost])

-- Profit Margin
Profit Margin = DIVIDE([Profit], [Total Revenue], 0)
```

---

## 📈 Insights and Findings
- **Bikes** contribute the most to overall revenue (≈ 86%).  
- **United States** dominates regional sales performance ($63M).  
- **Top 5 Products:** Mountain-200 series in multiple variants.  
- Identified **less performing subcategories** such as Chains and Bottom Brackets.  
- Clear **seasonal trends** visible in quarterly performance.  

These insights support **strategic decisions** regarding inventory, marketing, and profitability optimization.

---

## 🎬 Project Demo
🎥 Watch the Power BI dashboard walkthrough:  
[**Power_BI_project_By-nisha.mp4**](Power_BI_project_By-nisha.mp4)

---

## 🧩 Files Included
| File | Description |
|------|--------------|
| `Problem Statement.pdf` | Defines business challenges, objectives, and expected outcomes |
| `Project_Report.pdf` | Methodology, KPIs, DAX measures, and dashboard explanation |
| `Retail_Sales_Analysis.pbix` | Power BI project file |
| `Retail_Sales_Analysis_dashbard_print.pdf` | PDF export of dashboard visuals |
| `Power_BI_project_By-nisha.mp4` | Video demonstration of the dashboard |

---

## 🖼️ Example Dashboard
![Retail Sales Dashboard](Retail_Sales_Analysis_dashbard_print.png)  
*Highlights: KPIs, category contribution, regional performance, and top-selling products.*

---

## 🧠 Conclusion
The **Retail Sales Analysis Dashboard** provides stakeholders with actionable insights to:
- Track performance in real-time.  
- Focus on high-margin products and profitable regions.  
- Understand customer and product trends.  
- Improve strategic decision-making.  

Through **DAX calculations**, **interactive visuals**, and **intuitive navigation**, the project delivers a complete analytical solution to drive profitability and business growth.

---

## 👩‍💻 Developed By
**Nisha Rai**  
*Power BI | Data Analytics | Business Intelligence*
