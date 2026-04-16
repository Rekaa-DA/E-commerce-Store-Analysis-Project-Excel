# 📊 E-Commerce Sales Data Analysis

## 📌 Project Overview

This project focuses on analyzing e-commerce sales data using Microsoft Excel. The dataset was organized into structured tables (CUSTOMER, PRODUCT, STORE, SALES) and analyzed to generate business insights through data cleaning, transformation, formulas, pivot tables, and visualization.

## 🧹 Data Entry & Organization

The raw dataset was structured into four main tables:

* CUSTOMER
* PRODUCT
* STORE
* SALES

## 🧼 Data Cleaning & Transformation

The dataset was cleaned and standardized to improve accuracy and consistency:

* Corrected formatting errors in text fields
* Standardized date format for `Order_Date`
* Handled missing values
* Removed extra spaces and corrected column names
* Converted text to uppercase for consistency
* Standardized percentages and decimal values

## 📊 Excel Formulas & Functions Used

### 🔢 Aggregation Functions

* Total Quantity Sold – `SUM`
* COD Unit Price – `SUMIFS`
* Credit Card Revenue – `SUMIFS`
* PayPal Sales – `SUMIF`
* Total Discount – `SUM`

### 🧠 Logical Functions

* High/Low Order Classification – `IF`
* Order Value Segmentation – `IFS`

  * Premium (>2000)
  * High (>1000)
  * Normal (<1000)
* Discount Condition – `IF` + `AND`

### 📈 Average Calculations

* Average Unit Price – `AVERAGE`
* Average Quantity per Order – `AVERAGE`
* PayPal Average Sales – `AVERAGEIF`
* Credit Card + Quantity > 2 – `AVERAGEIFS`

### 📝 Text & Lookup Functions

* Merge Sale ID & Quantity – `CONCAT`
* Extract Year – `YEAR`
* Convert Month to Text – `TEXT`
* Data Lookup – `VLOOKUP` (Customer & Product details)

## 📊 Data Analysis (Pivot Tables)

* Category-wise Total Sales
* Order Quantity Distribution
* Year-wise Sales & Payment Type Analysis
* Monthly Sales Trend
* Store-wise Performance Comparison
* Sparklines for trend visualization

## 📉 Data Visualization

* Pie Chart – Category-wise Sales Distribution
* Column Chart – Year-wise Payment Type Analysis
* Line Chart – Monthly Sales Trend
* Scatter Chart – Quantity Distribution
* Slicers – City-wise interactive filtering

## 🔍 Key Business Insights

### 🏷️ Category Performance

* Sports (25%) and Electronics (23%) are the top-performing categories
* Together they contribute nearly 48% of total sales
* Beauty (15%) is the lowest performing category

### 📅 Monthly Sales Trend

* Sales peak in April (~1200)
* Decline observed until February (~980)
* Lowest point in May (~930)
* Strong recovery after May

### 💳 Payment Type Analysis

* Credit Card is the highest revenue contributor
* COD is stable but lower
* PayPal remains consistent

### 📦 Order Quantity Pattern

* Most orders are for 1–2 items
* Peak at quantity 2 (~515 orders)
* Decline in higher quantities

## 🛠️ Tools & Technologies

* Microsoft Excel
* Power Query
* Pivot Tables
* Data Visualization (Charts & Slicers)

## 📌 Key Skills Demonstrated

* Data Cleaning & Transformation
* Data Modeling
* Excel Formulas (SUMIFS, IF, IFS, VLOOKUP, etc.)
* Business Intelligence Reporting
* Dashboard Creation

## 📊 Final Outcome

An interactive Excel dashboard that provides clear visibility into:

* The analysis revealed that a small group of products contributes to a large portion of total sales, indicating a strong dependency on top-performing items.
* Certain regions consistently generated higher revenue, highlighting key markets for business expansion and targeted marketing strategies.
* Seasonal trends were observed, showing fluctuations in sales during specific time periods, which can help in better demand forecasting.
* Profitability varied significantly across product categories, suggesting the need to optimize pricing and reduce low-margin items.
* Customer purchasing patterns indicate repeat buying behavior in some segments, which can be leveraged through loyalty programs and personalized offers.
* Interactive dashboards provided a clear and actionable view of KPIs such as total sales, profit, and order trends, enabling faster decision-making.


