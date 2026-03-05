
# Healthcare Operational Performance & Revenue Analytics

## 🏥 Project Overview

This project presents a **3-page Power BI dashboard** designed to analyze **55,000+ hospital patient records** and provide actionable insights into financial performance, clinical patterns, and operational efficiency.

The dashboard acts as a  **“Pulse Check” for hospital performance** , centralizing financial, clinical, and operational metrics in one interactive report.

**Key findings:**

* **Total Revenue:** $1.40B
* **Total Admissions:** 55K
* **Average Length of Stay:** 15 Days
* **ER Admission Rate:** 32.93%

These insights help hospital leadership make  **data-driven decisions for resource allocation, staffing, and patient care optimization** .

---

## 📊 Dashboard Preview

### Executive Summary

![Executive Dashboard](04_Documentation/Executive_Overview_Dashboard.png)

### Patient Demographics & Clinical Insights

![Patient Insights](04_Documentation/Patient_Demographics_Insights.png)

### Doctor & Hospital Performance

![Doctor Analysis](04_Documentation/Doctor_Hospital_Performance.png)

---

## 🚀 Key Features

### Executive Summary

High-level KPI monitoring including:

* Total Admissions
* Total Revenue
* Average Length of Stay
* ER Admission Rate

### Clinical Insights

Detailed analysis of:

* Patient demographics (Age Groups, Blood Types)
* Medication distribution
* Abnormal vs Normal test result patterns

### Operational Analysis

Performance insights across:

* **Hospitals**
* **Doctors**
* **Insurance providers**

Includes **ranking and filtering capabilities** to identify top performers.

### Interactive Dashboard

Users can dynamically filter data by:

* Year
* Admission Type
* Medical Condition

---

## 🛠 Tech Stack & Skills Demonstrated

### Power Query (ETL)

* Cleaned and standardized **55K+ rows of healthcare data**
* Handled duplicates and missing values
* Engineered **Length of Stay** metric

### Data Modeling

* Implemented a **Star Schema**
* Built a **custom Calendar table** using DAX

### DAX (Data Analysis Expressions)

Created analytical measures including:

* **ER Admission Rate**

  Calculated using `DIVIDE()` and `CALCULATE()` to monitor emergency load.
* **Total Revenue**

  Aggregated billing across hospitals and insurance providers.
* **Average Length of Stay**

  Derived from admission and discharge dates.

### Data Visualization

Used Power BI visuals to highlight insights:

* KPI Cards
* Treemaps
* Donut Charts
* Stacked Bar Charts
* Scatter Plots
* Conditional Formatting (Heatmaps)

---

## 📂 Project Structure

<pre class="overflow-visible! px-0!" data-start="3170" data-end="3559"><div class="relative w-full my-4"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute end-1.5 top-1 z-2 md:end-2 md:top-1"></div><div class="pt-3"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼ5 ͼj"><div class="cm-scroller"><div class="cm-content q9tKkq_readonly"><span>Healthcare-Analytics-Dashboard/</span><br/><span>├── 01_Data/</span><br/><span>│   └── healthcare_dataset.csv</span><br/><span>├── 02_Scripts/</span><br/><span>│   └── DAX_Measures.txt</span><br/><span>├── 03_Report/</span><br/><span>│   └── Healthcare_Operations_Analytics_v1.0.pbix</span><br/><span>├── 04_Documentation/</span><br/><span>│   ├── Executive_Overview_Dashboard.png</span><br/><span>│   ├── Patient_Demographics_Insights.png</span><br/><span>│   ├── Doctor_Hospital_Performance.png</span><br/><span>│   └── Project_Implementation_Guide.pdf</span><br/><span>└── README.md</span></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

## 📈 Business Impact

### Financial Oversight

Automated monitoring of **$1.40B in hospital billing revenue** across multiple insurance providers.

### Resource Optimization

Identified that  **32.93% of admissions originate from the Emergency Department** , highlighting staffing and capacity planning needs.

### Clinical Quality Insights

Revealed  **medication distribution patterns across medical conditions** , helping identify treatment trends for diseases such as  **Diabetes, Cancer, and Hypertension** .

---

## ▶️ How to Use

1. Download the `.pbix` file from the **03_Report** folder.
2. Open it using  **Microsoft Power BI Desktop** .
3. Use slicers to filter data by  **Year, Admission Type, or Medical Condition** .

---

## 👨‍💻 Author

**Akash Gupta**

Aspiring Data Analyst | Power BI | SQL | Data Visualization
