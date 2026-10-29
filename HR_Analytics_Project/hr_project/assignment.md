#### HR Analytics - Boosting Retention with Data Insights at Adecco India

### Background:

Adecco India is a medium-sized technology company specializing in software development. It has a diverse workforce spread across various departments, including engineering, marketing, sales, and customer support. Recently, Adecco India has observed an increase in employee turnover, especially among junior-level employees, which is concerning for the management. The company is committed to understanding the factors influencing employee attrition and job satisfaction to develop strategies for improving employee engagement and retention.

**Scenario:**
Adecco India is facing a high attrition rate, particularly in the sales department among junior-level employees. The management is worried about the potential impact on productivity and the costs associated with hiring and training new employees. As a data analyst, you are tasked with analyzing the HR data to uncover insights that can help in reducing the attrition rate. Your analysis will inform strategic decisions aimed at enhancing employee satisfaction and retention.

**Problem Statement**

- **What is the problem?**

Adecco India is experiencing high employee turnover, particularly in the sales department among junior-level employees. This turnover is costly and disrupts team dynamics, leading to decreased productivity and morale.

- **Why is it important to solve it?**

High attrition rates can lead to significant costs associated with recruitment, onboarding, and training of new employees. It also affects the company's ability to maintain consistent performance and achieve long-term goals. Improving employee retention will enhance productivity, reduce costs, and foster a more stable and motivated workforce.

### Stakeholders

**Types of Stakeholders:**

- Internal Stakeholders:
  - HR Department
  - Sales Department
  - Engineering Department
  - Marketing Department
  - Customer Support Department
  - Senior Management
- External Stakeholders:
  - Recruitment Agencies
  - Training Providers





**Problem Definition According to the Scenario Created:**
Adecco India needs to identify and address the factors contributing to high attrition rates among its junior sales employees. The company aims to develop targeted strategies to improve employee engagement, satisfaction, and retention.
Data Requirements:
To conduct HR analytics, the following data sources can be utilized:

- HRIS (Human Resource Information System): Employee demographic information, employment history, and compensation details.
- Performance Management System: Employee performance ratings, goals, and achievements.
- Employee Surveys: Feedback on job satisfaction, work-life balance, and engagement.
- Exit Interviews: Reasons for employee departures and feedback on their experiences.

Metric Development:

- Attrition Rate: Percentage of employees leaving the company within a specified period.
- Job Satisfaction Score: Average score from employee surveys on job satisfaction.
- Engagement Score: Average score from employee surveys on employee engagement.
- Performance Ratings: Average performance rating of employees.
- Tenure: Average length of employment of employees.

Insights & Actions:

- Targeted Analysis: Analyze historical data to understand factors contributing to employee attrition, such as department, job level, salary, tenure, performance ratings, and employee demographics.
- Actionable Insights: Derive actionable insights from the analysis results to develop targeted strategies for improving employee retention, job satisfaction, and performance.

Communication:

- Final Conclusion: Present the findings and recommendations to the senior management and HR department to inform strategic decisions.

### Dataset:

[https://www.kaggle.com/datasets/bhanupratapbiswas/hr-analytics-case-study	](https://www.kaggle.com/datasets/bhanupratapbiswas/hr-analytics-case-study)

### Data Dictionary

| Column                   | Description                                                      |
| ------------------------ | ---------------------------------------------------------------- |
| Age                      | Age of the employee                                              |
| Attrition                | Whether the employee has left the company (Yes/No)               |
| BusinessTravel           | Frequency of business travel                                     |
| DailyRate                | Daily salary rate of the employee                                |
| Department               | Department in which the employee works                           |
| DistanceFromHome         | Distance of the employee's home from the workplace               |
| Education                | Education level of the employee (1-5 scale)                      |
| EducationField           | Field of education                                               |
| EmployeeCount            | Always 1 (as the data is individual-specific)                    |
| EmployeeNumber           | Unique identifier for each employee                              |
| EnvironmentSatisfaction  | Employee's satisfaction with the work environment (1-4 scale)    |
| Gender                   | Gender of the employee                                           |
| HourlyRate               | Hourly salary rate of the employee                               |
| JobInvolvement           | Employee's involvement in their job (1-4 scale)                  |
| JobLevel                 | Job level of the employee (1-5 scale)                            |
| JobRole                  | Role of the employee within the company                          |
| JobSatisfaction          | Employee's satisfaction with their job (1-4 scale)               |
| MaritalStatus            | Marital status of the employee                                   |
| MonthlyIncome            | Monthly salary of the employee                                   |
| MonthlyRate              | Monthly rate of the employee                                     |
| NumCompaniesWorked       | Number of companies the employee has worked for                  |
| Over18                   | Whether the employee is over 18 years old                        |
| OverTime                 | Whether the employee works overtime (Yes/No)                     |
| PercentSalaryHike        | Percentage increase in salary                                    |
| PerformanceRating        | Performance rating of the employee (1-4 scale)                   |
| RelationshipSatisfaction | Employee's satisfaction with relationships at work (1-4 scale)   |
| StandardHours            | Standard working hours (80 for all employees)                    |
| StockOptionLevel         | Stock option level of the employee (0-3 scale)                   |
| TotalWorkingYears        | Total number of years the employee has worked                    |
| TrainingTimesLastYear    | Number of training sessions attended by the employee last year   |
| WorkLifeBalance          | Employee's work-life balance (1-4 scale)                         |
| YearsAtCompany           | Number of years the employee has been with the company           |
| YearsInCurrentRole       | Number of years the employee has been in their current role      |
| YearsSinceLastPromotion  | Number of years since the employee's last promotion              |
| YearsWithCurrManager     | Number of years the employee has been with their current manager |

### Basic-Level Questions (Excel-Oriented)

1. What is the overall attrition rate at Adecco India?
   - Hint:
     1. Use the COUNTIF function to count the number of employees who left the company (Attrition = "Yes").
     2. Use the COUNTA function to count the total number of employees.
     3. Calculate the attrition rate using the formula:
     4. Attrition Rate=Number of Employees Who LeftTotal Number of Employees×100
     5. Attrition Rate=
     6. Total Number of Employees
     7. Number of Employees Who Left
     8. ​
     9. ×100
   - How it helps: Understanding the overall attrition rate gives a high-level view of employee retention and helps in benchmarking against industry standards.
2. Which department has the highest attrition rate?
   - Hint:
     1. Use a PivotTable to group data by Department and Attrition.
     2. Add a calculated field to calculate the attrition rate for each department.
   - How it helps: Identifying departments with high attrition rates allows the company to focus retention efforts where they are most needed, potentially uncovering department-specific issues.
3. What is the average age of employees who have left the company?
   - Hint:
     1. Filter the data to show only employees who left (Attrition = "Yes").
     2. Use the AVERAGE function to calculate the average age of these employees.
   - How it helps: Knowing the age demographics of those leaving can inform targeted retention strategies, such as tailored benefits or career development programs.
4. How does job satisfaction vary across different job roles?
   - Hint:
     1. Use a PivotTable to group data by JobRole and calculate the average JobSatisfaction score.
   - How it helps: Understanding job satisfaction across roles helps in identifying specific roles that may need attention to improve employee morale and retention.
5. Is there a significant difference in attrition rates between male and female employees?
   - Hint:
     1. Use a PivotTable to group data by Gender and Attrition.
     2. Add a calculated field to calculate the attrition rate for each gender.
     3. Optionally, perform a t-test in Excel to check for statistical significance.
   - How it helps: Identifying gender-based differences in attrition rates can help in developing gender-specific retention strategies and ensuring workplace equality.
6. What is the average monthly income of employees who have left the company?
   - Hint:
     1. Filter the data to show only employees who left (Attrition = "Yes").
     2. Use the AVERAGE function to calculate the average monthly income of these employees.
   - How it helps: Analyzing the income levels of those who leave can highlight potential salary-related issues and guide compensation strategies.
7. How does distance from home impact employee attrition?
   - Hint:
     1. Create a scatter plot with DistanceFromHome on the x-axis and Attrition (Yes/No) on the y-axis.
     2. Use the TRENDLINE feature to visualize the relationship.
   - How it helps: Understanding the impact of commute distance on attrition can lead to initiatives like remote work options or relocation assistance.
8. What is the distribution of performance ratings among employees?
   - Hint:
     1. Use a PivotTable to group data by PerformanceRating.
     2. Create a histogram or bar chart to visualize the distribution.
   - How it helps: Visualizing performance ratings helps in assessing overall employee performance and identifying areas for improvement in performance management systems.
9. How many employees work overtime regularly?
   - Hint:
     1. Use the COUNTIF function to count the number of employees who have 'Yes' for the OverTime variable.
   - How it helps: Understanding overtime trends can highlight potential work-life balance issues and guide workload management.
10. What is the average number of years employees have worked at Adecco India?
    - Hint:
      1. Use the AVERAGE function on the YearsAtCompany column.
    - How it helps: Knowing the average tenure helps in understanding employee loyalty and can inform strategies for increasing long-term retention.





### Medium-Level Questions (Excel-Oriented)

1. What are the top three factors contributing to employee attrition at Adecco India?
   - Hint:
     1. Use the CORREL function to calculate correlation coefficients between Attrition and various factors (e.g., Age, MonthlyIncome, YearsAtCompany).
     2. Identify the top three factors with the highest absolute correlation values.
   - How it helps: Identifying key factors contributing to attrition helps in focusing on the most impactful areas for intervention and developing targeted retention strategies.
2. How does the attrition rate vary with different levels of job involvement?
   - Hint:
     1. Use a PivotTable to group data by JobInvolvement and Attrition.
     2. Add a calculated field to calculate the attrition rate for each job involvement level.
   - How it helps: Understanding the relationship between job involvement and attrition can inform initiatives to increase employee engagement and reduce turnover.
3. Is there a relationship between employee age and job satisfaction?
   - Hint:
     1. Create a scatter plot with Age on the x-axis and JobSatisfaction on the y-axis.
     2. Use the TRENDLINE feature to visualize the relationship.
   - How it helps: Analyzing the relationship between age and job satisfaction can guide age-specific programs to enhance job satisfaction and retention.
4. How does marital status impact employee attrition?
   - Hint:
     1. Use a PivotTable to group data by MaritalStatus and Attrition.
     2. Add a calculated field to calculate the attrition rate for each marital status.
   - How it helps: Understanding the impact of marital status on attrition can inform tailored retention strategies to address the needs of different marital groups.
5. What is the impact of training on employee attrition?
   - Hint:
     1. Use a PivotTable to group data by TrainingTimesLastYear and Attrition.
     2. Add a calculated field to calculate the attrition rate for different training levels.
   - How it helps: Analyzing the impact of training on attrition can highlight the importance of professional development and inform training programs to improve retention.
6. How does work-life balance affect employee performance ratings?
   - Hint:
     1. Create a scatter plot with WorkLifeBalance on the x-axis and PerformanceRating on the y-axis.
     2. Use the TRENDLINE feature to visualize the relationship.
   - How it helps: Understanding the relationship between work-life balance and performance can guide initiatives to enhance work-life balance and improve employee performance.
7. What is the effect of stock options on employee attrition?
   - Hint:
     1. Use a PivotTable to group data by StockOptionLevel and Attrition.
     2. Add a calculated field to calculate the attrition rate for each stock option level.
   - How it helps: Analyzing the impact of stock options on attrition can inform compensation strategies and enhance employee retention through stock-based incentives.
8. How does employee tenure relate to job satisfaction?
   - Hint:
     1. Create a scatter plot with YearsAtCompany on the x-axis and JobSatisfaction on the y-axis.
     2. Use the TRENDLINE feature to visualize the relationship.
   - How it helps: Understanding the relationship between tenure and job satisfaction can guide initiatives to enhance job satisfaction and retain long-term employees.
9. What is the impact of business travel on job satisfaction?
   - Hint:
     1. Use a PivotTable to group data by BusinessTravel and calculate the average JobSatisfaction score for each travel frequency.
   - How it helps: Analyzing the impact of business travel on job satisfaction can inform policies on travel requirements and enhance overall job satisfaction.
10. How do years since last promotion affect employee performance?
    - Hint:
      1. Create a scatter plot with YearsSinceLastPromotion on the x-axis and PerformanceRating on the y-axis.
      2. Use the TRENDLINE feature to visualize the relationship.
    - How it helps: Understanding the impact of promotion frequency on performance can guide promotion policies and improve employee performance through timely career advancements.

### Additional Considerations for Advanced Questions:

- Ethical and Privacy Concerns: While developing predictive models and handling patient data, it's crucial to consider the ethical implications and ensure privacy and data protection standards are met.
- Interdisciplinary Collaboration: Engage with clinical experts, healthcare providers, and patients to validate findings and refine intervention strategies.
- Continuous Improvement: Consider these analyses as part of an ongoing effort to improve healthcare delivery. Regularly update models and strategies based on new data and outcomes.

### Deliverables

- Case Study Document: Includes problem statement, data dictionary, and questions.
- Solution Guide: Detailed answers and explanations for each question.
- Additional Resources: References for further exploration.

### Desired Outcome

The trainees will develop an analytical and logical mindset, understanding the importance of various factors in loan analysis. They will learn to apply different data analysis techniques to uncover insights and make data-driven decisions. ​​