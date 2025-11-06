# 🏨 Hospitality Performance Dashboard (Power BI)

## 📊 Overview

This project presents an **interactive Power BI dashboard** analyzing the performance of a hotel chain operating across multiple cities and categories (Luxury and Business).  
The dashboard provides actionable insights into **revenue trends, occupancy rates, RevPAR, ADR, and realization percentages**, helping management make data-driven decisions to optimize pricing, room utilization, and booking platforms.

---

## 🚀 Key Insights & Features

### 🔹 Revenue Analysis
- **Total Revenue:** $1.69 Billion across all hotels (May–July)
- **Revenue by Category:**  
  - Luxury: 61.6%  
  - Business: 38.4%
- **Revenue by Week Number and Category** visualization for trend monitoring.

### 🔹 Occupancy & ADR Trends
- **Average Occupancy:** 57.8% overall  
- **Average Daily Rate (ADR):** 12.7K  
- **RevPAR (Revenue per Available Room):** 7.34K  
- Comparative weekly trends for **Weekdays vs Weekends** help evaluate operational efficiency.

### 🔹 Realisation & Booking Platforms
- Realisation percentage consistent around **70%**, showing stable customer retention.
- ADR and Realisation% are analyzed by **booking platform** to identify high-value channels (e.g., direct, online aggregators).

### 🔹 Hotel-Level Performance
Each property’s key metrics include:
| Metric | Description |
|--------|-------------|
| **Revenue (M)** | Total hotel revenue in millions |
| **RevPAR (K)** | Revenue per available room |
| **Occupancy (%)** | Average occupancy rate |
| **ADR (K)** | Average daily room rate |
| **Realisation (%)** | Share of realized revenue |
| **Cancellation (%)** | Average booking cancellation rate |
| **Average Rating** | Customer satisfaction indicator |

Example Snapshot:  
> **Atliq Blu Hyderabad** — Revenue: $55M | Occupancy: 65% | ADR: 9K | Realisation: 70% | Avg Rating: 4.25  

---

## 🧱 Data Model & Sources

The analysis is powered by **five structured datasets** forming a star schema:

| Table | Description |
|--------|--------------|
| **dim_date** | Contains date, month, week number, and day type (Weekday/Weekend). |
| **dim_hotels** | Lists properties, categories (Luxury/Business), and cities. |
| **dim_rooms** | Defines room types and classes (Standard, Elite, Premium, Presidential). |
| **fact_aggregated_bookings** | Aggregated daily bookings and capacity per room type. |
| **fact_bookings** | Detailed transactional data including guests, booking status, revenue, and platform. |

**Data Timeline:** May, June, and July (covering multiple week numbers).  
**Metric Calculations:**  
- **RevPAR** = Revenue / Available Rooms  
- **ADR** = Total Revenue / Booked Rooms  
- **Realisation%** = (Revenue Realized / Revenue Generated) × 100  

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data visualization and dashboard creation |
| **Excel** | Data cleaning and preliminary aggregation |
| **DAX** | Custom calculations and performance metrics |
| **Power Query** | Data transformation and model preparation |

---

## 💡 Business Impact

- Identified **top-performing hotels** and **cities** by revenue and occupancy.
- Enabled **targeted marketing** by analyzing **booking platform performance**.
- Supported **pricing optimization** through ADR and RevPAR trend analysis.
- Improved understanding of **customer satisfaction** via ratings and cancellation patterns.

---

## 🗂️ Attachments / Links
> 🔗 [Power BI Dashboard (.pbit)](https://github.com/Yanglesh5139/Hospitality-Analytics/blob/main/hospitality_dashboard.pbit)  
> 🔗 [Dashboard PDF Report](https://github.com/Yanglesh5139/Hospitality-Analytics/blob/main/hospitality_dashboard.pdf)  
> 🖼️ [Dashboard Overview Preview](https://github.com/Yanglesh5139/Hospitality-Analytics/blob/main/Dashboard_pics/Hospitality_Homepage.png)  

---

📫 Contact Information

👤 Yanglesh Jaiswal  
🎓 Management Engineering Student | Data Analyst  
📍 Palermo, Italy  
📧 jaiswalyanglesh11@gmail.com  
📞 +39 3935524408  
### 🌐 Social Links  

<p align="left">
  <a href="https://www.linkedin.com/in/yanglesh-jaiswal/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="40" height="40"/>
  </a>
  <a href="https://github.com/Yanglesh5139/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="40" height="40"/>
  </a>
</p>
