# Nigeria Food Price Analysis Dashboard 

## Project Overview
Food prices in Nigeria have been changing quickly. I wanted to see which states are most expensive and which foods are rising the fastest.

### My Workflow:
1. **Data Cleaning (Python):** The raw Kaggle data had messy units. I used **Pandas** to standardize all units to a common metric.
2. **Analysis:** Calculated price volatility and median costs per state.
3. **Visualization (Power BI):** Exported the cleaned data to Power BI to create an interactive dashboard for stakeholders.

## The Solution
The most challenging part was the **unit inconsistency**. I wrote a Python script to:
* Strip strings from unit columns.
* Convert different measurements into a standard numeric scale.
* Handle missing values in the "Market" column.

## The Dashboard
![Nigeria_Food_Prices](Nigeria_Food_Prices.png)

## Key Findings 
* **Price Spike:** Prices stayed flat for years but jumped massively after 2020.
* **Top Spender:** Borno State has the highest median food prices (352.73).
* **Most Volatile:** Milk powder prices change the most frequently compared to other items.

## Tools I Used
* **Data Cleaning:** Python
* **Visualization:** Power BI
