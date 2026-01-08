# 🎫 Customer Support SLA Dashboard (Excel)

An interactive Excel dashboard built to analyze customer support tickets and evaluate SLA (Service Level Agreement) performance using real-world data cleaning, KPIs, pivot tables, and slicers.

---

## 📌 Project Overview
This project focuses on analyzing resolved customer support tickets to measure support efficiency and service quality.  
The dashboard helps identify SLA breaches, resolution performance, and customer satisfaction trends across regions and products.

---

## 🛠 Tools & Technologies
- Microsoft Excel
- Pivot Tables & Pivot Charts
- KPI Cards
- Slicers
- Excel Formulas (COUNTIF, AVERAGE, IF, etc.)

---

## 📂 Dataset Description
- Large simulated customer support ticket dataset (150–200+ records)
- Multiple regions: North, South, East, West
- Products: Mobile, Laptop, Printer, Desk, Chair
- Issue types such as login issues, hardware problems, and system errors
- Includes resolution time, SLA performance, and CSAT scores

---

## 🧹 Data Cleaning & Preparation
The following steps were performed:
- Removed rows with missing critical values
- Trimmed and standardized text fields (Region, Product, Status)
- Ensured numeric consistency in resolution time and CSAT
- Focused analysis on resolved (closed) tickets
- Created a derived column `SLA_Status` to classify tickets as:
  - Within SLA
  - SLA Breach

---

## 📊 KPI Metrics
The dashboard includes the following KPIs:
- **Total Tickets**
- **SLA Breaches**
- **% Tickets Within SLA**
- **Average Resolution Time (Hours)**
- **Average CSAT Score**

All KPIs dynamically update based on slicer selections.

---

## 📈 Dashboard Visualizations
- Tickets by Region (Bar Chart)
- SLA Breach vs Within SLA (Pie / Donut Chart)
- Average Resolution Time by Product (Column Chart)
- Average CSAT by SLA Status (Bar Chart)

---

## 🧠 Key Insights
- Most customer support tickets are resolved within SLA limits.
- SLA breaches are higher for certain products such as Printers.
- Tickets with SLA breaches generally have lower CSAT scores.
- Faster resolution time strongly correlates with higher customer satisfaction.
- Regional and product-based filtering helps identify operational bottlenecks.

---

## 📎 How to Use
1. Download the Excel file from this repository
2. Open it using Microsoft Excel (desktop version recommended)
3. Use slicers to filter data by Region, Product, and SLA Status
4. Observe changes in KPIs and charts dynamically

---

## ⭐ Project Purpose
This project was created to:
- Practice real-world Excel data analysis
- Build a professional dashboard project for portfolio
- Demonstrate SLA and operational performance analysis skills

---

## 👤 Author
**Aman Chaurasia**
