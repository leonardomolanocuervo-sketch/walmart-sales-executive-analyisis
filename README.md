# walmart-sales-executive-analyisis
Executive sales performance, spatial efficiency and inventory optimization analysis for Walmart stores using Excel

# 📊 E-Commerce Sales Data Cleaning & Executive Analysis (Excel)

## 📌 Project Overview
This project focuses on conducting end-to-end data cleaning, transformation, and exploratory commercial analysis on an e-commerce sales dataset for Q4. 

The primary objective was to transform raw, unstructured transactional data into a clean, structured model to extract key performance indicators (KPIs) and deliver actionable business insights regarding revenue, product performance, and regional sales distribution.

---

## 🛠️ Tools & Techniques Used
* *Tool:* Microsoft Excel
* *Data Cleaning & Preprocessing:* Handling missing values, standardizing string/text data (capitalization & regional naming), splitting complex product attributes.
* *Data Modeling & Feature Engineering:* Creating custom categorical tags (Category, Type, Specifications) from multi-attribute text.
* *Data Aggregation & Summarization:* Formulas (SUMIF, AVERAGE, COUNTIF), Pivot Tables, and descriptive executive metrics.

---

## 🧹 Data Cleaning & ETL Process

The raw dataset contained *753 transactions* with several quality issues that were systematically resolved in the Datos_Limpios phase:

1. *Text Standardization:* Fixed inconsistent city naming conventions (e.g., standardizing capitalization and regional variants for cities like Monterrey and Bogotá).
2. *Missing Value Imputation:* Identified and resolved 10 missing entries in Precio unitario and 6 missing entries in Monto total using deterministic price mapping and quantity back-calculations.
3. *Feature Engineering:* Deconstructed composite product strings (e.g., Laptop-Oficina-32GB) into three distinct analytical dimensions:
   * *Category:* Laptop, Auriculares, Tablet
   * *Type:* Oficina, Gaming, Bluetooth, Estándar
   * *Specifications:* 8GB, 16GB, 32GB

---

## 📊 Key Commercial Findings & Metrics

Based on the processed executive summary, the core performance metrics for the period are:

| Metric | Value |
| :--- | :--- |
| *Total Quarterly Revenue* | *$2,944,620.61* |
| *Total Transactions* | *753* |
| *Average Order Value (AOV)* | *$3,910.52* |
| *Top Performing City (by Sales)* | *Monterrey* |
| *Best-Selling Product (by Volume)* | *Laptop-Oficina-32GB* |

---

## 💡 Executive Insights & Recommendations

* *Regional Dominance:* Monterrey leads total sales volume across all regions, suggesting strong demand in this market. Recommendations include optimizing local warehouse stock and targeted marketing campaigns.
* *Product Mix Strategy:* High-spec operational hardware (Laptop-Oficina-32GB) generates the highest volume, indicating strong demand from enterprise or remote-work customer segments.
* *Data Quality Governance:* Future transactional systems should implement strict validation controls at input to prevent missing price values and inconsistent text formats.

---

## 📁 Repository Structure
```text
├── Proyecto 1_ Limpieza y resumen de datos en hojas de cálculo.xlsx  # Main workbook with raw & cleaned sheets
└── README.md                                                         # Project documentation
