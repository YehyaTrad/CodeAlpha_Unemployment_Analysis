# Unemployment Analysis (1991–2021) – CodeAlpha Internship Task 2

## Overview
This project is part of the **CodeAlpha Data Science Internship (Task 2)**.  
It analyzes global unemployment rates from 1991 to 2021 using Python, Pandas, and Seaborn, with a focus on Lebanon. The analysis highlights long-term trends and the impact of COVID-19 on unemployment rates.

## Dataset
- **Source:** `unemployment.csv`  
- **Description:** Country-wise unemployment rates over the years 1991–2021.  
- **Columns:**
  - `Country Name` – Name of the country  
  - `Country Code` – ISO country code  
  - `1991` to `2021` – Unemployment rate per year  
- **Preprocessing:** The dataset was reshaped from **wide to long format** using Pandas `melt()` for effective time-series analysis.

## Tools & Libraries
- **Programming Language:** Python 3.x  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  

## Steps Performed
1. **Data Loading & Inspection**  
   - Loaded `unemployment.csv` into a Pandas DataFrame.  
   - Checked for missing values and data types.  

2. **Data Transformation**  
   - Reshaped data from wide to long format (`Year` and `Unemployment_Rate` columns).  
   - Converted `Year` column to numeric.  

3. **Exploratory Data Analysis (EDA)**  
   - Plotted unemployment trends for Lebanon (1991–2021).  
   - Analyzed the impact of COVID-19 (2019–2021).  
   - Identified patterns and fluctuations in unemployment rates.  

4. **Visualization & Results**  
   - Line plots to show long-term trends.  
   - Highlighted unemployment changes during the COVID-19 period.  
   - Plots saved to the `results/` folder.  

## Key Insights
- Lebanon’s unemployment rate shows variability over the last three decades.  
- Significant increase observed during 2020–2021, reflecting the COVID-19 economic impact.  
- Visualizations provide clear insights into trends, useful for economic or social policy analysis.  

## Folder Structure
CodeAlpha_Unemployment_Analysis/
│
├── data/
│ └── unemployment.csv
│
├── notebooks/
│ └── unemployment_analysis.ipynb
│
├── results/
│ ├── lebanon_unemployment_trend.png
│ └── lebanon_covid_impact.png
│
├── README.md
└── requirements.txt
