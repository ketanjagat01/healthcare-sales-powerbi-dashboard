# Healthcare Sales & Profitability Analysis Dashboard

[Power BI Dashboard](Screenshots/dashboard-overview.png)

## 📊 Project Overview

This project presents an interactive Power BI dashboard developed to analyze healthcare business performance across revenue, costs, profitability and product returns.

The dashboard brings key financial and operational metrics into a single interactive view to help identify performance trends, major revenue contributors, profitability drivers and areas requiring further investigation.

---

## 🎯 Business Objective

The objective of this project was to transform business data into an interactive analytical dashboard that can help stakeholders answer key business questions such as:

- How is revenue performing over time?
- How does total revenue compare with total cost?
- Which departments contribute most to revenue?
- Which sub-categories generate the highest gross profit?
- How does performance vary across quarters?
- Which sub-categories have the highest return quantities?
- What is the overall gross margin and return rate?

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | 281.75M |
| Total Cost | 236.28M |
| Net Revenue | 224.71M |
| Gross Profit | 45.47M |
| Gross Margin | 16.14% |
| Return Rate | 33.20% |

---

## 🔎 Key Business Insights

### 1. Revenue Concentration

Department 1 contributes approximately 87.7% of total revenue, making it the largest revenue contributor among the departments displayed in the dashboard.

### 2. Gross Profit Performance

Injections generate approximately 21.13M in gross profit, representing the highest displayed gross-profit contribution among the sub-categories shown.

### 3. Revenue Trend

Monthly revenue reaches approximately 28M at its peak during the displayed period.

### 4. Product Returns

Injections have the highest displayed return quantity at approximately 0.16M, followed by IV Fluids/Electrolytes at approximately 0.07M.

### 5. Overall Profitability

The business generates approximately 45.47M in gross profit with an overall gross margin of 16.14%.

---

## 📈 Dashboard Components

The dashboard includes:

- Revenue and cost trend analysis
- Department-wise revenue contribution
- Quarterly revenue and gross profit analysis
- Gross profit by sub-category
- Revenue by sub-category
- Return quantity by sub-category
- Interactive department and sub-category filters

---

## 🧮 DAX

### Gross Profit

```DAX
Gross Profit = [Total Revenue] - [Total Cost]
