# 🏥 Healthcare Disease & Risk Analysis Dashboard

An interactive **Power BI healthcare analytics project** designed to analyze patient health conditions, disease patterns, demographic factors, and health-related risks.

The dashboard transforms healthcare data into meaningful visual insights that can help identify disease patterns, compare patient groups, and understand major health risk factors.

---

## 📌 Project Overview

Healthcare organizations generate large amounts of patient and health-related data. Analyzing this data can help identify patterns across diseases, demographics, and health indicators.

This project uses **Power BI** to build an interactive dashboard that provides a consolidated view of:

- Patient demographics
- Disease distribution
- Disease patterns by age and gender
- Health indicators
- Lifestyle and risk factors
- Disease-related trends
- Patient risk patterns

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze the distribution of diseases among patients
- Understand disease patterns across different age groups
- Compare disease prevalence by gender
- Analyze important health indicators
- Identify major health and lifestyle risk factors
- Explore relationships between demographics and diseases
- Create an interactive dashboard for healthcare analysis
- Present complex healthcare data through easy-to-understand visualizations

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Calculated measures and analytical calculations |
| **Data Modeling** | Relationships and analytical structure |
| **Excel / CSV** | Data source and preparation |

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

The cleaning process included:

- Handling missing values
- Removing duplicate records
- Correcting data types
- Standardizing categorical values
- Replacing unknown values where appropriate
- Handling blank values
- Checking inconsistent records
- Preparing fields for analysis
- Creating analytical categories where required

---

## 📊 Dashboard KPIs

The dashboard provides key healthcare indicators such as:

- 👥 Total Patients
- 🦠 Total Disease Cases
- 📈 Disease Rate
- 👨 Male Patients
- 👩 Female Patients
- ⚠️ High-Risk Patients

The exact KPI selection may vary depending on the final dashboard implementation.

---

## 📈 Dashboard Analysis

### 1. Disease Analysis

The dashboard analyzes the distribution of diseases among patients and identifies which diseases have the highest representation.

### 2. Disease by Gender

Disease patterns are compared across male and female patients to identify differences in disease prevalence.

### 3. Disease by Age Group

Patients are grouped into age categories to understand how disease occurrence varies across different age groups.

### 4. Health Risk Analysis

The dashboard examines health-related factors that may contribute to increased disease risk.

### 5. Demographic Analysis

Patient demographics are analyzed to understand the relationship between age, gender, and disease patterns.

### 6. Interactive Filtering

Users can interact with the dashboard using filters and slicers to analyze specific patient groups and disease categories.

---

## 📊 Power BI Visualizations

The dashboard uses a combination of visualizations to avoid repetitive chart types and improve analytical storytelling.

Examples include:

- KPI Cards
- Bar Charts
- Column Charts
- Donut Charts
- Line Charts
- Matrix/Table
- Slicers
- Interactive Filters

---

## 🧮 DAX

DAX measures are used to calculate important healthcare metrics and support interactive analysis.

Example measures include:

```DAX
Total Patients =
DISTINCTCOUNT(Patients[PatientID])
Total Disease Cases =
CALCULATE(
    [Total Patients],
    Patients[Disease] <> "None"
)

# 🗃️ Data Modeling

The Power BI data model is designed to support efficient analysis and filtering.

The model includes:

Patient/transaction-level data
Relevant categorical attributes
Date-related fields where applicable
Calculated measures
Relationships between analytical tables where required

A structured data model helps ensure accurate calculations and interactive filtering across the dashboard.

🔍 Key Insights

The dashboard helps answer questions such as:

Which diseases are most common?
Which age groups have higher disease occurrence?
How does disease distribution differ by gender?
Which health factors are associated with higher risk?
Which patient segments require greater attention?
How are disease patterns distributed across the available demographic groups?
💼 Business Value

This dashboard demonstrates how healthcare data can be transformed into actionable insights.

Potential business applications include:

Healthcare reporting
Patient population analysis
Disease monitoring
Risk identification
Demographic analysis
Healthcare decision support
Management reporting

The dashboard provides a consolidated view that can help analysts and decision-makers identify important patterns more efficiently.

Project Structure
healthcare-disease-risk-analysis/
│
├── README.md
│
├── Dataset/
│   └── healthcare_disease_dataset.csv
│
├── PowerBI/
│   └── Healthcare_Disease_Risk_Analysis.pbix
│
├── Documentation/
│   └── Healthcare_Disease_Risk_Analysis_Documentation.pdf
│
├── Screenshots/
│   └── healthcare_dashboard.png
│
└── Insights/
    └── Healthcare_Dashboard_Insights.md

🚀 Future Enhancements

Possible future improvements include:

Advanced healthcare risk scoring
Additional time-based analysis
More detailed patient segmentation
Predictive analytics
Automated reporting
Advanced DAX calculations
Integration with additional healthcare datasets
👩‍💻 Author

Reshma Krishnapillai

Aspiring Data Analyst | Power BI | SQL | Excel | Python

⭐ Project Highlights

Domain: Healthcare Analytics
Tool: Power BI
Focus: Disease Analysis & Health Risk Insights
Dashboard: Interactive One-Page Dashboard
