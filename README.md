# 🧠 Panic Attacks Data Analysis using Snowflake & Power BI

## 📌 Project Overview
This project focuses on analyzing **panic attack patient data** to uncover patterns related to **symptoms, sleep habits, panic duration, lifestyle factors, and demographics**.  
The goal is to convert raw healthcare data into **actionable insights** using **Snowflake SQL**, **Power BI**, **Power Query**, and **DAX**.

The analysis helps in understanding:
- Common panic attack symptoms
- Impact of sleep and alcohol consumption
- Panic attack duration patterns
- Demographic trends (age & gender)
  

---

## 🔗 Live Power BI Dashboard
👉 **View Interactive Dashboard**  
https://app.powerbi.com/groups/me/reports/680e63c2-5487-4d58-9cdc-1bc48c928dc8/91d04770342874bc40ee?experience=power-bi

---

## 📊 Dataset Information
- **Domain:** Healthcare Analytics  
- **Data Source:** Snowflake (Cloud Data Warehouse)  
- **Data Type:** Patient-level panic attack data  
- **Usage:** Educational & analytical purposes  

---

## 🛠 Tools & Technologies Used
- **Power BI** – Dashboard & visualization  
- **Snowflake** – Cloud data warehouse  
- **SQL** – Data querying & validation  
- **Power Query Editor** – Data cleaning & transformation  
- **DAX** – Calculated columns & measures  

---
### Age Group Classification
```DAX
Age Group = 
IF(
    'PANIC_ATTACK_DATA'[AGE] <= 17, "Child",
    IF(
        'PANIC_ATTACK_DATA'[AGE] <= 24, "Adolescent",
        IF(
            'PANIC_ATTACK_DATA'[AGE] <= 64, "Adult",
            "Senior"
        )
    )
)
  ---
### 📈 Key Analysis Performed
- Analyzed panic attack symptom patterns including chest pain, dizziness, sweating, and trembling  
- Studied panic attack duration trends across different patient groups  
- Evaluated the impact of sleep hours on panic attack frequency  
- Analyzed alcohol consumption (drinks per week) in relation to panic attack severity  
- Performed age group-wise segmentation using DAX  
- Identified common trigger reasons such as caffeine intake, PTSD, and phobia  
- Correlated medical history factors (anxiety, depression) with panic attack occurrence  
- Built KPI-driven visuals and interactive slicers for exploratory analysis  

---

## 🎯 Business & Analytical Insights
- Patients with lower sleep duration tend to experience higher panic attack frequency  
- Certain symptoms like chest pain and sweating are more prevalent among patients  
- Adult age group shows the highest number of panic attack cases  
- Lifestyle factors such as alcohol intake influence panic attack duration  
- Interactive dashboards enable targeted demographic and symptom-based insights  

---

## 🚀 Key Learnings
- Gained hands-on experience in healthcare data analytics  
- Applied SQL and Snowflake concepts for structured data analysis  
- Used DAX for demographic segmentation and business logic  
- Designed interactive Power BI dashboards with meaningful KPIs  


---

## 👤 Author
**Pallav Garg**  
Aspiring Data Analyst

