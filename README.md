# HR Executive Attrition & Employee Performance Dashboard

## 📌 Project Overview
This Human Resources dashboard analyzes workforce demographics and employee turnover (attrition) patterns. It assists HR executives in identifying risk factors that lead to staff resignations and evaluating department-level performance distribution.

## 🛠️ Tech Stack & Skills
*   **BI Tool:** Power BI Desktop
*   **Data Source:** HR Data Matrix
*   **Languages:** DAX
*   **Key Concepts:** Workforce Demographics, Attrition Rate Tracking, Employee Segmentation.

## 📈 Key Metrics & DAX Measures Used
1.  **Total Employees:** `COUNT(HRData[EmployeeID])` - Monitors active headcount.
2.  **Attrition Count:** `CALCULATE(COUNT(HRData[EmployeeID]), HRData[Attrition] = "Yes")` - Isolates the exact number of employees who left the company.

## 💡 Key Business Insights
*   Provides clear visibility into turnover metrics, indicating which roles or departments suffer from the highest attrition.
*   Gender and Role-based visualizations help HR build better retention and diversity strategies.
# HR-Executive-Attrition-Dashboard
