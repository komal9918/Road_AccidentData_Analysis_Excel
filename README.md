# 🚗 Road Accident Data Analysis (Excel)

## 📘 Project Information
This project provides an in-depth analysis of road accident data using **Microsoft Excel**.  
The goal is to uncover trends and insights that help improve **road safety**, identify **high-risk locations**, and understand **factors influencing accidents** such as weather, road type, and time of day.

---

## 🎯 Business Problem
Road safety authorities, transport planners, and traffic management agencies need to make data-driven decisions to reduce accident frequency and severity.  
Key questions addressed in this project:
- When and where do most accidents occur?
- What are the common causes and conditions leading to severe accidents?
- Which vehicle types are most frequently involved in accidents?
- How can the identified trends support better safety measures?

This analysis provides actionable insights through charts, dashboards, and summaries to assist in **strategic planning and safety initiatives**.

---

## 🗂️ Dataset
**Dataset Source:** The data used is stored in this repository (or can be replaced with similar road accident data).  

**Sample Columns:**
Accident index, Accident Date,Month,Year,Day Of Week,Junction Control,Junction Detail, Accident Severity,latitude,light Condition, Local Authority(District),Carriageway_Hazards, Longitude, Number_of_Casualties, Number_of_Vehicles, Police_Force, Road_Surface_Conditions, Road_Type, Speed_limit, Time, Urban_or_Rural_Area, Weather_Conditions, Vehicle_Type
 
## 🛠️ Technologies Used
- **Microsoft Excel**
  - Power Query (for data cleaning & transformation)
  - Power Pivot (for modeling)
  - Pivot Tables & Charts (for analysis & visualization)
  - Slicers and Filters (for interactivity)
 
## 🔁 Workflow

### Step 1: Data Cleaning
- Import dataset into Power Query  
- Remove duplicates, fix missing values, and standardize formats  
- Create new columns like `Month`, `DayOfWeek`, and `Hour` for time-based analysis  

### Step 2: Data Transformation
- Categorize accident severity and weather conditions  
- Group data by location, vehicle type, and time  

### Step 3: Data Analysis
- Build PivotTables to summarize:
  - Accidents by year, month, or day  
  - Accidents by road type and vehicle type  
  - Accidents by weather and lighting conditions  

### Step 4: Visualization
- Create Excel charts for:
  - Monthly trend of accidents  
  - Severity-wise distribution  
  - Top 10 accident locations  
  - Time-of-day vs accident frequency heatmap  

### Step 5: Dashboard Creation
- Combine visualizations into an interactive dashboard  
- Add filters for **Year**, **Location**, **Vehicle Type**, and **Severity**

  ## 📊 Results / Insights
- Identified **peak accident hours** (commonly 5 PM – 8 PM).  
- **Two-wheelers and cars** account for the majority of total accidents.  
- **Rainy weather** and **low-light conditions** show a higher percentage of severe accidents.  
- Certain **road segments** repeatedly appear as hotspots.  

These findings can help local authorities prioritize road safety actions such as **speed control**, **road lighting**, and **public awareness programs**.

## ▶️ How to Run the Project
**Clone or Download the Repository**
   ```bash
   git clone [https://github.com/komal9918/Road_AccidentData_Analysis_Excel.git](https://github.com/komal9918/Road_AccidentData_Analysis_Excel)
