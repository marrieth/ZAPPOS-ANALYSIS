# ZAPPOS EMPLOYEE WELLNESS PROGRAM ANALYSIS

### PROJECT OVERVIEW

This project the company wants to assess the impact and effectiveness of its employee wellness program to make informed decisions regarding program improvement  and resources.



![IMG_2672](https://github.com/marrieth/ZAPPOS-ANALYSIS/assets/138234128/98505de7-9876-4524-89e4-990f67745537)

### DATA SOURCE

Employee Wellness Program data used for this analysis is the employee_wellness_data.csv file,containing detailed record about the employee wellness program made by Zappos.

### TOOLS 

- Power BI - Data Analysis
- Power BI - Data Visualization

### DATA CLEANING/PREPARATION

- Exraction, Transform and Load (ETL)
- Formatted the Data
- Create the Fact and Dimension Tables
- Create Relationship(Data Modelling)

### EXPLORATORY DATA ANALYSIS

The exploratory data analysis involved in the employee wellness program data to answer key questions are as follows:
- Evaluate the overall participation rate in the wellness program.
- Analyze feedback sentiment to understand employee perceptions
- Identify areas of improvement in the current wellness program.
- Provide actionable insights to enhance the effectiveness of the program.

### DATA ANALYSIS

Involving some code/features work:

``` Power BI

"year",YEAR([Date]),
"Quarter","Q" & Quarter([Date]),
"Month_Name", FORMAT([Date],"MMM")

```

### RESULTS AND FINDINGS

1. The column chart shows that Engineering and Finance department has the highest total rating of 211 while sales had 183.
2. The average participation rating by wellness program shows an average of 3.00 with stress management been the highest of 3.04.
3. The line graph  show the month of October with the highest  no. of feedback sentiment of 98 while February is the lowest with 68.
4. The bar chart shows the count of age 45 participation rate of 39 while age 33 with the lowest participation rate of 13.
5. This table shows the feedback comment , with majority  majority encouraging with 799 comment while 201 comment did not support the wellness program.
6. The wellness program with the highest negative feedback sentiment is mental health with 24.19% while the wellness program with the highest positive comment is fitness and stress management with 22.88% and 22.08% respectively.


### RECOMMENDATION

- I recommend that the wellness program should continue with more focus on the fitness and stress management.
- I also recommend that improvement should be made for the mental health program to reduce the negative feedback sentiment because the mental health of their employee is very important.


















