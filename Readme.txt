# 🚲 Bike Sharing Demand Analysis

## 📌 Project Overview

This project explores the Bike Sharing Dataset (day.csv) to analyze daily rental demand patterns based on seasonal and environmental factors.

The analysis includes:
- Descriptive statistical analysis
- Data quality assessment
- Data cleaning process
- Demand pattern exploration
- Business insights and recommendations

This project demonstrates applied Exploratory Data Analysis (EDA) using real-world transportation data.

---

## 📊 Dataset Description

The dataset contains daily aggregated bike rental data from the Capital Bikeshare System – Washington D.C. (2011–2012).

### Key Variables

| Variable | Description |
|----------|------------|
| dteday | Date |
| season | Season (1: Spring, 2: Summer, 3: Fall, 4: Winter) |
| yr | Year (0: 2011, 1: 2012) |
| mnth | Month |
| holiday | Whether the day is a holiday |
| workingday | Working day indicator |
| weathersit | Weather situation category |
| temp | Normalized temperature |
| atemp | Normalized feeling temperature |
| hum | Normalized humidity |
| windspeed | Normalized wind speed |
| casual | Casual users count |
| registered | Registered users count |
| cnt | Total rental count |

---

## 🔎 Analysis Performed

### 1️⃣ Descriptive Statistics

- Measuring Central Tendency (Mean, Median)
- Measuring Dispersion (Variance, Standard Deviation)
- Measuring Asymmetry (Skewness)
- Correlation Analysis (Data Relationship)

### 2️⃣ Data Quality Assessment

Checked for:
- Missing values
- Duplicate rows
- Invalid values
- Inconsistent data types
- Outliers (IQR method)

### 3️⃣ Data Cleaning

- Dropped duplicate rows (if any)
- Imputed missing numerical values using median
- Converted date column to datetime format
- Validated numerical ranges
- Identified outliers using IQR method

All cleaning decisions are documented in the Excel workbook included in this repository.

---

## 📈 Key Insights

- Bike rental demand increased significantly in the second year.
- Weather conditions strongly influence daily rental count.
- Temperature has a positive correlation with demand.
- Clear weather leads to higher usage, while poor weather reduces rentals.
- Working days show stable patterns, while weekends are more fluctuative.

---

## 💡 Business Recommendations

- Optimize bike distribution during high-demand seasons.
- Use weather forecasting for operational planning.
- Apply promotional strategies during low-demand periods.
- Segment users into commuter and recreational groups.

---

## 📂 Project Structure

```
├── day.csv
├── Bike_Sharing_Analysis_Workbook.xlsx
├── Bike_Sharing_EDA_Presentation.pptx
└── README.md
```

---

## 🛠 Tools Used

- Python (Pandas, NumPy)
- Excel
- PowerPoint
- Git & GitHub

---

## 📚 Dataset Source

Fanaee-T, H., & Gama, J. (2013).
Event labeling combining ensemble detectors and background knowledge.
Progress in Artificial Intelligence.

Original dataset:
https://capitalbikeshare.com/system-data

---

## 👩‍💻 Author

Dwi Nur Indah Sari
Exploratory Data Analysis Project  
