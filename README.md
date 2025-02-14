# HR Analysis Report
**Understanding Employee Attrition, Demographics, and Compensation Trends**

# Introduction & Background

This analysis aims to examine employee behavior, attrition trends, and key factors influencing performance and retention. By gaining insights into workforce demographics, income distribution, and promotion patterns, HR stakeholders can develop more effective strategies to enhance employee satisfaction and work-life balance. Additionally, this project highlights my expertise in data analysis, visualization, and DAX-based data modeling.


# Key Objectives:

This dashboard aims to answer the following key stakeholder questions:

- What is the total number of employees?
- What is the gender breakdown of employees? Are they increasing or decreasing?
- How many employees are there in each job role and age group?
- What is the distribution of employees by job satisfaction level?
- How many employees are there at each job level?
- What is the average performance rating of employees, broken down by age and gender?
- What is the relationship between employee rating and marital status?
- What is the overall attrition rate?
- What is the attrition rate for males vs. females?
- How does attrition vary by education level and marital status?
- What is the attrition rate for each job level?
- How does the attrition rate vary by job role and work-life balance?
- What is the average number of years employees stay with the company, broken down by gender and age?
- What is the average salary for men and women?
- How do the average number of promotions and total number of employees vary by gender and company age?





# Data Source & Methodology

**Data Source**
The dataset was sourced from Kaggle.com and imported into Power BI for analysis.

**Data Cleaning & Transformation**

- Merged two CSV files ("test.csv" and "train.csv") using the folder.files M query function.
- Removed redundant columns and replaced attrition column values with binary encoding (1 = Yes, 0 = No).
- Created an age group classification for better categorical analysis.
- Used data profiling tools to detect and correct anomalies.
- Standardized data types for consistency and readability.

**Data Model**

The dataset follows a flat file schema, simplifying the analysis by eliminating the need for additional dimensional references.


**Analysis Approach**

- Created complex measures using DAX (Data Analysis Expressions) to derive insights.

  
# Dashboard Features & Key Performance Indicators (KPIs)

**Demographic Insights**

- Total Employees
- Male Count & Percentage
- Female Count & Percentage
  
**Attrition Analysis**

- Overall Attrition Rate
- Male vs. Female Attrition Rate

**Income & Promotions**

- Highest Salary (Men & Women)
- Average Salary (Men & Women)
- Total Promotions


**Visualizations**

- Line Graph – Trends in performance ratings and total employees by age and gender.
- Column Chart – Employee distribution by performance rating and marital status.
- Pie Chart – Job level distribution of employees.
- Bar Chart – Job satisfaction score comparison.
- Scatter Plot – Attrition rate and average tenure distribution by age and gender.
- Treemap – Monthly income distribution by job role.
- Line & Column Chart – Salary trends and promotions by job role.


# Conclusion & Recommendations

**Summary:**

**Demographic Insights**

- The total workforce consists of **54,000 employees**, with **57.86% male** and **45.14% female.**
- **Twenty-seven thousand employees** reported **"High"** job satisfaction, while **11,000** rated **"Very High,"** **11,000 rated "Medium,"** and **5,000** rated **"Low."**
- Married employees achieved the highest performance ratings compared to single and divorced employees.

**Attrition Trends**

- The overall attrition rate is **47.05%,** with males at **43.05%** and females at **53.05%.**
- Entry-level positions have the highest attrition rate **(63.51%),** while senior-level jobs show a significantly lower rate **(20.38%).**
- Single employees exhibit a higher attrition rate than their married or divorced counterparts.
- Attrition rates decrease as employees reach their **30s and beyond,** indicating longer retention with age.


**Income & Promotions**

- The highest salary for men is **$16,149,** while for women, it is **$15,552.**
- The **average salary** for men and women is nearly identical **($7,304 vs. $7,300).**
- Most promotions occur among employees with **average performance ratings (27,000 employees promoted).**
- Companies aged **10–100 years** report an average of **1 promotion per 400 employees.**

**Recommendations:**

- **Addressing High Attrition Rates**
  - Single employees show the highest attrition despite strong performance ratings. To reduce attrition, conducting exit interviews and employee satisfaction surveys can help identify key factors driving turnover. Additionally, implementing mentorship programs or flexible work policies may improve retention among single employees.

- **Reducing Female Attrition**
  - The female attrition rate is significantly higher than that of male employees despite relatively equal average salaries. This indicates potential gaps in career progression, support systems, or workplace inclusivity. A deeper analysis of factors like career growth opportunities, leadership representation, work-life balance effectiveness, and employee engagement scores can provide actionable insights. Introducing initiatives such as leadership development programs for women, structured mentorship, and flexible career paths can help mitigate this issue.

- **Enhancing Revenue from Promotions & Salary Equity**
  - With entry-level employees making up the majority of attrition cases (63.51%), it's crucial to understand the challenges they face. A structured onboarding program, enhanced career development tracks, and early engagement strategies can improve retention. Analyzing the first-year turnover reasons and implementing tailored retention programs—such as skill development training, role clarity sessions, and performance-based incentives—could reduce early-stage attrition.


# Dashboard

![image](https://github.com/user-attachments/assets/acbfc0fb-cbb8-41c7-816f-1bbf93d7851d)

![image](https://github.com/user-attachments/assets/c99ca4a8-7c15-496b-9202-2f002d28ad3c)

![image](https://github.com/user-attachments/assets/73df4781-663a-4929-9ed9-6008229a8269)





