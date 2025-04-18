# Medicare Fraud Claims Analysis

![Restaurant](images/Medicare.jpg)

## 📑Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Power BI Interactive dashboard](#power-bi-interactive-dashboard)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)

## 📁Project Overview
Medicare fraud costs the U.S. healthcare system billions annually. This project analyzes inpatient and outpatient claims data, along with provider, physician, beneficiary, diagnosis, and procedure details—to identify patterns and anomalies that may indicate fraudulent billing.

## 🌐Data Sources

- <b>Provider:</b> This table captures the information about Providers who gave treatment for the patient as per the claim and details about whether the Provider is involved in fraudulent activities <br>
- <b>Beneficiary:</b> This table contains detailed information about the Beneficiaries (Patient) who have taken treatment from the provider and their demographic details and Chronic Conditions. <br>
- <b>Inpatient:</b> This table captures data claims for the patients admitted to the hospital and the diagnosis procedure codes for the claims. <br>
- <b>Outpatient:</b> This table indicates the details about the claims of patients who visited the hospital and the diagnosis procedure codes for the claims. <br>

### 💻Tools

- Python - Data cleaning and normalization, Exploratory Data analysis
- Pandas - Data manipulation
- Matplotlib & Seaborn - Data visualization
- Power BI - Creating interactive dashboards and reports

### 🔍Data Cleaning and Preparation

The raw Medicare claims data required extensive preprocessing before analysis. Using Python (Pandas, NumPy), the following steps were performed:

- Handled missing, duplicate, and inconsistent values.
- Converted data types (e.g., date formats, categorical encoding).
- Merged inpatient, outpatient, provider, and beneficiary datasets into a unified structure.
- Generated new features such as claim duration, admission duration, and age.

### ✨🔍Exploratory Data Analysis (EDA)

Conducted in-depth exploratory data analysis to gain insights into Medicare claim behavior and identify potential fraud indicators. The analysis focused on various factors, including:<br>

- <b>Distribution Analysis of:</b>
  - Fraudulent Claims
  - Fraudulent Claims across inpatient and outpatient claims
  - Insurance amount reimbursed and deductible amount paid in inpatient and outpatient claims
  - Claim duration, Admission duration, Age of Beneficiaries


- <b>Provider based analysis:</b>
  - Top 10 Provider occurring in fraudulent activities in inpatient claims
  - Top 10 Provider occurring in fraudulent activities in outpatient claims
  - Top 10 Provider occurring in fraudulent activities in both inpatient and Outpatient Claims
  - Top 10 Provider and Physician combos in fraudulent claims in inpatient claims and outpatient claims

- <b>Diagnosis Pattern analysis:</b>
  - Top 10 Diagnosis codes used in fraudulent claims in inpatient claims
  - Top 10 Diagnosis codes used in fraudulent claims in outpatient claims

- <b>Procedure code Pattern analysis</b>
  - Top 10 Procedure codes used in fraudulent claims in inpatient claims
  - Top 10 Procedure codes used in fraudulent claims in outpatient claims

<p>
  <a href="https://github.com/Bhuvi128/Bengaluru-Restaurant-Trends-Analysis/blob/main/Bengaluru%20Restaurant%20Trends%20Analysis.ipynb" target="_blank" style="text-decoration:none;">
    <img src="https://img.shields.io/badge/View-Python_Notebook-ffbcc4?style=for-the-badge&logo=jupyter" alt="Python Notebook">
  </a>
</p>

### 📊Power BI Interactive dashboard

An interactive Power BI dashboard was built to visualize key metrics and uncover potential Medicare fraud patterns.

![Medicare Claims Fraud Overview](Power-BI-Dashboards/Medicare-Claims-Fraud-Overview.png)<br>
![Provider-and-Physician-Analysis](Power-BI-Dashboards/Provider-and-Physician-Analysis.png)<br>
![Diagnosis-and-Procedure-Pattern](Power-BI-Dashboards/Diagnosis-and-Procedure-Pattern.png)<br>
![Geographic](Power-BI-Dashboards/Geographic-Fraud-Mapping.png)<br>
![Beneficiary](Power-BI-Dashboards/Beneficiary-Risk-Profiling.png)<br>

<p>
   <a href="https://drive.google.com/file/d/1uiFNtuu1ThZB6MZflrG7y6VcrzHjl6W_/view?usp=drive_link" target="_blank" style="text-decoration:none;">
    <img src="https://img.shields.io/badge/Download-Dashboard-babbf6?style=for-the-badge&logo=github" alt="Download Dashboard">
  </a>
</p>

### 📝Results/Findings

- <b>Dominance of Major Chains:</b>
  - The Bengaluru restaurant landscape is heavily influenced by popular chains like Cafe Coffee Day, McDonald's, and Baskin-Robbins, indicating strong customer preference for recognizable brands.
    
- <b>High Demand for Dessert and Beverages:</b>
  - Chains like Corner House Ice Cream, Sweet Truth, and The Chocolate Heaven highlight the popularity of dessert and beverage-focused outlets across the city.
    
- <b>Casual Dining and Quick Bites are Preferred:</b>
  - The majority of outlets fall under Casual Dining, Quick Bites, and Cafes, showing that customers favor relaxed and accessible dining experiences.

- <b>Popular Cuisines:</b>
  - North Indian, South Indian, and Chinese are the most common cuisines offered, reflecting local tastes and preferences.
 
- <b>Neighborhood Trends:</b>
  - Areas like BTM, HSR Layout, and Koramangala host a dense concentration of restaurants, making them hotspots for food businesses but also increasing competition.

- <b>Online Delivery Popularity:</b>
  - A large number of restaurants offer online delivery, suggesting the growing reliance on food delivery apps among Bengaluru residents.

- <b>Price and Ratings Relationship:</b>
  - There isn’t a strict correlation between high pricing and high ratings. Reasonably priced restaurants often maintain strong customer satisfaction through quality and service.

### 📝🚀Recommendations

- <b>New Entrants Should Focus on High-Demand Locations:</b>
Areas such as Koramangala, BTM, and HSR Layout are ideal due to high foot traffic and customer activity, though competition is also higher.

- <b>Consider Offering Dessert or Beverage Options:</b>
Given the success of dessert chains, incorporating such items can attract additional customer segments and boost average order value.

- <b>Opt for Quick Bites or Cafe Formats:</b>
For lower startup and operating costs with high customer turnover, focusing on Quick Bites or Cafe formats can be a strategic entry point.

- <b>Offer Online Delivery Services:</b>
To remain competitive and meet customer expectations, ensure integration with major food delivery platforms.

- <b>Keep Prices Reasonable Without Compromising Quality:</b>
High ratings do not necessarily require high prices. Focus on maintaining quality and service to achieve strong customer loyalty.

- <b>Leverage Popular Cuisines:</b>
Starting with familiar and in-demand cuisines like North Indian and South Indian can help attract a larger customer base, especially in new setups.
