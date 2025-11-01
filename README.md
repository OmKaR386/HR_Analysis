# 📊 HR Analytics Project: Employee Attrition Dashboard

This repository contains the files for a comprehensive **HR Analytics Data Project** focused on understanding and visualizing the factors contributing to employee **attrition**. The final deliverable is an interactive dashboard built in **Power BI**.

***

## 🎯 Project Goal

The primary objective of this project is to analyze the organizational Human Resources data to:

1.  Identify the **key drivers** of employee attrition.
2.  Visualize attrition trends across various demographics (e.g., age, gender, marital status) and work-related factors (e.g., job role, income, years at company).
3.  Provide actionable insights and recommendations to the HR department to improve employee retention and satisfaction.

***

## 🛠️ Tools and Technologies

| Category | Tool/Technology | Usage |
| :--- | :--- | :--- |
| **Data Source** | `HR_Analytics.csv` | [cite_start]The raw dataset used for analysis. [cite: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19] |
| **Visualization & Analysis** | **Microsoft Power BI** | Used to clean, model the data, and create the interactive HR Analytics Dashboard. |
| **Version Control** | **Git/GitHub** | Used for project management and collaboration. |

***

## 📁 Repository Structure

* [cite_start]`HR_Analytics.csv`: The core dataset containing employee information. [cite: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19]
* `hr analysis.pbix`: The Power BI Desktop file containing the data model, transformations, DAX measures, and the final dashboard visualization.
* `README.md`: This project documentation file.

***

## 📑 Dataset Description

The dataset, `HR_Analytics.csv`, contains various features related to employees, which are critical for an in-depth attrition analysis. [cite_start]Key columns include: [cite: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19]

| Column Name | Description |
| :--- | :--- |
| **Attrition** | Target variable indicating if the employee left (Yes/No). |
| **Department** | The business unit (e.g., Research & Development, Sales). |
| **JobRole** | The specific role of the employee (e.g., Sales Representative, Laboratory Technician). |
| **MonthlyIncome** | Employee's monthly salary. |
| **TotalWorkingYears** | Total years the employee has worked. |
| **YearsAtCompany** | Number of years spent at the current company. |
| **EnvironmentSatisfaction** | Level of employee satisfaction with their environment (e.g., 1-4). |
| **OverTime** | Whether the employee works overtime (Yes/No). |
| **MaritalStatus** | Marital status (Single, Married, Divorced). |

***

## 💡 Potential Key Findings (Example)

* **Income Disparity:** Employees in certain Job Roles or Departments with below-average **Monthly Income** have a significantly higher attrition rate.
* **Job & Environment Satisfaction:** Low ratings in **EnvironmentSatisfaction** or **JobSatisfaction** correlate strongly with increased attrition.
* **Overtime:** Employees who regularly work **OverTime** show a higher likelihood of leaving the company.
* [cite_start]**Tenure:** New employees (low **YearsAtCompany**) and employees in the **18-25 AgeGroup** have the highest churn rates. [cite: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19]

***

## 🖼️ Dashboard Preview


***

## 🚀 How to View the Dashboard

1.  **Install Power BI Desktop:** Ensure you have Microsoft Power BI Desktop installed on your machine.
2.  **Clone the Repository:** Download or clone this GitHub repository to your local machine.
3.  **Open the File:** Double-click the `hr analysis.pbix` file. Power BI Desktop will open and load the interactive dashboard, data model, and report pages.
4.  **Explore:** Interact with the slicers and visuals to explore attrition trends and gain insights.
