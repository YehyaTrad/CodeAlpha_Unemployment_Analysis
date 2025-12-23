# 📊 Unemployment Analysis (1991–2021)
### 🎓 CodeAlpha Data Science Internship — Task 2

---

## 📌 Overview
This project is part of the **CodeAlpha Data Science Internship**.  
It focuses on analyzing global unemployment rates from **1991 to 2021**, with a detailed case study on **Lebanon**, highlighting long-term trends and the **impact of COVID-19** on unemployment.

---

## 📁 Dataset Information
- **File Name:** `unemployment.csv`
- **Type:** Country-wise unemployment rate dataset
- **Time Period:** 1991 – 2021

### 🧾 Columns Description
| Column Name | Description |
|------------|-------------|
| Country Name | Name of the country |
| Country Code | ISO country code |
| 1991 – 2021 | Unemployment rate (%) per year |

🔄 The dataset was converted from **wide format** to **long format** for efficient analysis using Pandas.

---

## 🛠️ Tools & Technologies
- 🐍 **Python 3**
- 📊 **Pandas**
- 🔢 **NumPy**
- 📈 **Matplotlib**
- 🎨 **Seaborn**
- 📓 **Jupyter Notebook**

---

## 🔍 Project Workflow
### 1️⃣ Data Loading & Inspection
- Loaded dataset using Pandas
- Inspected structure, data types, and missing values

### 2️⃣ Data Preprocessing
- Reshaped dataset using `melt()`
- Converted year columns to numeric format

### 3️⃣ Exploratory Data Analysis (EDA)
- Analyzed unemployment trends for Lebanon
- Compared pre-COVID and post-COVID unemployment levels

### 4️⃣ Visualization
- Line charts for long-term trends
- Focused COVID-19 impact visualization (2019–2021)
- Saved plots for reporting and presentation

---

## 📊 Key Insights
- 📉 Lebanon’s unemployment rate fluctuated significantly over three decades  
- 🦠 A sharp increase was observed during **2020–2021**, reflecting COVID-19’s economic impact  
- 📈 Visual analysis helps identify policy-relevant trends and patterns  

---

## 📁 Folder Structure

```
📁 CodeAlpha_Unemployment_Analysis/
│
├── data/
│   └── unemployment.csv
│
├── notebooks/
│   └── unemployment_analysis.ipynb
│
├── results/
│   ├── lebanon_unemployment_trend.png
│   └── lebanon_covid_impact.png
│
├── README.md
└── requirements.txt
```

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```
git clone https://github.com/YehyaTrad/CodeAlpha_Unemployment_Analysis.git
```
 ###2️⃣ Navigate to Project Directory
```
cd CodeAlpha_Unemployment_Analysis

```
### 3️⃣ Install Dependencies
```
pip install -r requirements.txt
```
### 4️⃣ Run the Notebook
```
jupyter notebook notebooks/unemployment_analysis.ipynb
```

## 👤 Author

**Yehya Trad**  
🎓 Data Science Intern — CodeAlpha
```
## 📜 License
```
This project is created for **educational purposes** as part of the CodeAlpha Internship Program.


