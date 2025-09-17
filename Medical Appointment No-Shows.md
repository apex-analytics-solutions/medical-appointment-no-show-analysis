# Medical Appointment No-Shows: A Data-Driven Approach

## 📝 Project Summary

This project aims to provide an in-depth analysis of patient appointment no-shows in Brazil. Using various data science techniques, we explore the key factors contributing to this issue and build a machine learning model to predict which patients are likely to miss their appointments.

## 📊 Exploratory Data Analysis (EDA) & Visualization

Our analysis revealed several key findings, which are visually represented in a comprehensive dashboard.

### Key Findings:
* **Overall No-show Rate:** Approximately **20.19%** of patients did not show up for their appointments.
* **Gender Impact:** There is a slight difference in no-show rates between males and females, with both hovering around **20%**.
* **Age Impact:** The highest no-show rates were observed in the age groups of 19-30 and 31-45 years.
* **Long Wait Times:** The most significant finding was the impact of appointment wait times. Patients who waited **30 days or more** had a no-show rate more than double that of those who waited less (**~45%** vs. **~20%**). This suggests long wait times are a major factor.

## 🤖 Modeling and Prediction

We used a **Logistic Regression** model to predict patient no-shows. The initial model performed poorly due to **imbalanced data** (a large number of patients who showed up versus a small number of no-shows). To address this, we used the **SMOTE** technique.

### Model Performance Improvement:
* **Initial Model:** The model's ability to correctly identify no-shows (`recall`) was only **8%**.
* **Improved Model (with SMOTE):** The `recall` for no-shows significantly improved to **52%**, demonstrating the effectiveness of the SMOTE technique in handling imbalanced data.

## 💡 Recommendations

Based on our analysis and predictive modeling, we propose the following recommendations:
1.  **Improve Reminder System:** Instead of sending an SMS reminder just one day before the appointment, consider sending it two days prior or making a personal phone call.
2.  **Reduce Wait Times:** Given the strong correlation between long wait times and no-shows, a key strategy is to reduce appointment scheduling delays.

## 🤝 Contribution

This project demonstrates my proficiency in the data science pipeline, from data cleaning and analysis to modeling and evaluation. The complete code and analysis can be viewed in the accompanying Jupyter Notebook.