# 🚦 Traffic Accident Analysis Dashboard Using Power BI

> **Author:** Vishwa Sai Challa  
> **Project Type:** Data Analysis & Visualization  
> **Tools:** Power BI Desktop (Feb 2024 Edition), Bravo Tool, Measure Killer
> **Dataset Size:** 200,000+ traffic crash records (From Kaggle)
---

## 📌 Project Overview

This Power BI dashboard explores a large dataset of traffic accident reports to uncover trends, assess crash severity, evaluate financial impact, and support public safety decision-making. The dashboard enables users to interactively explore accident patterns across time, environmental conditions, and contributing causes. It is structured into modular, data-rich pages with drill-down capabilities, dynamic tooltips, and DAX-powered KPIs.

---

## 🧰 Tools and Technologies

- **Power BI Desktop** – Visualization and report development
- **Power Query** – Data ingestion and transformation
- **DAX (Data Analysis Expressions)** – Custom measures
- **Git + GitHub** – Version control and documentation
- **Bravo Tool** – Date Table and Time Intelligence functions
- **Measure Killer** – Cleaned unused columns and measures.

---

## 📊 Dataset Description

The dataset includes over 200,000 traffic crash records with fields such as:

- Crash date & time
- Traffic control device, road surface & alignment
- Weather and lighting conditions
- Primary cause & crash type
- Damage estimates
- Number of units involved
- Injury severity levels

---

## 🧹 Data Cleaning & Enrichment (ETL)

Using Power Query:
- Promoted headers and corrected data types
- Standardized missing values using "Not Reported"
- Eliminated inconsistent categorical labels
- Created **new calculated columns**:
  - `Injury Severity Level`: mapped by crash outcome
  - `Crash Weekday Name`: derived from crash date
  - `Daylight Cycle`: grouped lighting conditions
- Built a custom **Date Table** for YTD, MTD, and QTD calculations
- Used Measure Killer for cleaning Unused Columns and Measures

---

## ⚙️ DAX Measures Developed

- Total Crash Count
- Injury vs. Non-Injury Crash Count
- Fatal, Incapacitating, and Minor Injury Counts
- Damage Aggregation by Category (e.g., \$500 or less, \$1500+)
- Units Involved per Crash
- Time Intelligence: YTD, MTD, YOY Growth
- Generated Date Table and Time Intelligence measures using Bravo Tool

---

## 🖥️ Dashboard Structure

The report is divided into **five interactive pages**:

### 1. Executive Summary  
- Overview of total crashes, injury distribution, and weather conditions  
- High-level KPIs with dynamic slicers
<img width="668" alt="image" src="https://github.com/user-attachments/assets/abff8a0a-0efb-469a-994d-a8ffef9e2719" />

### 2. Time Trend Analysis  
- Line chart showing crash frequency over months and years  
- Dynamic tooltips and date filtering
- Year Trand Graph Used a Custom Tool Tip
  <img width="671" alt="image" src="https://github.com/user-attachments/assets/dfc98326-2bfd-473e-9422-29a08ccfe379" />

### 3. Damage and Units Report  
- Toggle button to switch between **Damage Value** and **Number of Units**  
- Card visuals for high-damage crashes  
- Breakdown by environment and lighting
- Included Toggle feature for KPIs.
  <img width="668" alt="image" src="https://github.com/user-attachments/assets/14188181-e50d-428b-887d-0f440a933f5b" />

### 4. Decomposition Tree  
- Root-cause analysis of crashes by severity, weather, and road type  
- Interactive drill-down to identify key risk contributors
  <img width="670" alt="image" src="https://github.com/user-attachments/assets/651de4f9-917e-468c-b844-475febea2d92" />


### 5. Tooltip Page  
- Embedded as a popup inside visuals  
- Provides deep contextual info on hover
<img width="841" alt="image" src="https://github.com/user-attachments/assets/d7c30af3-3c4e-4bb9-ab36-2577e9a2ec40" />

---

## 💡 Key Insights

- Most crashes occurred under **clear daylight** conditions
- Crash counts peaked in **October** and on **Fridays**
- High-damage crashes contributed to the **majority of financial loss**
- Straight roadways and dry conditions were frequent factors

---

## 🔍 Evaluation & Results

- Dashboard performance was smooth on desktop with 16GB RAM
- Modular pipeline ensured minimal breakage with data updates
- Dynamic visual elements (tooltips, toggles) enhance interactivity

---

## 🧠 Lessons Learned

- Power BI's combination of **Power Query + DAX + visual storytelling** is ideal for public data analytics
- Clean schema design and early feature engineering simplified DAX later
- The Decomposition Tree is powerful for root-cause analysis, but purely descriptive

---

## 🧭 Future Enhancements

- Integrate **real-time traffic accident feeds** via APIs
- Add **GIS maps and heatmaps** for spatial crash hotspots
- Use **predictive modeling** (e.g., crash severity prediction with ML)
- Deploy via **Power BI Service for web-based access**

---

## 📂 Repository Structure

```bash
📦 traffic-accident-report
├── README.md
├── Dashboard and Datset/
│   ├── Final_Traffic_Accident_Report.pbix
│   ├── traffic_dataset
├── resources/
│   ├── Traffic_Accident_Analysis_Report.pdf
│   ├── Damage and Units.png
│   ├── Monthly Crashes Plot.png
│   ├── Sample Dashboard.png
│   ├── System Architecture.png
│   ├── Traffic_Accidents.json
```

---

## 📫 Contact

- **Author**: Vishwa Sai Challa  
- **Email**: cvishwasai@gmail.com
- **LinkedIN**: https://www.linkedin.com/in/vishwasai
- **GitHub**: [github.com/VishwaSaiChalla](https://github.com/VishwaSaiChalla)

---
