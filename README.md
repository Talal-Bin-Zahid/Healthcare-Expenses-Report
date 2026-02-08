# Healthcare-Expenses-Report
<img width="959" height="540" alt="Healthcare Expenses Report" src="https://github.com/user-attachments/assets/51441fe6-194d-4980-9055-db14d1d5eef7" />

---

## 📌 Project Overview

The **Healthcare Expenses Report** is an end-to-end, interactive **Power BI dashboard** built to analyze healthcare costs, patient demographics, medical conditions, insurance coverage, and provider performance. The report spans **January 2020 to early 2024** and is designed to support **financial oversight, operational efficiency, and strategic decision-making** for healthcare stakeholders.

This dashboard centralizes clinical, demographic, and billing data into a single analytical layer, enabling users to identify trends, compare providers, and uncover cost drivers across the healthcare ecosystem.

---

## 🎯 Business Objectives

* Monitor **healthcare billing trends** over time
* Understand **patient distribution** by age, gender, and medical condition
* Evaluate **insurance provider contributions**
* Identify **high-billing doctors and hospitals**
* Analyze **admission patterns** across genders
* Support data-driven decisions for **cost optimization and resource allocation**

---

## 📊 Global KPIs (Report-Level Metrics)

| KPI                                       | Value           | Description                                             |
| ----------------------------------------- | --------------- | ------------------------------------------------------- |
| **Total Patients**                        | **55.50K**      | Total number of patients included in the dataset        |
| **Total Billing Amount**                  | **$1.42B**      | Aggregate healthcare billing across all years           |
| **Average Billing per Patient**           | **$25.54K**     | Mean billing amount per patient                         |
| **Average Patient Age**                   | **51.54 Years** | Average age of all patients                             |
| **Average Billing per Medical Condition** | **$236.24M**    | Mean billing contribution per condition                 |
| **Primary Medical Condition (Filter)**    | **Arthritis**   | Default selected condition used for contextual analysis |

---

## 📈 Dashboard Pages & Visualizations

### 1️⃣ Billing Amount by Month

**Visualization Type:** Line Chart
**Metrics Used:** Total Billing Amount, Date (Month-Year)

**Description:**
Displays monthly healthcare billing trends from 2020 to early 2024.

**Key Observations:**

* Billing remains relatively stable year-over-year
* Minor fluctuations reflect seasonal or utilization changes
* A sharp decline in the latest period suggests **incomplete or partial data** rather than an actual cost reduction

---

### 2️⃣ Patient Demographics – Gender Distribution

**Visualization Type:** Donut Chart
**Metrics Used:** Patient Count, Gender

**Breakdown:**

* **Male:** 27.77K (50.04%)
* **Female:** 27.73K (49.96%)

**Insight:**
Patient distribution is almost perfectly balanced across genders, indicating no demographic skew.

---

### 3️⃣ Patients by Medical Condition

**Visualization Type:** Horizontal Bar Chart
**Metrics Used:** Patient Count, Medical Condition

**Conditions & Volumes:**

* Arthritis: **9.31K**
* Diabetes: **9.30K**
* Hypertension: **9.25K**
* Obesity: **~9.23K**
* Cancer: **~9.22K**
* Asthma: **9.19K**

**Insight:**
Patient volumes are evenly distributed across major chronic conditions, highlighting diversified healthcare demand.

---

### 4️⃣ Age vs. Billing Amount

**Visualization Type:** Scatter Plot
**Metrics Used:** Patient Age, Billing Amount

**Description:**
Illustrates the relationship between patient age and billing amount.

**Insight:**

* Billing is spread across all age groups
* No extreme concentration in a single age band
* Indicates cost drivers are condition- and treatment-based rather than age-exclusive

---

### 5️⃣ Insurance Provider Performance

#### 🔹 Total Billing by Insurance Provider

**Visualization Type:** Bar Chart
**Metrics Used:** Total Billing Amount, Insurance Provider

**Providers Included:**

* Cigna – **~$287M**
* Medicare – **~$286M**
* Blue Cross – **~$283M**
* UnitedHealthcare – **~$282M**
* Aetna – **~$279M**

**Insight:**
Billing is evenly distributed across major insurers, indicating a well-diversified payer mix with no over-reliance on a single provider.

---

### 6️⃣ Medical Condition vs. Insurance Provider Matrix

**Visualization Type:** Table / Matrix
**Metrics Used:** Total Billing Amount

**Dimensions:**

* Rows: Medical Conditions
* Columns: Insurance Providers (Aetna, Blue Cross, Cigna)

**Purpose:**
Enables cross-comparison of billing contribution by condition and insurer, supporting reimbursement and contract analysis.

---

### 7️⃣ Provider Performance Analysis

#### 🔹 Top Doctors by Billing

**Visualization Type:** Ranked Bar Chart
**Metrics Used:** Total Billing Amount, Doctor Name

**Top Performers (Sample):**

* Michael Smith – **$0.78M**
* Robert Smith – **$0.63M**
* John Smith – **$0.61M**
* Robert Johnson – **$0.52M**
* David Smith – **$0.47M**

**Insight:**
Highlights high-billing physicians for workload analysis, performance reviews, and operational planning.

---

#### 🔹 Top 10 Hospitals by Billing

**Visualization Type:** Treemap
**Metrics Used:** Total Billing Amount, Hospital Name

**Purpose:**
Identifies hospitals contributing the most to overall billing volume, supporting capacity planning and strategic investments.

---

### 8️⃣ Admission Type Analysis by Gender

**Visualization Type:** Stacked Percentage Bar Chart
**Metrics Used:** Admission Type, Gender, Patient Count

**Admission Types:**

* Elective
* Urgent
* Emergency

**Insight:**

* Admission patterns are evenly distributed between males and females
* No significant gender-based bias in admission types

---

## 🎛️ Filters & Parameters

The dashboard includes interactive slicers for:

* **Medical Condition**
* **Insurance Provider**
* **Gender**
* **Year / Date Range**

These parameters dynamically update all KPIs and visuals to support deep-dive analysis.

---

## 🛠️ Technical Stack

* **Power BI Desktop** – Data modeling and visualization
* **Power Query** – Data extraction, cleaning, and transformation
* **DAX (Data Analysis Expressions)** – KPI calculations and business logic
* **Star Schema Data Model** – Optimized for analytical performance

---

## 🔍 Key Analytical Insights

* Healthcare billing is **balanced across genders**
* Chronic conditions contribute **similar patient volumes and cost impact**
* Insurance billing is **evenly distributed**, reducing payer risk
* High-billing doctors and hospitals can be clearly identified for operational review
* Recent billing decline reflects **data completeness issues**, not actual cost reduction

---

## 🚀 Future Enhancements

* Predictive **cost forecasting and trend modeling**
* Drill-through pages by **hospital, doctor, and condition**
* **Length of stay** and **time-to-admission** metrics
* Integration with **clinical outcomes and readmission rates**
* Cost-to-outcome efficiency analysis

---

## 📁 Intended Audience

* Healthcare Administrators
* Financial & Operations Analysts
* Hospital Management
* Insurance & Policy Stakeholders
* Data & BI Professionals

---

## ✅ Conclusion

This Power BI Healthcare Expenses Report provides a **holistic, data-driven view** of healthcare costs, utilization, and provider performance. By combining financial, demographic, and clinical dimensions, the dashboard enables smarter decisions, improved transparency, and better healthcare cost management.

