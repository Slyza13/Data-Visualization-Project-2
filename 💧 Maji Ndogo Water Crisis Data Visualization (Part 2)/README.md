# 💧 Maji Ndogo Water Crisis Data Visualization (Part 2)

[![Made with SQL](https://img.shields.io/badge/Made%20with-SQL-blue?logo=sqlite)](https://www.sqlite.org/)
[![Made with Power BI](https://img.shields.io/badge/Made%20with-Power%20BI-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Data Analysis](https://img.shields.io/badge/Field-Data%20Science-FF6F00?logo=google-analytics&logoColor=white)]()
[![Visualization](https://img.shields.io/badge/Visualization-Power%20BI%20Dashboard-005571)]()

[![GitHub Repo Size](https://img.shields.io/github/repo-size/YOUR-USERNAME/YOUR-REPO)]()
[![GitHub last commit](https://img.shields.io/github/last-commit/YOUR-USERNAME/YOUR-REPO)]()
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?logo=github)]()

---

## 📌 Project Summary: Building an Interactive Water Access Dashboard (Part 2)

**Objective:**  
To transform a multi-table SQL dataset into an interactive Power BI dashboard, enabling deep analysis of water access, quality, safety, and social challenges in the fictional region of **Maji Ndogo**.  

---

## 🔑 Key Components  

### 1. Data Model Foundation  
- Imported multiple SQL-cleaned tables into Power BI.  
- Solved a **many-to-many issue** with crime data by bridging through the `location` table.  
- Final schema: **multi-star schema** linking fact tables (`visits`, `water_source_related_crime`) with shared dimensions (`location`).  

### 2. National-Level Dashboard  
- **Map of provinces**, urban vs. rural split, treemap of water source usage, and bar charts.  
- Fully interactive: province selections update all visuals instantly.  

### 3. Queue Analysis Dashboard  
- Added **day_of_week** and **hour_of_day** using Power Query.  
- Visuals: queue times by day/hour, demographics of men/women/children in queues.  
- Cross-filtering allows deep insights (e.g., queue composition by province and time).  

### 4. Water Source Pollution Dashboard  
- Mapped pollution testing results.  
- Categorized wells: **Clean**, **Chemically Contaminated**, **Biologically Contaminated**.  
- Interactive drilldowns: highlight problem provinces by contamination type.  

### 5. Crime & Safety Dashboard  
- Connected crime data to location + timestamps.  
- Charts reveal patterns by **victim type, crime type, time of day, and province**.  
- **Critical Findings:**  
  - Women = twice as likely to be victims as men.  
  - Harassment & assault dominate crime categories.  
  - Crimes peak in **early morning** and **late evening**.  

---

## 🖼️ Screenshots  

| National Overview | Queue Analysis |
|-------------------|----------------|
| ![National Overview] | ![Queue Analysis]|

| Pollution Dashboard | Crime & Safety |
|---------------------|----------------|
| ![Pollution Dashboard]| ![Crime & Safety]

---

## 📊 Critical Insights  

- Gender disparities in water access and safety are **systemic**.  
- Queue times are **socially stratified** (women + children bear the brunt).  
- Certain provinces (e.g., Amanzi, Kilimani) demand urgent attention.  
- Linking crime with water access surfaces risks invisible in tabular data.  

---

## 🚀 Next Steps  

- Refine visuals with KPIs & simplified storytelling layouts.  
- Expand to future phases (e.g., linking water access with education & health).  
- Test advanced Power BI features (drill-through reports, custom tooltips).  

---

## 📚 Attribution  

This project was completed as part of the **ALX / ExploreAI Academy Data Science Program**.  
Dataset and problem framing are **fictional** and created for **educational purposes**.  



