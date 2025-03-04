![](https://github.com/oluwagbemiga01/Electricity-Consumption/blob/main/Image/bulb.webp)

# Electricity Consumption Analysis 💡
Date: 27th of February, 2025

**Tools Used**:
- Power BI
- DAX 
- Power Query

---
1. ## Project Overview
   - This project aims to **analyze patterns in electricity consumption** over time and explore the relationships between power usage and other temporal factors.
   - The dataset contains the following features:
        - Real Consumption
        - Predicted Consumption
        - Time
 
   - The key objectives include:
     
          1. Identifying peak consumption hours 🕒  
          2. Analyzing trends in energy usage 📈
          3. Providing data driven recommendations for energy optimization 🧰

---
2. ## Dataset Information
   - **Source**: This [dataset](https://www.kaggle.com/datasets/qubdidata/electric-power-consumption?select=Power+Consumption+Data.csv) contains live electric power consumption data from Gerogia, spanning the years 2020 to 2024.
   - **Columns**:
         - Date & Time (Timestamp of power usage)
         - Consumption (MW) (Energy used at each time interval)
         - Day of the week (Derived from the Time column) 

  ---

  3. ## Data Cleaning & Preparation
      - I checked for **missing values** and also formatted the dataset properly.
      - Time intelligence analysis was also implemented to effectively work with my date & time.
      - I also extracted additional time-related features (Hour, Day, Month, AM/PM format).
    
  ---
  4. ## Key Metrics & Dax Measures
       - 📌 **Total Electricity Consumption**

     ![](https://github.com/oluwagbemiga01/Electricity-Consumption/blob/main/Image/total%20consumption.png)
     
     - 🔝 **Peak Consumption Hour**
     
![](https://github.com/oluwagbemiga01/Electricity-Consumption/blob/main/Image/peak%20consumption%20hour.png)

---

5. ## Key Insights & Findings

  **Peak Consumption Analysis**
  - The highest electricity consumption occurs at **7PM**, this is indicating there is increase in usage in the evening.
  - On **Mondays**, peak consumption occurs at **5AM**, this might be due to the fact that businesses, industries, and households are starting the week afresh with high energy. 
