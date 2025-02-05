# Hospital Emergency Room Visit - Analytics
### [Power BI -Dashboard Link](https://github.com/sachinbasyal/Hospital-ER-Visit-Data-Analytics/blob/main/Power%20BI%20Dashboard%20%26%20Report/Hospital%20ER-Visit%20Insights.pbix)

## Project Background
Emergency rooms (ER) are the frontline of healthcare, handling critical patient cases 24/7. However, inefficiencies in ER management can lead to long wait times, patient dissatisfaction, and resource constraints. To improve operational efficiency and patient experience, I developed a **Hospital Emergency Room Analysis Dashboard** in **Power BI** that enables data-driven decision-making for hospital administrators.

This dashboard provides real-time insights into:
- Patient visits
- Wait times
- Satisfaction scores
- Referrals
- Demographic trends

The **raw dataset** used for this analysis can be found [here](https://github.com/sachinbasyal/Hospital-ER-Visit-Data-Analytics/blob/main/Hospital-ER%20Dataset.csv). <p>
The **targeted SQL queries** used for analysis and validation can be found [here](https://github.com/sachinbasyal/Hospital-ER-Visit-Data-Analytics/blob/main/SQL%20Queries.pdf).

## Executive Summary
This project focuses on analyzing emergency room patient data to optimize hospital performance and enhance patient care. The dashboard integrates various **Key Performance Indicators (KPIs)** to provide actionable insights into patient flow, waiting times, department referrals, and patient demographics.

### **Key Objectives:**
- Monitor monthly/yearly patient visits to detect seasonal patterns.
- Analyze wait times to identify delays and improve service efficiency.
- Assess patient satisfaction scores to evaluate the quality of care.
- Examine referral trends to allocate hospital resources effectively.
- Understand demographic insights (age, race, gender) to customize healthcare services.

## Tools Used
- **Microsoft Excel**: Data cleaning and preprocessing to ensure accuracy and consistency.
- **MySQL**: Querying and managing the dataset to derive insights.
- **Power BI**: Creating dynamic visualizations, interactive dashboards, and reports.

## Steps Followed
1. Requirement Gathering / Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Layouts
9. Charts Development and Formatting
10. Dashboard / Report Development
11. Insights Generation

## Data Findings & Insights
### **1. Patients Visit Record:**
- Over 9K+ recorded ER visits, with an average of **485 patients per month**.
- **50% of patients** were hospitalized.
- **Peak ER visits** occurred in **August 2020**, while **February 2020** had the lowest visits.
- **Weekends** experienced higher patient traffic, indicating potential **staffing needs**.
- **Seasonal spikes** observed during winter months (flu season).
- **Elderly patients (65+ years)** had the highest ER visits.

### **2. Average Wait Time:**
- **Mean wait time**: **35 minutes**.
- Longer wait times observed during peak seasons (**January–March**).
- **Elderly patients (70+)** and **racial minorities** experienced slightly **longer wait times**.

### **3. Patient Satisfaction Score:**
- **Average score**: **5.47/10**.
- **75% of patients** did not provide a satisfaction rating.
- Lower satisfaction scores correlated with **longer wait times**.
- **Elderly patients (71-80)** reported lower satisfaction scores.

### **4. Patients Referred vs. Walk-ins:**
- **59% of ER patients** were treated directly in the ER, while **41% were referred** to specialized departments.
- **General Practice** and **Orthopedics** received the highest referrals.

### **5. Gender Analysis:**
- **Male (51.1%)** vs **Female (48.7%)** ER visits were evenly distributed.

### **6. Racial Demographics and Age Distribution:**
- Majority of ER visits were from **White (17%)** and **African American (12%)** patients.
- **Patients aged 19-65** accounted for the highest ER visits.

# Report Snapshot (Power BI DESKTOP)
![Dashboard_upload](https://github.com/sachinbasyal/Hospital-ER-Visit-Data-Analytics/blob/main/Power%20BI%20Dashboard%20%26%20Report/Dashboard.png)

## Recommendations
Based on the findings, the following recommendations are proposed to enhance ER operations and patient satisfaction:

- **Reduce peak-time congestion** by improving triage efficiency and scheduling additional staff.
- **Increase specialist availability** in high-referral departments (**General Practice & Orthopedics**).
- **Address disparities** in satisfaction scores across racial and older age groups (**71-80**).
- **Improve wait-time management** with self-check-in kiosks to reduce delays.
- **Leverage predictive analytics** to anticipate high-traffic periods and adjust staffing.
- **Provide clearer communication** about expected wait times to manage patient expectations.
- **Deploy real-time patient feedback mechanisms** to address concerns proactively.
- **Partner with local communities** to promote preventive care and reduce avoidable ER visits.

---
### 📌 **Contributions & Feedback**
If you have any suggestions or want to contribute, feel free to open a **pull request**!

### 📧 Contact: [sachinbasyal@gmail.com]
---

