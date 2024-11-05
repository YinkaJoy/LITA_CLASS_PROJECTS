# LITA_CLASS_ACTIVITIES
This is where I will document my class activities on Data Analysis with Incubator Hub.

### Project Title: Incubator Hub HR Data Analysis
---

### Project Outline
---

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Recommendations](#recommendations)

[Conclusion](#conclusion)



### Project Overview
---
The aim of this project is to analyze the attrition rate of employee of a company based on their age, gender, marital status, Job description. The analysis includes deriving various objectives to understand the underlying issues and to propose actionable recommendations.

### Data Sources
---
The primary source of Data used is the Human Resource data provided by the company. The data was provided in CSV format, making it accessible for analysis.

### Tools Used
---
- Microsoft Excel [Download Here](https://1drv.ms/x/c/aad348901d0848c9/EQCZIc0H2NFAruPR4Hg0-mQBb5vRzleIwA5A2ZFT6eYsYg)
  1. For Data cleaning
  2. For Analysis.
- SQL - Structured Query Language for querying of Data
- PBI - Microsoft PowerBI for visualization.
- GitHub for portfolio building.

### Data Cleaning and Preparation
---
  1. Data loading and Inspection
  2. Removed duplicates
  3. Data Cleaning and Formatting

### Exploratory Data Analysis
---
 In exploring data for effective analysis, the following questions were asked;
 - What is the total number of employee?
 - What is the number of attrition?
 - How many current employee do the company have?
 - What department have the highest attrition rate?
 - What gender have the highest attrition?
   
### Data Analysis
---
Included are some basic lines of code or queries or even some of the DAX expressions that were used during my analysis;  

```SQL
SELECT *FROM [dbo].[employee]
select count(employeeno) from [dbo].[employee]
group by gender;
```

```SQL
SELECT *FROM [dbo].[employee]
select count(employeeno), department from employee
group by department
```

### Data Visualization
---
![HR DASH BOARD](https://github.com/user-attachments/assets/09e057a0-19b5-4ca0-8758-9edab931f965)

As illustrated in the figure above, out of a total of 1470 employees, an attrition rate of 16% was recorded that is about 237 employees left the company. Based on our analysis, the highest attrition rate in 
gender is the male.
The data show about 63% of employee that left the company are male. Factors responsible for this could be any of the following;
 - Low income rate
 - Lack of job satisfaction
 - Poor work life balance 
     







![JOB AND EDUCATIONAL FIELD](https://github.com/user-attachments/assets/d661652b-5d61-4424-ab59-31b2127f7570)

