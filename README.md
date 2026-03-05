# Healthcare Operational Performance & Revenue Analytics

## 🏥 Project Overview
This project involved developing a comprehensive 3-page Power BI dashboard to analyze 55,000+ patient records. The solution provides a "Pulse Check" on hospital health by centralizing financial, clinical, and operational data.

The final dashboard identified a total gross revenue of $1.40bn and an average patient stay of 15 days, enabling hospital leadership to make data-driven decisions regarding resource allocation and patient care quality.

## 🚀 Key Features

- **Executive Summary:** High-level KPI tracking for Admissions, Revenue, and Length of Stay.
- **Clinical Insights:** Deep-dive into patient demographics (Age, Blood Type) and "Abnormal" test result patterns.
- **Operational Analysis:** Performance ranking of 40k+ Doctors and Hospitals using Top-N filtering.
- **Interactive Design:** Dynamic filtering by Year, Admission Type, and Medical Condition.

## 🛠️ Tech Stack & Skills

- **Power Query (ETL):** Standardized 55k rows of irregular string data, handled duplicates, and engineered a custom "Length of Stay" metric.
- **Data Modeling:** Architected a Star Schema with a centralized Fact table and a custom DAX-based Calendar dimension.
- **DAX (Data Analysis Expressions):** Authored complex measures including:
- **ER Admission Rate:** Calculated using DIVIDE and CALCULATE to monitor emergency load (32.93%).
- **Revenue Variance:** SUM of billing across multiple hospital dimensions.
- **Data Visualization:** Implemented conditional formatting (Heatmaps), Treemaps, and Donut charts to highlight outliers and medical distributions.

## 📂 Project Structure

  Healthcare-Analytics-Dashboard/
  ├── 01_Data/
  │   └── healthcare_dataset.csv
  ├── 02_Scripts/
  │   └── DAX_Measures.txt
  ├── 03_Report/
  │   └── Healthcare_Operations_Analytics_v1.0.pbix
  ├── 04_Documentation/
  │   ├── Executive_Overview_Dashboard.png
  │   ├── Patient_Demographics_Insights.png
  │   ├── Doctor_Hospital_Performance.png
  │   └── Project_Implementation_Guide.pdf
  └── README.md

## 📈 Business Impact

- **Financial Oversight:** Automated tracking of $1.40bn in billing across 5 insurance providers.
- **Resource Optimization:** Identified that 32.93% of visits are Emergency-based, allowing for better ER staffing models.
- **Clinical Quality:** Provided visibility into medication distribution patterns against specific medical conditions like Diabetes and Cancer.

