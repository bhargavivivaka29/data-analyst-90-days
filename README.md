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

# Excel Day 6 - AVERAGEIF Function

## Topics Learned

* AVERAGEIF Function
* Calculating averages based on conditions
* Text-based criteria
* Applying AVERAGEIF to employee data

## Practice

Used AVERAGEIF on an employee dataset to calculate:

* Average salary of IT employees
* Average salary of Finance employees
* Average salary of HR employees
* Average salary of Sales employees

## Formulas Used

`=AVERAGEIF(C2:C11,"IT",E2:E11)`

`=AVERAGEIF(C2:C11,"Finance",E2:E11)`

`=AVERAGEIF(C2:C11,"HR",E2:E11)`

`=AVERAGEIF(C2:C11,"Sales",E2:E11)`

## Skills

Excel | AVERAGEIF | Data Analysis | Conditional Calculations

# Excel Day 7 - COUNTIFS Function

## Topics Learned

* COUNTIFS Function
* Multiple conditions
* Counting records based on multiple criteria
* Conditional data analysis

## Practice

Used COUNTIFS on an employee dataset to calculate:

* IT employees aged 25 or above
* Finance employees aged 30 or above
* Sales employees with salary above ₹45,000

## Formulas Used

`=COUNTIFS(C2:C11,"IT",D2:D11,">=25")`

`=COUNTIFS(C2:C11,"Finance",D2:D11,">=30")`

`=COUNTIFS(C2:C11,"Sales",E2:E11,">45000")`

## Results

* IT employees aged 25+ → 2
* Finance employees aged 30+ → 2
* Sales employees with salary above ₹45,000 → 1

## Skills

Excel | COUNTIFS | Conditional Analysis | Data Analysis

# Excel Day 8 - SUMIFS Function

## Topics Learned

* SUMIFS Function
* Multiple criteria
* Conditional sum
* Data analysis using Excel

## Practice

Used SUMIFS on an employee dataset to calculate:

* Total salary of IT employees → ₹162,000
* Total salary of Finance employees → ₹190,000
* Total salary of Sales employees → ₹94,000
* Total salary of employees earning above ₹50,000 → ₹310,000
* Total salary of HR employees → ₹93,000

## Formulas Used

`=SUMIFS(E2:E11,C2:C11,"IT")`

`=SUMIFS(E2:E11,C2:C11,"Finance")`

`=SUMIFS(E2:E11,C2:C11,"Sales")`

`=SUMIFS(E2:E11,E2:E11,">50000")`

`=SUMIFS(E2:E11,C2:C11,"HR")`

## Skills

Excel | SUMIFS | Conditional Analysis | Data Analysis


# Excel Day 9 - MAXIFS & MINIFS

## Topics Learned

* MAXIFS Function
* MINIFS Function
* Finding maximum values based on conditions
* Finding minimum values based on conditions
* Conditional data analysis

## Practice

Used MAXIFS and MINIFS on an employee dataset to calculate:

* IT highest salary → ₹62,000
* IT lowest salary → ₹42,000
* Finance highest salary → ₹70,000
* Finance lowest salary → ₹55,000
* Sales highest salary → ₹50,000

## Formulas Used

`=MAXIFS(E2:E11,C2:C11,"IT")`

`=MINIFS(E2:E11,C2:C11,"IT")`

`=MAXIFS(E2:E11,C2:C11,"Finance")`

`=MINIFS(E2:E11,C2:C11,"Finance")`

`=MAXIFS(E2:E11,C2:C11,"Sales")`

## Skills

Excel | MAXIFS | MINIFS | Conditional Analysis | Data Analysis

