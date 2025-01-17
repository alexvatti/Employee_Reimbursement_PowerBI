# Employee Reimbursement Power BI

![Employee Reimbursement](https://github.com/alexvatti/Employee_Reimbursement_PowerBI/blob/main/Capture.png)

## Problem Statement

1. Import the data and open the Power Query
2. The expense type column has some spelling and punctuation errors, correct them
3. Project names are not uniform, make it uniform.
4. The Currency column has some missing values, based on the amount, create a new custom column.
   
Condition: amount >= 1000, = INR; amount < 1000, = USD; else = EURO

Formula: (if [Currency] = null and [Amount] >= 1000 then "INR" else if [Currency] = null and [Amount] < 1000 then "USD" else [Currency] )

5. Normalize the amount column into INR based on the currency column.
6. Create a measure to calculate the sum of reimbursed amount in INR.
7. Use the calculate function and check the total reimbursed amount for Project_B
8. Create a measure to check the count of declined requests.
9. Create a slicer visual for the Project and employee
10. Create a bar chart for employees and reimbursement amount.
11. Create a pie chart for Project vs reimbursement amount

### Steps Followed

## Data Cleaning
Meticulously handled null values, corrected spelling and punctuation errors, and standardized project names. Ensured  dataset ready for analysis!

## Data Transformation
Implemented a custom rule to fill missing currency values, converted USD & EURO to INR, and crafted a dynamic measure to calculate total reimbursed amounts. 
Delved deeper to derive insights on Project_B and tracked declined requests.

## Dashboard Creation
Crafted an interactive experience with a slicer visual for projects and employees. 
Visualized employee reimbursement amounts through a compelling bar chart and presented a clear overview of project vs. reimbursement amounts with a pie chart.

