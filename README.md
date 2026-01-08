# 🩺 Healthcare Data Analysis Using Python & Power BI

This project explores a real-world healthcare dataset to uncover disparities in screening participation across race, ethnicity, language, and region. It combines Python-based data science workflows with interactive Power BI dashboards to deliver actionable insights for equitable healthcare strategies.

---

## 📘 Project Overview

Healthcare data often contains valuable information hidden in demographic and performance metrics. The goal of this project was to explore, clean, and analyze the given dataset, understand relationships between key attributes, and visualize important trends.

### 🔍 Key Components
- Python-based EDA, statistical testing, and predictive modeling
- Interactive Power BI dashboard for stakeholder insights
- Professional EDA summary report (PDF)

---

## 🎯 Objectives
- Understand the structure and contents of the dataset
- Perform detailed Exploratory Data Analysis (EDA)
- Handle missing data and inconsistencies
- Identify relationships between demographics and screening behavior
- Create interactive visualizations and dashboards
- Generate a professional summary report

---

## 📊 Dataset Description

**File:** `Data for healthcare analyst.xlsx` (check this Dataset on this repository folder)
**Rows:** 6,597 | **Columns:** 10

| Column Name                  | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| Member ID Encrypted         | Unique identifier for each member                                           |
| EBM Numerator               | Indicates if screening was completed (1 = Yes)                              |
| EBM Denominator             | Indicates eligibility for screening (1 = Eligible)                          |
| ORIG_PREFERRED_LANGUAGE     | Member’s originally preferred language                                      |
| SRC_LANGUAGE                | Language reported by the source system                                      |
| ORIG_RACE                   | Original race classification of the member                                  |
| SRC_RACE                    | Race classification reported by the source system                           |
| Original Member Ethnicity   | Member’s original ethnicity                                                 |
| SRC_ETHNICITY               | Ethnicity reported by the source system                                     |
| Zip (5-digit)               | Member’s residential ZIP code                                               |

---

## 🛠️ Tools & Technologies

| Category         | Tools / Libraries                          |
|------------------|---------------------------------------------|
| Programming      | Python                                      |
| Data Handling    | Pandas, NumPy                               |
| Visualization    | Matplotlib, Seaborn, Plotly                 |
| Dashboard        | Power BI                                    |
| IDE              | Google Colab                                |
| ML / Modeling    | Scikit-learn, Joblib                        |
| Documentation    | Markdown, GitHub                            |

---

## 🧠 Exploratory Data Analysis (EDA)

### 🔧 Tasks
- Data loading and cleaning  
- Handling missing values and inconsistencies  
- Cross-analysis between demographic variables  
- Frequency and distribution visualizations  
- Screening likelihood analysis

### 📐 Techniques
- Descriptive statistics and correlation  
- Aggregation and group-wise metrics  
- Data normalization  
- Visualization through Seaborn and Plotly

---

## 📈 Power BI Dashboard

🖥️ **Live Dashboard**  
👉 [View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZWQ3NWE4MTctNGEzOC00ZDZhLTljN2YtMDU2NTQ2MjNhMzJlIiwidCI6ImYxNjYxNTY4LTMwMjgtNDMyNC05M2E3LWFlNjI4YWE3YjcwOSJ9)

### Dashboard Highlights:
- Member distribution by race, ethnicity, and language  
- Comparison between original and source demographics  
- Screening likelihood and EBM ratio trends  
- Interactive filters by region and demographic category

---

## 🧾 EDA Summary Report

### Race Data Significance
- ORIG_RACE highest frequency → 3,207  
- SRC_RACE highest frequency → 2,137  
- Discrepancies may affect model reliability

### Screening Likelihood by Ethnicity
- **Range:** 0 to 1 | **Mean:** 0.6559 | **Std Dev:** 0.3647  
- High-likelihood groups: Hispanic or Latino – American Indian/Alaska Native (1.0)  
- Low-likelihood groups: Not Hispanic or Latino – Mixed (0.0)

📌 *Insight:* Cultural and access-related factors influence screening behavior. Tailored outreach can improve participation.

---

## 📸 Project Results & Visual Insights
### 📊 Power BI Dashboard
![Power BI Dashboard](Healthcare%20Analysis%20Dashboard%20Screenshot.jpg)

### 📈 Screening Likelihood
![Screening Likelihood](screening%20likelihood.png)

### 📊 EDA Overview
![EDA Overview](screenshot%20Feature%20Importance.png)
![EDA Overview](screenshot%20frequency%20of%20race%20category.png)


---

## 🚀 How to Run

### Option 1 — Google Colab  
Run the Python analysis directly in Google Colab:  
🔗 [Open Notebook](https://colab.research.google.com/drive/1dRKSe6gwG5TrLbHUzJG55k4dr2cJ6B-A?usp=sharing&utm_source=chatgpt.com#scrollTo=P9sg2a_HYhEZ)

### Option 2 — Power BI  
Open the `.pbix` file locally or explore the live dashboard:  
🔗 [View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZWQ3NWE4MTctNGEzOC00ZDZhLTljN2YtMDU2NTQ2MjNhMzJlIiwidCI6ImYxNjYxNTY4LTMwMjgtNDMyNC05M2E3LWFlNjI4YWE3YjcwOSJ9)

## 📊 Key Insights
- Demographic inconsistencies affect screening analysis  
- Significant variation in screening likelihood across ethnic groups  
- Visualizations reveal disparities and cultural influence  
- Power BI enables real-time, interactive monitoring

---

## 🧩 Outcomes
- Cleaned and analyzed real-world healthcare dataset  
- Performed detailed EDA with Python  
- Created Power BI dashboard for business insights  
- Generated EDA Report (PDF) documenting findings  
- Built foundation for predictive modeling and policy evaluation

---

## 👨‍💻 Author

**Waseem Ahmad Dar**  
Data Analyst | Power BI Developer | MEAL Coordinator | Consultant- Govt & Public Sector Advisory  
📍 India  

## 🔗 Connect & Explore

| Platform         | Link                                                                 |
|------------------|----------------------------------------------------------------------|
| 🧑‍💻 GitHub        | [GitHub Profile](https://github.com/Waseemdar)                  |
| 📓 Google Colab   | [Open Python Notebook](https://colab.research.google.com/drive/1dRKSe6gwG5TrLbHUzJG55k4dr2cJ6B-A?usp=sharing&utm_source=chatgpt.com#scrollTo=P9sg2a_HYhEZ) |
| 📊 Power BI       | [View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZWQ3NWE4MTctNGEzOC00ZDZhLTljN2YtMDU2NTQ2MjNhMzJlIiwidCI6ImYxNjYxNTY4LTMwMjgtNDMyNC05M2E3LWFlNjI4YWE3YjcwOSJ9) |

---

## 🧩 Conclusion

This project bridges data science and business intelligence, transforming healthcare data into actionable insights. By combining Python’s analytical power with Power BI’s interactive visuals, it showcases how modern analytics can improve data transparency, decision-making, and equitable healthcare outcomes.
