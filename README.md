
---

# 🚦 US Traffic Accident Analysis

## 📌 Project Overview

This project analyzes large-scale traffic accident data to identify patterns related to:

* ⏰ Time of day
* 📅 Day of week
* 🌤 Weather conditions
* 🛣 Road features
* 📍 Geographic hotspots
* 🚑 Accident severity

The goal is to uncover trends and contributing factors that influence accident frequency and severity.

---

## 📊 Dataset

* **Dataset:** US Accidents Dataset
* **Source:** Kaggle
* **Size:** ~7.7 million records
* **Features:** 46 original columns

The dataset includes accident time, location coordinates, weather conditions, road characteristics, and severity levels.

---

## 🛠 Project Workflow

### 1️⃣ Data Understanding

* Inspected dataset structure
* Selected relevant columns related to time, weather, location, and road conditions
* Identified missing values and duplicates

---

### 2️⃣ Data Cleaning & Preprocessing

* Removed ~387k duplicate records
* Handled missing weather values using median imputation
* Filled precipitation nulls with 0
* Removed invalid datetime records (~700k rows)
* Converted time to datetime format
* Created new time-based features:

  * Hour
  * Day
  * Month
  * Day_of_Week

---

### 3️⃣ Exploratory Data Analysis (EDA)

Analyzed accident patterns based on:

* Hourly trends
* Weekly distribution
* Seasonal variation
* Severity levels
* Weather conditions
* Road features
* State-level accident frequency

---

## 🔍 Key Insights

### ⏰ Time Patterns

* Accidents peak during **6–9 AM** and **3–6 PM** (rush hours).
* Accidents decline at night.
* However, **average severity increases late at night**.

---

### 📅 Weekly Trends

* Weekdays show significantly higher accident frequency.
* Friday has the highest number of accidents.
* Monday has the lowest among weekdays.
* Weekends have noticeably fewer accidents.

---

### ❄ Seasonal Trends

* Accident frequency spikes during **October–February (Winter)**.
* Accidents decline in summer months.

---

### 🚑 Severity Distribution

* Severity 2 is the most common.
* Followed by Severity 3.
* Severity 4 and 1 occur less frequently.
* Most accidents are moderate in impact.

---

### 🌦 Weather Impact

* Most accidents occur during:

  * Fair
  * Mostly Cloudy
  * Clear
  * Cloudy
  * Partially Cloudy

* Low visibility is strongly associated with accidents.

* Severe accidents are more common during:

  * Overcast
  * Scattered Clouds
  * Clear conditions

---

### 🛣 Road Feature Observations

Majority of accidents:

* Do not occur near traffic signals
* Do not occur near junctions
* Do not occur near crossings
* Do not occur near stop signs
* Do not occur near railway crossings

This suggests accidents frequently happen on open roads and highways.

---

### 📍 Geographic Hotspots

Top 3 states with highest accident counts:

* California (CA)
* Florida (FL)
* Texas (TX)

---

## 📈 Visualizations Included

* Accidents by Hour
* Accidents by Day of Week
* Monthly Trends
* Severity Distribution
* Weather Condition Analysis
* Road Feature Impact
* Geographic Hotspot Mapping (Sampled Visualization)

---

## 🎯 Conclusions

* Rush hours significantly influence accident frequency.
* Winter months increase accident risk.
* Low visibility conditions contribute to accidents.
* Nighttime accidents tend to be more severe.
* High-population states show higher accident concentration.

---

## 💡 Recommendations

* Improve traffic management during rush hours.
* Increase winter road safety awareness.
* Enhance lighting and visibility measures.
* Strengthen late-night safety enforcement.
* Improve highway monitoring systems.

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Folium (for mapping)
* Kaggle Notebook Environment

---

## 📁 Project Structure

```
├── notebook
        ├── US Accidents.ipynb
└── README.md
```

---

## 📌 Final Note

This project demonstrates the ability to:

* Handle large-scale datasets (7M+ records)
* Perform structured data cleaning
* Engineer meaningful features
* Extract actionable insights
* Present findings through visualization

---
