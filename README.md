# Day 1 - Excel Fundamentals

## Topics Learned
- Workbook and Worksheet
- Rows and Columns
- Cells and Ranges
- Basic Data Types
- Data Entry
- Basic Formatting

## Hands-on Practice
Created an Employee Dataset containing:
- Employee ID
- Name
- Department
- Age
- Salary
- Joining Date

## Tools Used
- WPS Spreadsheet

## Learning Goal
Building practical Excel skills for a Data Analyst career.

# Excel Day 2 - Basic Formulas

## Topics Learned
- SUM
- AVERAGE
- MIN
- MAX
- COUNT
- COUNTA
- COUNTBLANK

## Practice
Applied Excel formulas to an employee dataset to calculate salary statistics, employee count, and missing values.

## Skills
Excel Formulas | Data Analysis | Data Cleaning Basics

# Excel Day 3 - IF Function

## Topics Learned

* IF Function
* Logical Conditions
* TRUE and FALSE results
* Applying conditions to employee data
* Filling formulas across multiple rows

## Practice

Created an employee dataset and used the IF function to classify employees based on age.

### Condition

* Age >= 25 → Adult
* Age < 25 → Young

## Formula Used

`=IF(D2>=25,"Adult","Young")`

## Skills

Excel | IF Function | Logical Thinking | Data Analysis

# Excel Day 4 - COUNTIF Function

## Topics Learned

* COUNTIF Function
* Counting cells based on conditions
* Applying COUNTIF to employee data
* Working with numeric and text criteria

## Practice

Used COUNTIF on an employee dataset to calculate:

* Employees aged 25 or above
* Number of IT employees
* Employees with salary above ₹50,000

## Formulas Used

`=COUNTIF(D2:D11,">=25")`

`=COUNTIF(C2:C11,"IT")`

`=COUNTIF(E2:E11,">50000")`

## Skills

Excel | COUNTIF | Data Analysis | Logical Conditions

# Excel Day 5 - SUMIF Function

## Topics Learned

* SUMIF Function
* Summing values based on conditions
* Text-based criteria
* Numeric criteria
* Applying SUMIF to employee data

## Practice

Used SUMIF on an employee dataset to calculate:

* Total salary of IT employees
* Total salary of Finance employees
* Total salary of employees earning above ₹50,000
* Total salary of HR employees

## Formulas Used

`=SUMIF(C2:C11,"IT",E2:E11)`

`=SUMIF(C2:C11,"Finance",E2:E11)`

`=SUMIF(E2:E11,">50000",E2:E11)`

`=SUMIF(C2:C11,"HR",E2:E11)`

## Skills

Excel | SUMIF | Data Analysis | Conditional Calculations


