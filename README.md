# Business Intelligence & Data Visualization Project  
**Course:** DSA 3050A — Business Intelligence & Data Visualization  

---

## Project Overview
This project demonstrates the practical application of **Business Intelligence (BI)** concepts using **Power BI**, based on the *Sample Superstore* dataset.  

The work follows the complete BI lifecycle:
- Raw data ingestion
- Data cleaning and transformation
- Feature engineering and derived columns
- Data modeling using a **Star Schema**
- Interactive dashboard development
- Publishing and documentation

The final output is an **interactive Power BI dashboard** supported by a **fully documented analytical report**.

---

##  Files in This Repository
The repository contains **only the core required deliverables**, as listed below:

```text
Business-Intelligence-PowerBI-DSA3050A-602/
├── DSA3050_PowerBI_Report.pdf
├── DSA3050_PowerBI_MidSem602.pbix
├── SampleSuperstore.csv
└── README.md
```

---


###  File Descriptions
- **SampleSuperstore.csv**  
  Raw dataset used for analysis (sales, profit, region, category, dates, etc.)

- **DSA3050_PowerBI_MidSem602.pbix**  
  Power BI report file containing:
  - Data transformation steps
  - Derived columns
  - Data model (Star Schema)
  - Dashboards and visuals

- **DSA3050_PowerBI_Report.pdf**  
  Comprehensive project report containing:
  - Data preparation steps with explanations
  - Applied transformation evidence (screenshots)
  - Data model relationships
  - Dashboard visuals and justification

---

##  Data Preparation & Transformation
All transformations were performed in **Power Query** and include:

- Removal of unnecessary or redundant columns
- Standardization of text fields (e.g., state codes)
- Handling of zero and invalid values
- Date feature extraction:
  - Year
  - Month
  - Quarter
- Derived columns such as:
  - **Sales Bands** (categorizing sales magnitude)
  - **Profit / Loss Flag**
- Creation of clean fact and dimension tables

All transformation steps are fully documented in the PDF report.

---

##  Data Modeling
A **Star Schema** was implemented to ensure optimal analytical performance and clarity.

### Model Structure:
- **Fact Table**
  - Sales, Profit, Quantity, Discount, Order Date, Ship Date

- **Dimension Tables**
  - Date Dimension
  - Location Dimension
  - Product Dimension

### Modeling Best Practices Applied:
- One-to-many relationships
- Correct cardinality
- Single-direction filtering
- Avoidance of many-to-many relationships
- Hiding technical merge keys in Model View
- Logical table organization

Screenshots of the data model and relationship configurations are included in the PDF report.

---

##  Dashboard Features
The Power BI dashboard includes:

### ✔ KPI Summary
- Total Sales
- Total Profit
- Quantity Sold
- Average Discount

### ✔ Trend Analysis
- Sales and profit trends over time
- Yearly and monthly performance patterns

### ✔ Comparative Analysis
- Regional performance comparison
- Category and sub-category analysis

### ✔ Distribution Analysis
- Sales distribution using bands
- Profit vs loss segmentation

### ✔ Interactivity
- Slicers for region, category, segment, and time
- Cross-filtering between visuals
- Dynamic drill-down exploration

---

##  Published Dashboard
🔗 **Public Power BI Dashboard Link:**  
👉 *(https://app.powerbi.com/groups/me/reports/052e247f-a6b2-430c-86ab-e3834f51b949/14d9d1856680a04a02ca?experience=power-bi)*

---

##  Full Project Documentation
📘 **To review the complete analytical process, applied steps, and evidence:**  
👉 **[Click here to open the project PDF](./DSA3050_PowerBI_Report.pdf)**

This document includes:
- Step-by-step transformations
- Screenshots of applied steps
- Data model relationships
- Dashboard evidence

> GitHub may not preview  this whole PDF due to file size and formatting.  
> Please **download the file** if issue persists to view the full report.
> 
---

##  How to Navigate This Project (For Reviewers)
1. **Start with the PDF report** — full explanation and screenshots  
2. **Open the PBIX file** — explore transformations, model, and visuals  
3. **Use the dashboard link** — interact with published visuals  

---

##  Tools & Technologies
- Power BI Desktop
- Power BI Service (Publish to Web)
- Power Query
- DAX (calculated columns and measures)

---

##  Author
**Selmah Tzindori**

---

##  Notes
- This project was completed as part of an academic assessment.
- All transformations and models follow BI best practices.
- The dataset was sourced from Kaggle

---
