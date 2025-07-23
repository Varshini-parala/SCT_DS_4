# 🚦 Traffic Accident Analysis | SkillCraft Technology Internship - Task 04

## 📌 Project Overview

This project is part of my internship with **SkillCraft Technology**, where I performed an in-depth analysis of traffic accident data in the United States. The goal was to explore patterns in road accidents and uncover insights based on:

- **Time of day**
- **Weather conditions**
- **Location (hotspots)**
- **Day of the week**
- **Road and environmental factors**

The dataset used was `US_Accidents_March23.csv`, which contains real-world accident reports.

---

## 🗃️ Dataset Information

- **Source:** Kaggle (US Accidents)
- **File Used:** `US_Accidents_March23.csv`
- **Size:** ~7 million rows
- **Format:** CSV

Each row represents a single accident case with data like:
- Timestamp
- Weather condition
- Road type
- City, State
- Latitude/Longitude
- Severity level

---

## 🧪 Tools & Technologies Used

| Tool      | Description                     |
|-----------|---------------------------------|
| Python    | Core data analysis              |
| Pandas    | Data loading & manipulation     |
| Seaborn   | Data visualization              |
| Matplotlib| Charts and graphs               |
| Jupyter Notebook | Interactive environment |

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Accidents by **Hour** of the day
- Accidents by **Day of the Week**
- Accidents by **Month**
- Top **Weather Conditions**
- Accident **Hotspots (Start_Lat & Start_Lng)**
- Most affected **States**
- Time-based risk: **Night vs Day**, **Weekday vs Weekend**

### 🔍 Sample Visuals

- Line Chart: Accidents per Hour
- Bar Chart: Top 10 Weather Conditions
- Scatter Plot: Accident Locations
- Pie/Bar Charts: State-wise and Day-wise breakdown

---

## 📈 Key Insights

1. **Peak Hours:** Most accidents occur during morning and evening rush hours (7–9 AM & 4–6 PM).
2. **Weather Factor:** Rain and fog contribute to increased accident counts.
3. **Hotspot States:** California, Florida, and Texas lead in accident counts.
4. **Weekend Effect:** Slightly fewer accidents happen on weekends.
5. **Night Risk:** Accidents are relatively higher during low-light conditions.

---

## 🧼 Data Cleaning Steps

- Removed duplicates
- Converted `Start_Time` to datetime
- Extracted `Hour`, `Day`, and `Month`
- Dropped rows with null values in key fields like `Weather_Condition`
- Sampled data for plotting to improve performance

---
