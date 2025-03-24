# Phase-1-Project

# Aviation Safety Analysis  

## Overview  
As our company expands into aviation, this project analyzes historical accident data to identify **low-risk aircraft** for commercial and private operations. By understanding accident trends and risk factors, we can make data-driven decisions when selecting aircraft for our fleet.  

## Business Problem  
Aircraft accidents pose significant financial and operational risks. The goal of this analysis is to:  
- Identify aircraft models with the lowest accident rates.  
- Analyze key accident causes and patterns.  
- Provide data-driven recommendations for safer aircraft choices. 
## Data  
The dataset consists of aviation accident records, including details such as:  
- **Aircraft Information**: Make, Model, Engine Type, Number of Engines.  
- **Flight & Accident Details**: Event Date, Location, Purpose of Flight, Weather Conditions.  
- **Accident Outcomes**: Injury Severity, Aircraft Damage, Fatalities, Serious Injuries. 

---
## Methods

## Data Cleaning Process

## 1. Data Preprocessing  
To ensure high-quality data for analysis, the following cleaning steps were performed:  

### Dropped Columns  
- **Removed 'Schedule' and 'Air.carrier'** due to excessive missing values (>80%).  
- **Dropped 'FAR.Description' and 'Aircraft.Category'** since over 60% of values were missing, making them unreliable for analysis.  

### Handling Missing Values  

#### Categorical Columns  
Missing values in categorical columns were replaced with `"Unknown"` to retain all data points:  
- `Broad.phase.of.flight`, `Publication.Date`, `Engine.Type`, `Report.Status`, `Purpose.of.flight`, `Weather.Condition`, `Aircraft.damage`, `Injury.Severity`, `Airport.Code`, `Airport.Name`, `Location`, `Country`, `Make`, `Model`, `Registration.Number`.  

For `Amateur.Built`, missing values were replaced with `"No"` since the majority of aircraft are not amateur-built.  

#### Numerical Columns  
Missing numerical values were filled with `0`, assuming no injuries occurred when data was unavailable:  
- `Total.Fatal.Injuries`, `Total.Serious.Injuries`, `Total.Minor.Injuries`, `Total.Uninjured`.  

For `Number.of.Engines`:  
- If **numeric**, missing values were filled with the **median**.  
- If **non-numeric**, they were replaced with `"Unknown"`.  

### Final Check  
After cleaning, all missing values were successfully handled, ensuring a complete dataset for analysis.  

---
