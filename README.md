# 🏨 AtliQ Grand Hospitality Revenue Analytics

📊 **Data-Driven Insights for Strategic Hotel Revenue Optimization**

---

## 📌 Project Overview

AtliQ Grand, a luxury hotel chain in India, faced revenue dips and high cancellations across its properties. This project builds an interactive Power BI dashboard to uncover insights into booking trends, room performance, cancellation impact, and strategic revenue metrics — designed to support better pricing, marketing, and occupancy decisions.

🔗 **Live Power BI Dashboard**: [View Report]()

---

## 💡 Key Business Insights

- **Mumbai leads revenue**: ₹669M total  
- **AtliQ Exotica = highest revenue & booking share**  
- **Week 24 was the peak revenue period**  
- **High cancellation impact**: ₹298M lost due to cancellations  
- **Elite rooms = high demand but high cancellation %**  
- **OTA platforms (e.g., MakeMyTrip, LogTrip)** are strong revenue drivers  

---

## 🧠 Metrics & Measures

Over **20 custom DAX measures** including:

- ADR (Average Daily Rate)  
- RevPAR (Revenue Per Available Room)  
- Occupancy %  
- Cancellation Rate  
- Revenue Lost from Cancellations  
- Booking Share by Platform  
- Week-over-Week Revenue Trends  

---

## 📊 Dashboard Previews

### 🏠 Home View

Overview of key KPIs across all hotel properties, weekly revenue patterns, and overall booking trends.  
![Home Page]()

### 🏨 Property Performance

Deep dive into city-wise and hotel-wise performance with RevPAR, Occupancy %, and Cancellation Trends.  
![Property View]()

### 📅 Weekly Revenue Trends

Compare week-wise spikes and dips to identify high-performance windows and cancellation risks.  
![Weekly Trends]()

-----------

## 📊 Dashboard Previews

### 🧭 Overview View

Quick snapshot of business health across all hotel properties:

- **Top KPIs** at a glance: Revenue, RevPAR, DSRN, Occupancy %, ADR, and Realization %
- **Category revenue breakdown**: Business vs Luxury segments
- **Weekly key metric trends** (RevPAR, ADR, Occupancy %) to spot seasonal performance changes
- **Realization % vs ADR by platform** – see which OTA is bringing in both volume and profitability
- **Property leaderboard** with detailed KPIs: Revenue, RevPAR, Occupancy %, ADR, Booking Nights, Ratings, and Cancellation %

This page gives leadership the 360° pulse of hotel performance across all dimensions.

---

### 🏢 Executive View

Designed for deep-dive exploration and insights:

- **Decomposition Tree** for hierarchical revenue breakdown by City → Property → Room Class → Category
- **Treemap of bookings by platform** – visually highlights top-performing OTAs like MakeMyTrip and LogTrip
- **Revenue by City** – compares property hubs like Mumbai, Bangalore, Delhi, Hyderabad
- **Occupancy % by day type** – contrast between weekday vs weekend traffic
- **Revenue Trend by Month** – track monthly growth and revenue curve



---

## 🧱 Data Model & Structure

### 🔹 Dimension Tables

| Table         | Key Fields                        |
|---------------|------------------------------------|
| `dim_date`    | date, week, month, day_type       |
| `dim_hotels`  | property_id, city, property_name  |
| `dim_rooms`   | room_id, room_class               |
| `dim_platforms` | platform_id, platform_name      |

### 🔹 Fact Tables

| Table               | Description                                        |
|---------------------|----------------------------------------------------|
| `fact_bookings`     | Booking details (dates, guests, revenue, room info) |
| `fact_aggregated`   | Daily room capacity and booking success rates       |

📌 Snowflake schema implemented for clean filtering and scalability.  
![Data Model]()

---

## 🔍 Business Recommendations

- Refine cancellation policies — especially for elite rooms  
- Target OTA partnerships — maximize MakeMyTrip & LogTrip  
- Revenue drop in last 4 days — plan retention campaigns  
- Push high-occupancy properties with better pricing strategies  

---

## 🛠️ Tech Stack

| Area             | Tools / Concepts                    |
|------------------|-------------------------------------|
| BI Tool          | Power BI (Desktop + Service)        |
| Modeling         | DAX, Power Query                    |
| Optimization     | DAX Studio, Bravo for BI            |
| Data Sources     | Excel, MySQL                        |
| UX Features      | Bookmarks, Navigation Buttons, Tooltips |

---


## 🎓 What I Learned

- 🏨 **Domain Knowledge** – Gained solid understanding of the **hospitality industry** — from revenue KPIs to how booking behavior impacts business strategy. This was a great opportunity to combine data analysis with real-world business context.

- 💡 **Advanced DAX Skills** – Built dynamic calculations for YoY, WoW trends, and Realization % to uncover meaningful performance shifts.  

- 🔍 **Smart Visuals** – Used **Decomposition Tree** for drill-down analysis, **Sparkline by OKVIZ** to show trendlines, **Smart Filter by OKVIZ**, and an **Advanced Toggle Switch** by TME AG to add interactivity and control.  

- 🎨 **UI/UX Design** – Designed both **Dark and Light Themes** to create a visually pleasing and smooth experience for users, no matter their preference.  


---

## 📣 Contact

📧 anandcinenkanolu@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/Anand-Cinenkanolu/)  
🗂️ [Portfolio](https://codebasics.io/portfolio/Anand-Cinenkanolu)

---

## 📁 Folder Structure

