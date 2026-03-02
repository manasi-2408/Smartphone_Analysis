# 📱 Smartphone Usage & Well-Being Analysis

## 📌 Project Overview

This project analyzes smartphone usage behavior and its relationship with stress levels, sleep duration, productivity, and lifestyle factors across 50,000 users.

The objective is to evaluate whether demographic attributes (gender, age, occupation, device type) and behavioral metrics (daily phone usage, social media hours, app usage count, caffeine intake) significantly impact well-being indicators.

The analysis combines:

- SQL (data extraction)
- Python (data cleaning & visualization)
- Power BI (interactive dashboard)
- Statistical & correlation analysis

---

## 🎯 Problem Statement

Smartphone usage is commonly assumed to negatively impact stress, sleep, and productivity. However, these claims are often anecdotal.

This project investigates whether higher digital engagement meaningfully influences well-being metrics using structured data analysis.

---

## 🗂️ Project Structure

```
Smartphone_Analysis/
│
├── data/
│   └── smartphone.csv
│
├── images/
│   ├── img.png
│   ├── img_1.png
│   └── img_2.png
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── data_visualization.ipynb
│
├── powerbi/
│   └── smartphone.pbix
│
├── report/
│   └── smartphone.docx
│
└── README.md
```

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy)
- Matplotlib
- Seaborn
- MySQL
- SQLAlchemy
- Power BI
- Jupyter Notebook

---

## 📊 Data Processing Workflow

### 1️⃣ Data Extraction

- Connected to MySQL database  
- Queried and loaded dataset into Pandas  
- Exported cleaned dataset as CSV  

### 2️⃣ Data Cleaning

- Created custom Age Groups  
- Created App Usage Count Groups  
- Checked null values  
- Verified data types and distributions  

### 3️⃣ Exploratory Data Analysis

- Gender-based usage comparison  
- Device-type comparison  
- Occupation-level behavior analysis  
- Usage intensity segmentation  
- Correlation matrix  
- Distribution analysis (boxplots, standard deviation checks)  

### 4️⃣ Dashboard Development (Power BI)

#### Page 1 – User Behavior Overview

- Total Users  
- Avg Daily Hours  
- Avg Stress  
- Avg Sleep  
- Avg Productivity  
- App Usage Distribution  
- Age & Occupation Comparisons  

#### Page 2 – Impact Analysis

- Heavy Usage %  
- Stress vs Daily Hours  
- Productivity vs App Usage  
- Social Media vs Productivity  
- Correlation Insights  

---

## 🔎 Key Insights

- No significant behavioral difference across gender.  
- Device type does not meaningfully impact usage patterns.  
- Age-based differences in stress and sleep are marginal.  
- Occupation does not strongly influence productivity or digital behavior.  
- Heavy phone usage does not strongly correlate with higher stress or lower productivity.  
- Correlation coefficients between usage metrics and well-being indicators remain weak.  

---

## 📈 Correlation Findings

Correlation analysis shows:

- Weak relationship between Daily Phone Hours and Stress  
- Minimal association between Social Media Hours and Productivity  
- No strong predictive variable for well-being outcomes  

---

## 📌 Business Implications

- Demographic segmentation alone offers limited predictive value.  
- High digital engagement appears normalized across groups.  
- Behavioral targeting would require deeper contextual or psychological variables.  
- Common assumptions about heavy smartphone usage leading to negative outcomes are not strongly supported by this dataset.  

---

## 📄 Report

A detailed analytical report is available at:

```
report/smartphone.docx
```

---

## 📊 Power BI Dashboard

Interactive dashboard file:

```
powerbi/smartphone.pbix
```

---

## 🚀 How to Run the Project

1. Clone the repository  
2. Install required Python libraries:

```
pip install pandas numpy matplotlib seaborn mysql-connector-python sqlalchemy pymysql
```

3. Open Jupyter Notebook  
4. Run:

```
notebooks/data_cleaning.ipynb
notebooks/data_visualization.ipynb
```

---

## 📌 Final Conclusion

Smartphone usage intensity does not meaningfully affect stress, sleep, or productivity in this dataset. Behavioral patterns remain stable across demographic and occupational segments. The dominant theme observed is consistency rather than disparity.
