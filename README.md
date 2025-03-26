# Phase-1-Project

# Aviation Risk Analysis for Business Expansion

**Author:** Harriet Ngomo  

## Overview

This project analyzes aviation accident data from **1962 to 2023** to identify the safest aircraft models for commercial and private operations. By evaluating historical accident trends, aircraft safety records, and risk factors, this analysis provides actionable insights to minimize financial and operational risks. 

## Business Problem

Entering the aviation industry presents challenges, especially for companies with limited experience in assessing aircraft risks. Investing in aircraft with poor safety records can lead to financial losses and operational hazards. This project aims to identify low-risk aircraft models using a data-driven approach, ensuring informed investment decisions.

## Data

The dataset is sourced from the **National Transportation Safety Board (NTSB)** and contains **31 columns** detailing aviation accidents. Key features include:

- **Aircraft Information**: Make, model, number of engines, and engine type.
- **Accident Details**: Date, location, weather conditions, and severity.
- **Operational Factors**: Purpose of flight, regulatory category, and air carrier details.
- **Injury & Damage Information**: Number of fatalities, serious injuries, and uninjured passengers.
- **Report Information**: Investigation type, accident number, and report status.

## Methods

The analysis follows a structured approach:

1. **Data Cleaning**:
   - Handling missing values by dropping columns with excessive missing data (>60%) and filling categorical/numeric columns appropriately.
   - Standardizing data types for accurate analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Identifying trends in aviation accidents over time.
   - Assessing accident frequency across different aircraft models.
   - Examining risk factors such as weather conditions and flight phases.

3. **Data Visualization**:
   - **Time Series Analysis**: Trends in aviation accidents over the years.
   - **Bar Charts**: Aircraft models with the highest and lowest accident rates.
   - **Risk Factor Analysis**: Identifying the most accident-prone flight phases.

## Results

### **1. Aviation Accidents Trend (1982-2022)**
![image alt]([Aviatian Accidents trend.png](https://github.com/Harriet-ngomo/Phase-1-Project/blob/8d754ac98a24a4949417ba5c96c22887c0b38252/Aviatian%20Accidents%20trend.png))
- Aviation accidents have **declined over the years**, reflecting improvements in aircraft technology, safety regulations, and training.
- A sharp decline in **2020** aligns with the COVID-19 pandemic and reduced flight activity.
- Business takeaway: Investing in **modern aircraft models** is a safer and more strategic decision.

### **2. Aircraft Safety Records**
- **High-risk aircraft**: Cessna, Piper, and Beech models have the highest accident rates.
- **Low-risk aircraft**: Boeing 777-306ER, Waterwings, Inc., and FOGLIO have the fewest reported accidents.
- Business takeaway: Prioritize investment in **aircraft with historically low accident rates**.

### **3. Flight Phase & Risk Factors**
- **Takeoff, Cruise, and Landing** have the highest injury rates.
- **Go-around, Standing, and Taxi** are the safest phases with minimal injuries.
- Business takeaway: Focus on safety improvements in **critical flight phases** to reduce risks.

## Conclusions

Based on the analysis, the following recommendations can enhance decision-making in the aviation industry:

1. **Invest in Low-Risk Aircraft**: Prioritize models with a strong safety record to minimize financial and operational risks.
2. **Enhance Safety During Critical Phases**: Improve pilot training and technology in high-risk phases (Takeoff, Cruise, and Landing) to reduce accident-related injuries.
3. **Monitor Industry Trends**: Stay updated on aviation safety regulations and technological advancements to adapt investment strategies.

