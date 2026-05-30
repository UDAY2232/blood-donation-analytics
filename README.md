# 🩸 AI-Powered Blood Donation Analytics and Demand Forecasting System

## 📌 Overview

This project focuses on analyzing blood donation data, identifying blood shortages, and forecasting future blood demand using Machine Learning and Power BI.

The system helps healthcare organizations and blood banks make data-driven decisions by monitoring donor activity, analyzing demand-supply gaps, identifying high-risk regions, and predicting future blood requirements.

---

## 🎯 Objectives

- Analyze donor behavior and donation patterns.
- Identify blood demand and supply gaps.
- Detect blood shortage risks.
- Perform city-wise risk analysis.
- Forecast future blood demand using Machine Learning.
- Visualize insights through interactive Power BI dashboards.

---

## 🛠️ Technologies Used

### Programming & Analytics
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-Learn
- Random Forest Regressor

### Data Visualization
- Power BI
- DAX

---

## 📂 Dataset

### Source
Blood Transfusion Service Center Dataset (UCI Repository)

### Features

| Feature | Description |
|----------|------------|
| Recency | Months since last donation |
| Frequency | Total number of donations |
| Monetary | Total blood donated (cc) |
| Time | Total months as donor |
| Target | Donated in March 2007 (Yes/No) |

Additional synthetic attributes generated:

- Blood Group
- City
- Age
- Availability Status

---

## 🔍 Exploratory Data Analysis (EDA)

Performed:

- Data Cleaning
- Missing Value Analysis
- Donation Frequency Analysis
- Recency Analysis
- Correlation Analysis
- Donor Segmentation

### Key Findings

- Most donors donated fewer than 5 times.
- Only 23.8% of donors donated during the target period.
- O+ blood group showed the highest demand.
- Significant demand-supply gaps were observed across all blood groups.

---

## 🧠 Machine Learning

### Algorithm Used

Random Forest Regressor

### Purpose

Predict future blood demand based on:

- Month
- Blood Group

### Workflow

1. Data Preparation
2. Feature Encoding
3. Train-Test Split
4. Model Training
5. Forecast Generation

---

## 📊 Power BI Dashboard

### Executive Dashboard

KPIs:
- Total Donors
- Active Donors
- Total Requests
- Total Units Required

Visuals:
- Donor Segmentation
- Blood Demand Analysis
- Blood Supply Analysis

### Demand vs Supply Analysis

Visuals:
- Blood Group Demand vs Supply
- Gap Analysis
- Critical Blood Group Detection

### City Risk Analysis

Visuals:
- City-wise Demand
- City-wise Supply
- Risk Assessment

---

## 📈 Business Impact

This solution helps:

- Blood Banks
- Hospitals
- Healthcare Organizations

Benefits:

- Better blood inventory planning
- Early shortage detection
- Improved donor management
- Data-driven decision making
- Future demand forecasting



## 🚀 Future Enhancements

- Real-time donor matching
- Emergency blood request system
- Hospital integration
- Geospatial donor mapping
- AI-based donor recommendation system
- Cloud deployment

---

## 👨‍💻 Author

**Uday Chirra**

Data Analytics | Machine Learning | Power BI | Python

---

⭐ If you like this project, consider giving it a star.
