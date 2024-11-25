### STUDENT-DATA
This is my personal project that i worked on to showcase all that i have learnt in the process of learning Data Analysis from Skill Harvest Academy
## INTRODUCTION/OVERVIEW
The Student Performance-BD dataset contains information on the academic performance of students from various regions. It features 24 attributes related to demographics, academic metrics, extracurricular activities, and other relevant factors. The data can be used to analyze student performance, explore factors affecting academic outcomes, and provide insights to help students choose suitable educational paths. student performance can be evcaluated based on several that affects student performance factors such as; location, parental involvement, internet access, guardian, study time, tutoring, school types, attendance, extra curicular etc.```
## TOOLS USED
•	Ms Excel Download Here (http//www.excel.com) 
* https://www.kaggle.com/datasets/satayjit/student-performance-bd

•	Power BI Download Here (http//www.PowerBi.com) ```

## DATA CLEANING AND PREPARATION
In the process of data cleaning and preparation i performed the following actions
1.	data loading
2.	Removing unnecessary column
3.	Data cleaning and formating
4.	creating addition measure by adding conditional column on the data model 5.Data cleaning and transformation are critical steps in preparing raw data for analysis. In Power BI, we used Power Query to apply various transformations, ensuring that the data was consistent, accurate, and ready for analysis. Key transformations we applied included; using PROPER function to make the names of the student written in proper case using Excel function
5.	=PROPER(B2)
## DATA USED
The primary source of the data is gotten from ms excel and this an open source data that can easily be downloaded from an open source online
https://www.kaggle.com/datasets/satayjit/student-performance-bd

## DATA ANALYSIS
In the cause of the analysis, In summary, data analysis of open-source information is a powerful tool that can facilitate knowledge, promote transparency, and encourage shared progress. By engaging with these datasets. In analysising the data we able to deduce the following using excel functions
AVERAGE SCORE	370.7741523 =AVERAGE(Z2:Z8613)
HIGHEST SCORE	489 =MAX(Z2:Z8613)
LOWEST SCORE	220 =MIN(Z2:Z8613)
TOTAL NUMBER OF STUDENTS	8612 =COUNTA(B2:B8613)
NUMBER OF STUDENTS IN PRIVATE 	2394 =COUNTIF(P2:P8613,P2)
NUMBER OF STUDENTS IN  SEMI GOVT 	3067 =COUNTIF(P2:P8613,P3)
NUMBER OF STUDENTS IN GOVT	3151 =COUNTIF(P2:P8613,P4)
SCIENCE STUDENT WITH THE HIGHESTBSCORE	489 =MAXIFS(Z2:Z8613,X2:X8613,X2)
ARTS STUDENT WITH THE HIGHEST SCORE	434 = MAXIFS(Z2:Z8613,X2:X8613,X12)
COMMERCE STUDENT WITH THE HIGHEST SCORE	416 =MAXIFS(Z2:Z8613,X2:X8613,X3)
Students Total Score =SUM(S2,T2,U2,V2,W2,)
![image](https://github.com/user-attachments/assets/57fb07b5-db3a-47b6-8d3c-eff120276f42)


## EXPLORATORY DATA (EDA)
a data analysis method that uses visual displays and statistical tools to explore data sets for patterns, relationships, and anomalies. The goal of EDA is to learn about the data, rather than to confirm a hypothesis. EDA is an iterative process that involves: Data collection and cleaning Visualizing data Identifying patterns and anomalies Generating hypotheses EDA involved the exploring of the data with visualisation on Power BI to answer some questions about the data such as;The data can be used to analyze student performance, explore factors affecting academic outcomes, and provide insights to help students choose suitable educational paths. student performance can be evcaluated based on several that affects student performance factors such as; location, parental involvement, internet access, guardian, study time, tutoring, school types, attendance, extra curicular etc.

## KEY INSIGHT/INFERENCE
The dataset is intended for use in educational research, machine learning projects, and statistical analysis to identify trends and actionable insights for improving student success. THrough visualisation of data of Power BI excel function i have deduce
i. student total score by gender
ii. student  total score by location
iii. students total
iv. Top 5 students by location and total score
v. student performance by parental involvement
vi. count of science student
vii. sum of total score by student group
viii. sum of student performance by internet access and gender
ix
student performance rate by study time
```
## CONCLUSION
The dataset is useful in educational research, machine learning projects, and statistical analysis to identify trends and actionable insights for improving student performance success
we can deduce that with adequate study time, parental involvement and tutoring a student tends to have a better performance.student with internet access performance better to those without internet access. Male student perform better than female students.•	Assisting to identify the best-fit academic group (Science, Commerce, Arts) for students based on their performance.

