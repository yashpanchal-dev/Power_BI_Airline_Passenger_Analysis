# Airline Operations & Passenger Analysis Report (Power BI)

This repository contains a **Power BI dashboard project** that analyzes airline operations and passenger movement between airports.  
The report provides interactive insights into passenger traffic, flight volume, travel distances, and route performance across origins and destinations.

---

## 📌 Project Overview

The **Airline Operations & Passenger Analysis Report** is designed to help users:
- monitor **total passengers**, **total flights**, and **total travel distance**
- explore airport-to-airport travel patterns
- identify high-performing **origin/destination airports**
- analyze flight trends over time using interactive filters

---

## 🎯 What This Dashboard Does

The dashboard answers key questions such as:
- How many total passengers traveled during the selected period?
- What is the total number of flights operated?
- What is the total travel distance covered?
- Which origin airports handle the highest passenger counts?
- Which destination airports receive the most passengers?
- How do passengers and flights change across time (year/quarter/month/day)?
- What are the top passenger routes and airport locations?

---

## 📊 Key KPIs Included

The report includes KPI cards for:
- **Total Passengers** (`Sum(Airports2.Passengers)`)
- **Total Distance** (`Sum(Airports2.Distance)`)
- **Number of Flights** (`Sum(Airports2.Flights)`)

It also highlights:
- **Origin airport**
- **Destination airport**

---

## 🗺️ Visuals in the Report

### ✅ Main Dashboard Components
- **Map Visualization**
  - Shows airport locations using latitude/longitude
  - Bubble size based on **Passenger Count**
  - Interactive tooltip for **Origin Airport**

- **Passenger Analysis Charts**
  - Passenger count by **Origin Airport**
  - Passenger count by **Destination Airport**

- **Flights Trend**
  - Line chart showing **Flights by Quarter**

- **Passenger Trend**
  - Area chart showing **Passengers over time**
  - Supports Date drill-down: **Year → Quarter → Month → Day**

---

## 🎛 Filters / Slicers Available

Users can interact with slicers to filter the report by:
- **Fly Date**
- **Origin City**
- **Destination City**

---

## 🛠 Built With

- **Microsoft Power BI Desktop**
- **Power Query** (Data cleaning & transformation)
- **DAX** (Measures & aggregations)
- Interactive visuals: maps, charts, KPIs, slicers

---

## ✅ Conclusion

The **Airline Operations & Passenger Analysis Report** demonstrates how raw airline/airport data can be transformed into a clear and interactive decision-making dashboard using **Power BI**.

Through KPIs, route-based analysis, time trends, and geographic visualization, the report enables users to:
- monitor overall airline activity using key metrics (**Passengers, Flights, Distance**)
- evaluate busiest **origin and destination airports**
- analyze operational trends across time (Year → Quarter → Month → Day)
- understand travel patterns that support smarter planning and performance review

This project highlights practical skills in **data modeling, DAX measures, Power Query transformation, and dashboard storytelling**, making it a strong example of data analytics using Power BI.

