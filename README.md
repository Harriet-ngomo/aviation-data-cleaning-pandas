# Phase-1-Project

# Aviation Risk Analysis for Business Expansion

**Author:** Harriet Ngomo  

## Overview

This project analyzes aviation accident data from **1962 to 2023** to identify the safest aircraft models for commercial and private operations. By evaluating historical accident trends, aircraft safety records, and risk factors, this analysis provides actionable insights to minimize financial and operational risks. 

## Business Problem

Entering the aviation industry presents challenges, especially for companies with limited experience in assessing aircraft risks. Investing in aircraft with poor safety records can lead to financial losses and operational hazards. This project aims to identify low-risk aircraft models using a data-driven approach, ensuring informed investment decisions.

## Data
## Dataset Source
The dataset used for this analysis is from Kaggle. You can access it here:  
[Aviation Accident Database Synopses](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)
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
![image alt](https://github.com/Harriet-ngomo/Phase-1-Project/blob/8d754ac98a24a4949417ba5c96c22887c0b38252/Aviatian%20Accidents%20trend.png)
- Aviation accidents have **declined over the years**, reflecting improvements in aircraft technology, safety regulations, and training.
- A sharp decline in **2020** aligns with the COVID-19 pandemic and reduced flight activity.
- Business takeaway: Investing in **modern aircraft models** is a safer and more strategic decision.

### **2. Aircraft Safety Records**
![image](https://github.com/Harriet-ngomo/Phase-1-Project/blob/33ed9d568e553b2418529376087df43853e39a76/Aircraft%20Models%20with%20the%20Highest%20and%20Lowest%20Accident%20rates.png)
- **High-risk aircraft**: Cessna, Piper, and Beech models have the highest accident rates.
- **Low-risk aircraft**: The safest aircraft:CULP JOHN S,Bibbee,JANTZEN and more have the lowest accident rates, indicating strong safety performance. Businesses should prioritize these models for lower aviation risk.
- Business takeaway: Prioritize investment in **aircraft with historically low accident rates**.

### **3. Flight Phase & Risk Factors**
![image alt](https://github.com/Harriet-ngomo/Phase-1-Project/blob/44218aaacb898506c445f0a4d7a20b3b3fc53e92/Injury%20severity%20by%20Flight%20phase.png)
- **Landing,Cruise and Takeoff** have the highest total injuries, indicating these are the most critical phases for safety.

- **Maneuvering and Approach** also pose significant risks, with a high number of injuries.

- **Climb and Descent** show moderate injury rates.

- **Go-around, Standing, and Taxi** have the lowest injuries, suggesting they are less accident-prone.
- Business takeaway:  Focus on improving safety during Landing,Cruise, Takeoff, Maneuvering, and Approach to reduce accident-related injuries.

- ## Interactive Dashboard  
[View the Tableau Dashboard](https://public.tableau.com/views/Book1_17430285436540/PROJECTDASHBOARD?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


### **Conclusions & Business Recommendations**  
Based on the analysis, the following recommendations can enhance decision-making in the aviation industry:

- **Invest in Low-Risk Aircraft**  
   - Prioritize aircraft with strong safety records (e.g.,CULP JOHN S,Bibbee,JANTZEN ).  
   - Avoid high-risk models with frequent accidents (e.g., Cessna, Piper, and Beech models).  
- **Enhance Safety During Critical Flight Phases**  
   - Improve training and safety measures for **Takeoff, Cruise, and Landing**—the most accident-prone phases.  
   - Focus on **Maneuvering and Approach**, which also contribute to high injury rates.  
- **Monitor Industry Trends & Regulations**  
   - Stay updated on aviation safety standards and technological advancements.  
   - Continuously assess accident data to refine risk management strategies.  

**Takeaway:** Data-driven decision-making can lead to **safer operations, reduced financial risks, and strategic aviation expansion.**  

