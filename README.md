# 🚦 Regulatory Affairs of Road Accident Data 2020 — India

**Tableau Interactive Dashboard & Data Analysis Report**

This project analyses road accident patterns across India’s million-plus cities for the year 2020, focusing on **cause categories**, **city types**, **injury/fatality severity**, and **policy-relevant insights**.  
The goal is to uncover trends, high-risk factors, and actionable recommendations for improving road safety.

🔗 **Live Dashboard on Tableau Public**: [View Here](https://public.tableau.com/app/profile/dharana.singh/viz/RegulatoryAffairsofRoadAccidentData2020India2_0/HomeNavigation)  
📄 **Full Analysis Report (PDF)**: [View Report](Regulatory%20Affairs%20of%20Road%20Accident%20Data%202.0%20–%20India%202020.pdf)

---

## 📊 Objective
- Examine accident patterns by **cause type** and **city type**.  
- Understand **fatality rate**, **injury rate**, and **severity score** trends.  
- Identify high-risk hotspots and subcategories (e.g., overspeeding, weather conditions).  
- Provide **policy recommendations** for road safety improvement.

---

## 📂 Dataset & Sources
Data was sourced from:
- [data.gov.in – Road Accidents in India 2020](https://www.data.gov.in/catalog/road-accidents-india-2020)
- [Kaggle Dataset – Road Accident Data 2020 India](https://www.kaggle.com/datasets/rachit239/road-accident-data-2020-india)

---

## 🔄 Data Cleaning & Transformation (ETL)
Performed using **Excel** and **Power Query**:
- Pivoted and normalised outcome columns.
- Profiled rows (Valid Data, Data Error, No Impact, Empty).
- Categorised **city type**: Industrial, Metro, Tier 2, Tourist.
- Categorised **cause type**: Environmental, Infrastructure, Behavioural.
- Created calculated KPIs in Tableau:
  - **Fatality Rate** = (Persons Killed ÷ Total Accidents) × 100  
  - **Injury Rate** = (Total Injured ÷ Total Accidents) × 100  
  - **Severity Score (Raw)** = (1×Minor) + (3×Grievous) + (5×Deaths)  
  - **Severity Rate** = Severity Score ÷ Total Accidents × 100

---

## 📌 Key Insights
- **Behavioural causes** contribute ~50% of all accidents.
- **Tourist cities** have the highest injury rates (~94–95%).
- **Overspeeding** and **Sunny/Clear weather** are top subcategories for accidents.
- **Severity rates** exceed 100% for all cause groups, meaning multiple injuries/fatalities per accident.
- High-severity hotspots include **Delhi, Bengaluru, and Chennai**.

---

## 🛠 Skills Demonstrated
- **Data Cleaning & Transformation** – Excel, Power Query  
- **Data Analysis** – Calculated KPIs, grouping, aggregation  
- **Visualisation** – Tableau dashboards (multi-page, navigation-enabled)  
- **Storytelling** – Data narrative aligned with policy-making  
- **Publishing** – Tableau Public, GitHub portfolio integration  

---

## 📷 Dashboard Overview

### **Navigation Page**
![Navigation Page](Home%20(Navigation).png)

### **KPIs & Accident Patterns**
![KPIs Dashboard](Dashboard_%20KPIs.png)

### **National Accident Patterns by Cause and Severity**
![National Patterns](Dashboard_%20National%20Accident%20Patterns%20by%20Cause%20and%20Severity.png)

### **National Accident Patterns (Part 2)**
![National Patterns Part 2](Dashboard_%20National%20Accident%20Patterns%20by%20Cause%20and%20Severity%20(2).png)

### **City-Level Accident Patterns & Risk Hotspots**
![City-Level Patterns](City-Level%20Accident%20Patterns%20&%20Risk%20Hotspots.png)

---

## 📝 Policy Recommendations
1. **Enforcement** – Heavy fines or cumulative penalties for overspeeding.
2. **Public Awareness** – Targeted road safety campaigns in tourist-heavy regions.
3. **Infrastructure** – Upgrade junctions and traffic control in high-risk cities.

---

## 📌 How to View
1. **Clone this repo**:
   ```bash
   git clone https://github.com/Dharana-Singh/Regulatory-Affairs-of-Road-Accident-Data-2020-India.git
