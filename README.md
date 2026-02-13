# E-Commerce Sales & Customer Insights Dashboard (Excel)

![Ecommerce Dashboard](./assets/Ecommerce-Dashboard.jpg)

## 📌 Project Overview
This project is an **interactive Excel dashboard** designed to analyze e-commerce sales, customer behavior, product performance, logistics efficiency, and customer satisfaction.  
The dashboard transforms raw transactional data into **actionable business insights** using Excel features such as Pivot Tables, Charts, Slicers, and Conditional Formatting.

---

## 🎯 Business Problem
E-commerce businesses often face challenges such as:
- Data scattered across multiple fields without a unified view
- Difficulty tracking sales trends and performance KPIs
- Lack of visibility into customer buying behavior and preferences
- Limited understanding of product demand by customer segments
- Inability to easily monitor delivery performance and customer satisfaction

**Objective:**  
To build a **single, dynamic Excel dashboard** that answers critical business questions and supports data-driven decision-making.

---

## 📊 Key Business Questions Answered
- How many orders are placed and what is the total revenue generated?
- How are quantity and sales trending over the last 13 weeks?
- Which sales channels do customers prefer?
- How many items do customers typically buy per order?
- Which products are most popular across different gender segments?
- Where are customers geographically located?
- How long does it take to deliver orders?
- How satisfied are customers over time?

---

## 🧩 Problems Identified & Excel-Based Solutions

### 1. Disorganized and Raw Data
**Problem:**  
Raw order data lacked consistency and structure, making analysis difficult.

**Solution (Excel):**
- Standardized column names and formats
- Converted dataset into an **Excel Table** for dynamic range handling
- Ensured consistent categorical values (Gender, Channel, Location)

---

### 2. KPI Tracking Was Not Centralized
**Problem:**  
No single place to monitor overall business performance.

**Solution (Excel):**
- Created KPI cards using Pivot Tables:
  - Total Orders
  - Total Quantity Sold
  - Total Revenue
  - Average Customer Rating
  - Average Delivery Time

---

### 3. Sales Trend Analysis Was Missing
**Problem:**  
Daily data did not clearly show performance patterns.

**Solution (Excel):**
- Grouped order dates into **weekly periods**
- Built a **13-week trend line** showing Quantity and Sales Amount
- Enabled performance spike and drop analysis

---

### 4. Customer Channel Preferences Were Unclear
**Problem:**  
The business did not know which channels customers preferred.

**Solution (Excel):**
- Created a matrix Pivot Table with:
  - Rows: Order Channel
  - Columns: Gender Segment
- Applied conditional formatting to highlight high-performing segments

---

### 5. Basket Size Behavior Was Unknown
**Problem:**  
Order quantity totals did not explain customer purchasing habits.

**Solution (Excel):**
- Grouped quantities into purchase buckets (1, 2, 3, 4, 5, 6–10, >10)
- Built a bar chart to visualize basket-size distribution

---

### 6. Product Demand by Segment Was Hard to Identify
**Problem:**  
Product performance lacked demographic context.

**Solution (Excel):**
- Built product-wise Pivot Charts
- Segmented demand by gender category
- Sorted products to highlight top sellers

---

### 7. Geographic Demand Was Hard to Visualize
**Problem:**  
Text-based location data did not show regional demand clearly.

**Solution (Excel):**
- Used Excel Map Chart to visualize customer distribution
- Displayed quantity and revenue intensity by region/state

---

### 8. Delivery Performance Monitoring Was Limited
**Problem:**  
Average delivery time hid delays and variability.

**Solution (Excel):**
- Grouped delivery days into ranges
- Built a delivery-time distribution chart
- Identified fulfillment bottlenecks

---

### 9. Customer Satisfaction Trends Were Not Visible
**Problem:**  
Overall ratings did not reveal monthly sentiment changes.

**Solution (Excel):**
- Analyzed ratings month-wise
- Visualized rating distribution (2–5 scale)
- Tracked satisfaction improvement or decline over time

---

## 🧮 Tools & Excel Features Used
- Pivot Tables & Pivot Charts
- Excel Tables (Structured References)
- Slicers (Gender, Order Mode)
- Conditional Formatting
- Map Charts
- Data Grouping (Weeks, Buckets)
- Calculated Metrics & Aggregations

---

## 🖱️ Dashboard Interactivity
The dashboard allows users to:
- Filter insights by **Gender**
- Filter insights by **Order Mode / Channel**
- Automatically refresh insights when new data is added

---
