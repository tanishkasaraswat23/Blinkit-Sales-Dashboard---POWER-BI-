# 📊 Blinkit Sales Dashboard using Power BI

An interactive 4-page Power BI dashboard built on Blinkit grocery sales data, designed to help stakeholders track revenue performance, compare outlets, and identify top and bottom-performing products — all connected live to a MySQL database.

> 🔗 This dashboard is powered by the SQL project available here: **[Blinkit-Sales-Analytics-SQL](https://github.com/tanishkasaraswat23/Blinkit-Sales-Analytics-SQL-)**

---

## 📌 Project Overview

This dashboard transforms raw grocery sales data into an easy-to-navigate visual report across **8,523 sales records**, **10 outlets**, and **16 product categories**. It connects directly to a MySQL view (`vw_outlet_performance`) to keep reporting consistent with the underlying SQL analysis.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — dashboard design & DAX measures
- **MySQL** — data source (via MySQL Connector/NET)
- **DAX** — custom measures for KPIs

---

## 📄 Dashboard Pages

### 1️⃣ Overview
- KPI Cards: Total Revenue, Average Sale Value, Total Items Sold, Total Outlets
- Revenue by Item Type (Bar Chart)
- Revenue by Outlet Type (Donut Chart)

### 2️⃣ Outlet Analysis
- Outlet-wise Revenue (Bar Chart)
- City Tier-wise Revenue Comparison
- Outlet Performance Summary Table

### 3️⃣ Product Analysis
- Top 10 Best-Selling Items
- Bottom 10 Worst-Performing Items
- Low Fat vs Regular Item Revenue Comparison

### 4️⃣ Trends
- Year-wise Revenue Trend (Line Chart)
- Outlet Size Impact on Sales

---

## 📐 Key DAX Measures

```dax
Total Revenue = SUM(blinkit_cleaned[sales])

Avg Sale Value = AVERAGE(blinkit_cleaned[sales])

Total Items Sold = COUNTROWS(blinkit_cleaned)

Total Outlets = DISTINCTCOUNT(blinkit_cleaned[outlet_id])
```

---

## 🔑 Key Insights

- **Total Revenue:** ₹12,01,681.49 across all outlets
- **Supermarket Type1** outlets drive ~65% of total revenue
- **Tier 3** cities outperform Tier 1 & Tier 2 in total sales
- **Low Fat** items generate significantly higher revenue than Regular items
- Outlet size shows minimal impact on average sale value per item

---

## 📁 Repository Structure

```
Blinkit-Sales-Dashboard-PowerBI/
│
├── Blinkit_Dashboard.pbix        # Power BI file
├── README.md                     # Project documentation
└── screenshots/
    ├── page1_overview.png
    ├── page2_outlet_analysis.png
    ├── page3_product_analysis.png
    └── page4_trends.png
```

---

## 🚀 How to Use

1. Download `Blinkit_Dashboard.pbix`
2. Open in Power BI Desktop
3. Update the MySQL connection details (Server & Database) under **Transform Data → Data Source Settings**
4. Refresh the report to load live data

---

## 👩‍💻 Author

**Tanishka Saraswat**

[LinkedIn:# 📊 Blinkit Sales Dashboard using Power BI

An interactive 4-page Power BI dashboard built on Blinkit grocery sales data, designed to help stakeholders track revenue performance, compare outlets, and identify top and bottom-performing products — all connected live to a MySQL database.

> 🔗 This dashboard is powered by the SQL project available here: **[Blinkit-Sales-Analytics-SQL](https://github.com/tanishkasaraswat23/Blinkit-Sales-Analytics-SQL-)**

---

## 📌 Project Overview

This dashboard transforms raw grocery sales data into an easy-to-navigate visual report across **8,523 sales records**, **10 outlets**, and **16 product categories**. It connects directly to a MySQL view (`vw_outlet_performance`) to keep reporting consistent with the underlying SQL analysis.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — dashboard design & DAX measures
- **MySQL** — data source (via MySQL Connector/NET)
- **DAX** — custom measures for KPIs

---

## 📄 Dashboard Pages

### 1️⃣ Overview
- KPI Cards: Total Revenue, Average Sale Value, Total Items Sold, Total Outlets
- Revenue by Item Type (Bar Chart)
- Revenue by Outlet Type (Donut Chart)

### 2️⃣ Outlet Analysis
- Outlet-wise Revenue (Bar Chart)
- City Tier-wise Revenue Comparison
- Outlet Performance Summary Table

### 3️⃣ Product Analysis
- Top 10 Best-Selling Items
- Bottom 10 Worst-Performing Items
- Low Fat vs Regular Item Revenue Comparison

### 4️⃣ Trends
- Year-wise Revenue Trend (Line Chart)
- Outlet Size Impact on Sales

---

## 📐 Key DAX Measures

```dax
Total Revenue = SUM(blinkit_cleaned[sales])

Avg Sale Value = AVERAGE(blinkit_cleaned[sales])

Total Items Sold = COUNTROWS(blinkit_cleaned)

Total Outlets = DISTINCTCOUNT(blinkit_cleaned[outlet_id])
```

---

## 🔑 Key Insights

- **Total Revenue:** ₹12,01,681.49 across all outlets
- **Supermarket Type1** outlets drive ~65% of total revenue
- **Tier 3** cities outperform Tier 1 & Tier 2 in total sales
- **Low Fat** items generate significantly higher revenue than Regular items
- Outlet size shows minimal impact on average sale value per item

---

## 📁 Repository Structure

```
Blinkit-Sales-Dashboard-PowerBI/
│
├── Blinkit_Dashboard.pbix        # Power BI file
├── README.md                     # Project documentation
└── screenshots/
    ├── page1_overview.png
    ├── page2_outlet_analysis.png
    ├── page3_product_analysis.png
    └── page4_trends.png
```

---

## 🚀 How to Use

1. Download `Blinkit_Dashboard.pbix`
2. Open in Power BI Desktop
3. Update the MySQL connection details (Server & Database) under **Transform Data → Data Source Settings**
4. Refresh the report to load live data

---

## 👩‍💻 Author

**Tanishka Saraswat**
B.Tech AI & ML | Aspiring Data Analyst / BI Analyst
[LinkedIn:www.linkedin.com/in/tanishka-saraswat] | [GitHub:@tanishkasaraswat23]

