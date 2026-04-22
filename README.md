# HR_Dashboard
An interactive dashboard in Human Resource dataset to EDA, analyze, and make informed decisions.
![HR project cover page](1.JPG)

# Project Background
A fictional company, a dataset I received from Starttrain's challenge in Q1.2026, contains employee information and their performance of each department. This project thoroughly analyzes and synthesizes this data in order to uncover critical insights that will improve people management's success. 

Insights and recommendations are provided on the following key areas:

- **Attrition rate Trend Analysis** : Evaluation of historical **attrition rate** patterns, both overvall company and each department, focusing on Attrition rate, Attrition Voluntary rate, Early Attrition rate, and Tenure Attrition rate.  
- **Demographic Attrition Analysis** : An analysis of employee group's personal aspects, understanding the employee persona who already quit job.
- **Culture Working Analysis** : An evaluation of working environmental health on **satisfaction factors, promotion years, and worklife balance**
- **Depart Performance Analysis** : An assessment benefits of each department on **average salary, average promotion year, and time spend with managers**

# Data Structure & Initial Checks

The companies main database structure as seen below consists of fifteen tables, with one fact table is Employee, and the others are dimensional tables, with a total row count of 1470 employee records. A description of each table is as follows:

**Fact table**
Employees (ID employee, age, attribute, attrition, attritionRiskIndex, businessTravel, dateBirth, dateDeparture, dateStart, dateToday, department, distanceFromHome, Education, EmploymentType, EnvironmentSatisfaction, gender, hireType, jobLevel, jobRole, jobInvolvement, jobSatisfaction, maritalStatus, numCompaniesWorked, overTime, performanceRating, relationshipSatisfaction, salary, salaryHike, stockOption, terminationType, totalWorkingYears, trainingTimeLastYear, value, workLifeBalance, yearsAtCompany, yearsSinceLastPromotion, yearsWithCurrManager)

**Dimensional table**
1. BusinessTravel (ID, businessTravel)
2. Department (ID, department)
3. HireType (ID, hireType)
4. Gender (ID, gender)
5. EnvironmentSatisfaction (ID, environmentSatisfaction)
6. RelationshipSatisfaction (ID, relationshipSatisfaction)
7. JobRole (ID, jobRole)
8. TerminationType (ID, terminationType)
9. Education (ID, education)
10. Performance (ID, performance)
11. JobInvolvement (ID, involvement)
12. EmploymentType (ID, employmentType)
13. JobSatisfaction (ID, jobSatisfaction)
14. Calendar (Date)

![Metadata](2.JPG)

# Executive Summary

### Overview of Findings
![AttritionPiechart](AttritionPieChart.JPG)

**In 16.12% attrition rate, Voluntary occupied 75.95% (From 1985 to 2022 years working starting overall)**

![AttritionVoluntaryLinechart](AttritionVoluntaryLinechart.JPG)

From 2009 onward, the voluntary attrition rate have a ziczac shape impacting on the consistent quality workload of the company resulting on the ineffective management in the future. But we also concern about the effect of the recession of 2009, a lasting negative event, cutting off employee from the company structure. 

![TenureAttritionYoungAge](tenureyoungage.JPG)

The tenure employee of the attrition is younger (0-2) years intensely from the employee starting working in [2018-2022], who was born in 2000-2004, mainly responsible for entry, associate, and specialist job level title.


This chart show the % attrition rate of the total only Gen-Z. The attrition rate of Gen-Z ranges from 23% to 60%, and the highest from the HR.

# Insights Deep Dive
### Category 1:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 1]


### Category 2:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


### Category 3:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Category 4:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
