# 📦📊 Supply Chain Data Analysis using SQL  
_18 SQL queries unlocking operational efficiency, customer demand patterns, and sales intelligence._

This project dives deep into supply chain performance using SQL, identifying how customer behavior, order patterns, and product demand impact overall business outcomes.

---

## 🔍 Project Overview

The analysis focuses on understanding:

- 📦 Order trends across months  
- 👥 Customer-level sales contribution  
- ❌ Cancellation patterns  
- 🏷️ Item classifications (ABC analysis)  
- 🔄 Comparison of ordered vs. cancelled products  

The results uncover operational bottlenecks and highlight top revenue drivers.

---

## 🛠 Skills & Techniques Used

- **MySQL**
- **Joins**
- **Window Functions**  
  `ROW_NUMBER`, `NTILE`, `SUM() OVER`, cumulative totals  
- **Aggregation Queries**
- **Subqueries & Nested Logic**
- **ABC Classification Logic**

---

## 📈 Key Insights (Business-Ready Findings)

### 🔸 1. Order Volume Peaks in Jan–Feb  
These two months showed the **highest order activity**, indicating strong seasonal demand.

### 🔸 2. Sales Dominated by Top Customers  
Top **5 customers contributed 50%+** of total revenue — indicating a concentrated customer base.

### 🔸 3. Cancellation-Heavy Items Identified  
High-cancellation items were flagged, enabling supply chain teams to investigate **delays, defects, or vendor issues**.

### 🔸 4. ABC Classification (A/B/C Segments)  
Items were segmented based on sales contribution:  
- **A-Class:** High-value, top-priority products  
- **B-Class:** Moderate contributors  
- **C-Class:** Low-value but high volume  

---

## 🧹 Tasks Performed

### 🔍 1. JOIN-Based Analysis  
- Compared **ordered vs. canceled** items  
- Identified cancellation ratio per SKU  

### 🔢 2. Window Function Analytics  
Used SQL window functions to generate:  
- Customer rankings  
- NTILE() segmentation  
- Cumulative sales totals  

### 📊 3. Classification & Segmentation  
- High / Medium / Low **order classification**  
- **ABC classification** using % sales contribution  

### 🧮 4. KPI Computation  
Created SQL outputs for:  
- Monthly order counts  
- Top customers  
- High cancellation SKUs  
- Contribution margin groups 
