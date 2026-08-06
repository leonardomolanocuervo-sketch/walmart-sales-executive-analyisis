# walmart-sales-executive-analyisis
Executive sales performance, spatial efficiency and inventory optimization analysis for Walmart stores using Excel

# 🛒 Walmart 2012 Sales Analysis & Executive Inventory Strategy (Excel)

## 📌 Project Overview
This project delivers a commercial and financial performance analysis of Walmart's 2012 weekly sales across multiple store types and product departments. 

The primary goal was to process raw relational transactional tables, merge operational dimensions, and calculate key efficiency metrics—such as *Sales per Square Meter ($/m²)* and *Departmental Sales Share (%)*—to provide executive-level recommendations regarding budget reallocation, inventory protection, and floor-space optimization.

---

## 🛠️ Tools & Techniques Used
* *Tool:* Microsoft Excel (100% Advanced Excel Formulas & Analytical Features)
* *Data Transformation & Modeling:* XLOOKUP / VLOOKUP to join raw sales records with store size and department metadata tables.
* *Data Cleaning & Standardization:* Date formatting, handling missing values, and generating clean time-series keys.
* *Data Summarization & Analysis:* Dynamic Pivot Tables, nested formulas (SUMIFS, AVERAGEIFS), floor efficiency metrics ($/m²), and cross-departmental share analysis.
* *Executive Presentation:* Executive dashboard layout and strategic decision framework.

---

## 🧹 Data Cleaning & Relational Architecture

The workbook integrates three raw data sources (raw_ventas, raw_departamento, raw_tiendas) into a unified master model (Clean_ventas):

1. *Table Relational Merging:* Enriched over 95,000 transaction records by linking Store IDs and Department IDs with metadata to bring in Store Type (A, B), Store Size (sq. meters/feet), and Department Names.
2. *Key Metric Generation:* Calculated revenue density (*Sales per m²*) to evaluate floor space profitability across different retail categories.
3. *Data Aggregation:* Built structured Pivot Tables to isolate 2012 sales trends and evaluate performance across 14 commercial departments.

---

## 📊 Strategic Executive Findings

### 🏆 Top Performing Departments (Core Drivers)
* *Leading Categories:* *Pantry & Staples* (Despensa y Básicos), *Fresh Food* (Comida Fresca), and *Household & Paper Products* (Artículos del Hogar y Papel).
* *Impact:* These three departments represent the overwhelming majority of revenue and drive maximum foot traffic and high sales density per square meter.

### ⚠️ Underperforming Departments (Low Efficiency)
* *Lowest Contributors:* *Lawn & Garden* (Jardín y Vida al Aire Libre) and *Office, School & Crafts* (Oficina, Escuela y Manualidades).
* *Impact:* Generates *less than 2% of total sales revenue*, resulting in inefficient store floor-space allocation.

---

## 💡 Commercial Implications & Action Plan

1. *Inventory Protection & Hot-Spot Layout:*
   * Place top-performing categories (Pantry, Fresh Food) in prime store traffic corridors ("Hot Zones") to maximize cross-selling.
   * Implement safety stock protocols and strict inventory management to prevent stock-outs on critical revenue drivers.
2. *Floor Space & Floor Budget Optimization:*
   * *Reallocate Floor Space:* Reduce the physical footprint of low-density departments (<2% share, e.g., Lawn & Garden) and reallocate sq. footage to high-yielding categories.
   * *Private Label Substitution:* If margins remain low for underperforming categories, replace secondary brands with higher-margin Walmart private labels or trending seasonal merchandise.

---

## 📁 Repository Structure
```text
├── Proyecto 2_ Resumen Ejecutivo de Ventas Walmart.xlsx  # Complete workbook (Raw data, Cleaned data, Pivots, & Executive Summary)
└── README.md                                             # Executive documentation
