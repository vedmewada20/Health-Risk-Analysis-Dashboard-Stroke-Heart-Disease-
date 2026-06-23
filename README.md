# Health-Risk-Analysis-Dashboard-Stroke-Heart-Disease-
📌 Project Description
Health Risk Analysis Dashboard is a Power BI and Python-based healthcare analytics project that analyzes stroke and heart disease risk using age, BMI, smoking status, hypertension, gender, and glucose data. The project includes data cleaning, KPI creation, interactive dashboarding, and health-risk trend analysis for patient data exploration.

## 📖 Project Overview

The **Health Risk Analysis Dashboard** is a healthcare-focused **Data Analyst project** created to analyze patient health records and identify risk patterns related to **stroke** and **heart disease**. The project studies how age, smoking status, BMI, hypertension, glucose level, and gender are associated with health outcomes.

The project uses **Python for data cleaning and preprocessing** and **Power BI for dashboard creation**. The main goal is to convert raw healthcare data into a clean, interactive dashboard that helps analyze patient risk patterns and supports data-driven health insights.

---

## 🎯 Objectives

* Analyze stroke and heart disease patterns in patient data
* Study health risk across different **age groups**
* Evaluate smoking status and hypertension impact
* Monitor BMI and average glucose level trends
* Build an interactive healthcare dashboard using Power BI
* Generate health-risk insights from structured patient data

---

## 🗂️ Dataset Files Used

This project uses a healthcare dataset containing patient-level health and stroke-related records.

* **healthcare-dataset-stroke-data.csv** → Raw healthcare dataset
* **Cleaned_health.csv** → Final cleaned dataset after preprocessing
* **Cleaned_health.xlsx** → Excel version of cleaned dataset for reporting / Power BI use
* **HealthCare.pbix** → Power BI dashboard file

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Power BI**

### Skills Used

* Data Cleaning
* Data Preprocessing
* Dashboard Design
* KPI Analysis
* Healthcare Data Analysis
* Business / Risk Insight Generation

---

## ⚙️ Project Workflow

### 1) Data Collection

Loaded the healthcare dataset containing patient details such as age, gender, BMI, hypertension, heart disease, smoking status, and stroke information.

### 2) Data Cleaning & Preprocessing

Performed data cleaning using Python:

* checked missing values
* handled null values where required
* cleaned categorical fields
* prepared age-based grouping for analysis
* formatted dataset for Power BI dashboarding

### 3) Feature Preparation

Prepared analytical fields for dashboard reporting such as:

* age groups
* stroke count analysis
* heart disease count analysis
* BMI by age group
* smoking-status-based health analysis
* hypertension-based risk distribution

### 4) Dashboard Development

Imported the cleaned healthcare dataset into Power BI and created an interactive dashboard with KPI cards, charts, donut charts, and slicers.

---

## 📊 Dashboard KPIs

The dashboard includes the following key indicators:

* **Total Stroke Cases**
* **Total Heart Disease Cases**
* **Average Glucose Level**
* **Hypertension Distribution**
* **Age-group based health metrics**

---

## 📈 Dashboard Visuals

The Power BI dashboard includes:

### 1. Sum of Age by Smoking Status

Shows the distribution of age across different smoking categories.

### 2. Sum of BMI by Age Group

Analyzes BMI contribution across age groups.

### 3. Sum of Heart Disease by Age Group

Tracks how heart disease cases vary across different age groups.

### 4. Sum of Stroke by Age Group

Highlights stroke cases across different age groups.

### 5. Hypertension Distribution

Displays the patient split based on hypertension condition.

### 6. Interactive Filters

The dashboard includes slicers for:

* **Age range**
* **Gender**

---

## 📌 Key Business / Healthcare Questions Answered

This dashboard helps answer questions such as:

* Which age groups show higher stroke risk?
* Which age groups show higher heart disease cases?
* How does smoking status relate to health risk distribution?
* What is the BMI pattern across age groups?
* How are hypertension and disease risk connected?
* How does average glucose level vary across filtered patient groups?

---

## 💡 Key Insights

This project can help identify:

* higher stroke risk concentration in older age groups
* heart disease patterns across age groups
* smoking-status-related health trends
* hypertension distribution among patients
* BMI and glucose-level related health patterns
* gender-based filtered health risk analysis

---


## 📁 Project Structure

```bash id="3wkrha"
Health-Risk-Analysis-Dashboard/
│
├── data/
│   ├── healthcare-dataset-stroke-data.csv
│   ├── Cleaned_health.csv
│   └── Cleaned_health.xlsx
│
├── dashboard/
│   └── HealthCare.pbix
│
├── screenshots/
│   ├── health_risk_dashboard_overview.png
│   ├── male_filter_view.png
│   ├── female_filter_view.png
│   └── filtered_dashboard_view.png
│
└── README.md
```

---

## 📸 Dashboard Preview

### Dashboard Overview
<img width="1308" height="725" alt="Screenshot 2026-01-02 152634" src="https://github.com/user-attachments/assets/e57f2ae1-e5a0-407c-bdaf-af0df1a7c044" />
```md id="98g1g2"
![Dashboard Overview](screenshots/health_risk_dashboard_overview.png)
```

### Male Filter View
<img width="1297" height="730" alt="Screenshot 2026-01-02 152718" src="https://github.com/user-attachments/assets/0d05d3e4-2ab1-40b2-a766-7369b05f3ce0" />

```md id="mib0c8"
![Male Filter View](screenshots/male_filter_view.png)
```

### Female Filter View
<img width="1305" height="729" alt="Screenshot 2026-01-02 152755" src="https://github.com/user-attachments/assets/1759a813-0e2c-4a84-bbd6-0977fdd83d01" />

```md id="f6vt9q"
![Female Filter View](screenshots/female_filter_view.png)
```

## 🔍 Example KPIs / Metrics

Important dashboard metrics in this project include:

* **Total Stroke Cases** = Sum / count of stroke cases
* **Total Heart Disease Cases** = Sum / count of heart disease cases
* **Average Glucose Level** = Average of glucose levels
* **BMI by Age Group** = Aggregated BMI by age segments
* **Hypertension Distribution** = Split of hypertension vs non-hypertension cases

---


## 🚀 How to Use This Project

### Python side

* load the raw healthcare CSV file
* clean null values and categorical fields
* prepare age groups and analytical columns
* export cleaned dataset for Power BI

### Power BI side

* open `HealthCare.pbix`
* refresh the cleaned dataset if required
* explore healthcare KPIs and visuals using filters

---

## 🧠 Skills Demonstrated

This project demonstrates:

* Data Cleaning using Python
* Data Preprocessing
* Power BI Dashboard Development
* Healthcare Data Analysis
* KPI Design
* Analytical Thinking with domain-based data

---

## 📌 Why This Project Matters

This project is valuable because it applies data analysis to a **healthcare risk use case**, which is more domain-focused than a generic dashboard project. It shows how healthcare data can be cleaned, structured, and visualized to identify important risk patterns related to stroke and heart disease.

It is useful for a **Data Analyst fresher portfolio** because it demonstrates:

* domain-based analysis
* dashboarding ability
* KPI reporting
* healthcare data understanding
* analytical storytelling

---

## 🔮 Future Improvements

This project can be improved by:

* adding correlation analysis between BMI, glucose, and stroke risk
* creating deeper gender-wise and smoking-wise health analysis
* adding predictive ML model for stroke risk
* integrating SQL with Power BI workflow
* adding more patient risk segmentation visuals

---

## 👨‍💻 Author

**Ved Suthar**
Aspiring Data Analyst | Data Science & GenAI Learner
Ahmedabad, India
