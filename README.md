# Road-accident-dashboard
# 🚦 Road Accident Analysis Dashboard | Power BI

> Transforming raw accident data into actionable insights for safer roads and better decision-making.

---

## 📖 Project Overview

The **Road Accident Analysis Dashboard** is an interactive Power BI project developed to analyze road accident data and uncover meaningful patterns related to casualties, accident severity, vehicle involvement, road conditions, and geographical locations.

This dashboard helps stakeholders identify accident-prone areas, monitor safety trends, and make data-driven decisions to improve road safety.

---

## 🎯 Business Problem

Road accidents result in significant loss of life, injuries, and economic costs every year. Understanding when, where, and why accidents occur is essential for developing effective prevention strategies.

This dashboard provides a centralized platform for monitoring accident statistics and identifying critical risk factors.

---

## 🎯 Key Objectives

✅ Analyze total accidents and casualties

✅ Compare Current Year (CY) vs Previous Year (PY) performance

✅ Monitor Fatal, Serious, and Slight casualties

✅ Identify accident trends by month

✅ Analyze casualties by vehicle type

✅ Study road type and road surface impacts

✅ Compare Urban vs Rural accident distribution

✅ Visualize accident hotspots using geographical maps

---

# 📊 Dashboard Snapshot

### Main Dashboard Features

📌 Total Casualties

📌 Total Accidents

📌 Fatal Casualties

📌 Serious Casualties

📌 Slight Casualties

📌 Monthly Casualty Trends

📌 Vehicle Type Analysis

📌 Road Type Analysis

📌 Urban vs Rural Comparison

📌 Day vs Night Accident Analysis

📌 Geographic Accident Mapping

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning |
| DAX | Measures & Calculations |
| Excel/CSV | Data Source |
| Bing Maps | Geographic Visualization |

---

## 📂 Dataset Features

The dataset contains information about:

- Accident Date
- Vehicle Type
- Casualty Count
- Accident Severity
- Road Type
- Road Surface Condition
- Weather Conditions
- Light Conditions
- Urban/Rural Area
- Accident Location

---

# 📈 Dashboard Insights

### 🚗 Vehicle Type Analysis

The dashboard identifies which vehicle categories contribute most to casualties.

Vehicle Categories:

- Car
- Bike
- Bus
- Van
- Agricultural Vehicle
- Other Vehicles

---

### 📅 Monthly Trend Analysis

Track accident and casualty trends throughout the year.

Benefits:

✔ Identify seasonal accident patterns

✔ Compare CY vs PY performance

✔ Detect sudden spikes in accidents

---

### 🛣️ Road Type Analysis

Analyze casualties based on:

- Single Carriageway
- Dual Carriageway
- Roundabout
- One-Way Street
- Slip Road

---

### 🌆 Urban vs Rural Analysis

Compare accident occurrences between:

- Urban Areas
- Rural Areas

This helps identify where road safety measures should be prioritized.

---

### 🌙 Light Condition Analysis

Understand how visibility affects accident frequency.

Categories:

- Daylight
- Darkness

---

### 🗺️ Geographic Analysis

Interactive map visualizations help identify:

- Accident Hotspots
- High Casualty Regions
- Regional Safety Trends

---

## ⚙️ Data Preparation Process

### Data Cleaning

✔ Removed duplicate records

✔ Handled missing values

✔ Corrected inconsistent data

✔ Standardized formats

---

### Data Modeling

✔ Created relationships between tables

✔ Built Calendar Table

✔ Applied Star Schema Model

✔ Optimized model performance

---

## 📐 DAX Measures Used

### Current Year Casualties

```DAX
CY Casualties =
TOTALYTD(
SUM(Data[Number_of_Casualties]),
'Calendar'[Date]
)
