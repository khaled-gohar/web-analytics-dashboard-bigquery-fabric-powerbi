# 🌐 Web Analytics Dashboard – End-to-End Data Project  

📊 **[Live Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiYThiN2E2NDQtMDAyZi00NmE3LTg4YWMtYzBiOGJhYWNjM2Y2IiwidCI6IjIzZGI2ZTA2LTA1YzQtNDg5ZC1iMTM2LWNiYTk0YThlNmYzNiIsImMiOjh9)**

---

## 📖 Project Scenario  

In today’s digital landscape, understanding **website performance and user behavior** is key to driving growth.  

This project demonstrates how **raw web analytics data** can be transformed into **actionable insights** using a **modern data stack**.  

I built a **full end-to-end data pipeline** using **BigQuery, Microsoft Fabric, and Power BI** to deliver a **dynamic dashboard** that tracks:  
- User engagement  
- Traffic sources  
- Device usage  
- Conversions  
- Sales performance  

This project simulates a **real-world scenario** where a company needs a **scalable analytics solution** with:  
✔ Automated **daily incremental data loads**  
✔ Clean & transformed datasets in a **Lakehouse**  
✔ **Business-ready KPIs & dashboards** for decision-making  

---

## 🔗 Live Dashboard  

👉 **[Explore the Interactive Dashboard](https://app.fabric.microsoft.com/view?r=eyJrIjoiYThiN2E2NDQtMDAyZi00NmE3LTg4YWMtYzBiOGJhYWNjM2Y2IiwidCI6IjIzZGI2ZTA2LTA1YzQtNDg5ZC1iMTM2LWNiYTk0YThlNmYzNiIsImMiOjh9)**  


---

## 🛠️ Tech Stack & Tools  

- **Google BigQuery** → Raw data source  
- **Microsoft Fabric** →  
  - Lakehouse for storage  
  - Data Pipeline for ingestion  
  - Dataflow Gen2 for transformation & cleaning  
- **Power BI** → Interactive reporting & storytelling  

---

## 📂 Data Pipeline Architecture  

**1. Source** → Data ingested from **BigQuery**  
**2. Ingestion** → Fabric Data Pipeline loads raw data into the **Lakehouse**  
**3. Transformation** → Fabric Dataflow Gen2 cleans & standardizes data  
**4. Storage** → Final, transformed tables stored in the Lakehouse  
**5. Load Frequency** → Incremental loads scheduled **daily (night)**  
**6. Visualization** → Power BI connected to the Lakehouse for reporting  

---

## 📊 Dashboard Features  

### 🔹 Main Page – Web Analysis  
**KPIs (with % change vs previous period):**  
- Users  
- Page Views  
- Conversion Rate (%)  
- Avg. Session Duration (sec)  
- Avg. Bounce Rate (%)  

**Visuals:**  
📈 Line Chart → KPI over selected time period  
🍩 Donut Chart → KPI by Device Type  
📊 Column Chart → KPI by Traffic Source  
📉 Bar Chart → KPI by Country  

**Filters / Slicers:**  
- Time Period: Last 7, 30, 90, 365 days  
- KPI Selector: Controls all visuals + vs previous period values  

**Drill-through:**  
- From Country Bar Chart → **Country Analysis Page**  

---

### 🔹 Drillthrough Page – Country Analysis  
**KPIs (vs previous period):**  
- Users  
- Page Views  
- Conversion Rate (%)  
- Avg. Session Duration (sec)  
- Avg. Bounce Rate (%)  

**Additional KPIs (vs previous period):**  
- Customers Reached  
- Total Transactions  
- Avg. Product per Order  
- Total Sales Amount  
- Avg. Order Value  

**Visuals:**  
📈 Line Chart → Second KPI set over time  
📊 Bar Chart → KPI vs Product  
🔄 Toggle → Switch between **Visuals** and **Transaction Table**  

---

## 🎯 Business Value  

This dashboard enables teams to:  
✔ Track **user engagement trends**  
✔ Identify **top-performing traffic sources & devices**  
✔ Compare **country-level performance**  
✔ Link **web analytics with sales outcomes**  
✔ Drive **data-driven marketing & operational decisions**  

---

## 🚀 Key Skills Demonstrated  

- **Data Engineering** → Pipelines, incremental loads, transformations  
- **Data Modeling** → Lakehouse-based architecture  
- **Business Intelligence** → KPI design, storytelling dashboards  
- **Tools** → BigQuery, Microsoft Fabric, Power BI  

---



## 👤 About Me  

I’m **Khaled Gohar**, a **Data Analyst** with expertise in:  
- SQL | Power BI | Microsoft Fabric | Data Modeling  

This project reflects how I design and deliver **end-to-end data solutions** that bridge **raw data** to **business insights**.  

🔗 [LinkedIn](https://www.linkedin.com/in/khaled-gohar/) | [GitHub](https://github.com/khaled-gohar)  
---
