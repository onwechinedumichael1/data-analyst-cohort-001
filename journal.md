# Data Analyst Job-Ready Learning Journal

> Last updated: 4 July 2026

---

## Day 1 — Clean and validate: Workbook setup, tables, sorting, filtering, and named ranges

**Phase:** Excel

### What I Did

- **Built:** I learnt how to clean messy data table and make it error free for analysis
- **Why it matters:** I learnt how to fix each issue and log what I changed and the importance of doing so for business
- **Explained:** I learnt that it is important to keep the before and after version of the cleaning data
- **Verified:** I learnt that it is important to save the cleaned version of the work separately from the messy one.

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Clean and validate: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-07-04 | **Method:** SOLVE

> **Scenario:** Sector: HR / Payroll
> 
> Scenario: An HR manager has exported the monthly payroll for a logistics company. Before finance runs the pay run, you must find and fix every data quality issue — one wrong salary or one duplicate employee record costs real money and employee trust.

### S — Split the problem
- 1. Has the HR manager exported the monthly payroll for logistics company?
2. Is the data quality issues fixed?
3. Do you that one wrong salary or one duplicate employee record costs real money and employee trust?

- Audience: finance team
Data: Monthly payroll data for a logistics company
Visual decision: A cleaned and validated dataset
Time-to-understand constrain: The work must be cleaned and completed before payroll starts

- 1. Is the payroll workbook properly structured with clear column headings and data types?
2. Are there duplicate employee records, missing values, or invalid salary entries that needs to be corrected?
3. Can the data be sorted, filtered, and converted into an Excel Table with appropriate named ranges?
4. What changes were made during the cleaning process, and can they be recorded in a short change log?
5. Has the cleaned workbook been saved in the correct folder?

### O — Observe the data
- Workbook: Messy payroll
Rows: 6 rows
Columns: 6 columns
Formulas: find and replace
Targets: duplicates, wrong capitalisation, mixed dates formats, inconsistence with style of writing same words spellings
Actuals: Workbook must be verified clean before any further progress
Visual constraints: the messy payroll must be cleaned before pay-rolling starts

- Table: clean table
Formula output: correct use
Chart: filtered and sorted
Dashboard sheet: clean sheet copied to a new workbook.
Presentation-ready file: save before and after

- wrong chart type: this will alter the expected results causing more financial waste to the company
hidden raw issues: be keen enough to trace and correct the issue, to avoid errors,
clutter: inconsistent formats must be format to the right format, extra space, deleted and irrelevant tables corrected
unreadable labels: be traced and corrected

### V — Verify your logic
- sort, =SUM(F2:F9)

- this will give you a value that you can also use known value to prove the result is correct.

- all errors stated here will make the result fail the stakeholder.

### E — Evolve the solution
- Clutter

- Note

- Screenshot


---
<!-- framework:five-how -->

## Clean and validate: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-07-04 | **Method:** 5-HOW

> **Scenario:** Sector: HR / Payroll
> 
> Scenario: An HR manager has exported the monthly payroll for a logistics company. Before finance runs the pay run, you must find and fix every data quality issue — one wrong salary or one duplicate employee record costs real money and employee trust.

### Write it — code the solution
- I will study the payroll received, lookout for duplicates rows, errors in name spelling, hidden extra spaces,  study the salary possibility and raise concern where necessary.

- Sort

- Name, Salary, Status, and EmpID E001 is duplicated across the row which affected them all.

### Explain it — pseudocode
1. Started with setting up the table, and studying it
2. identified duplicate and deleted one
3. identified name style errors and homogenised them by making all same style.
4. Affected same style of date presentation
5. effected same style of status presentation
6. Saved the workbook separately for report and noted every work done showing before and after status.

### Compare it — analogy
**My analogy:** Sorting a pile of letters by date

**Why it works:** the structural difference is that the letters pile are physical but this items are electronic and an error will cause more harm than the physical sorting and assemblage.

**Where it breaks down:** this concept and approach is the only way to solve large data.

### Use it — job story
**My role:** Junior Data Analyst

**The problem:** A messy payroll data was exported by the HR/Payroll, clean it up and deliver it for use in the next 90minutes.

I opened the messy payroll data, studied it to identify the mess, I will start with duplicates, deleting the copies, work or dates and names, to make sure they are identical in style, look out for hidden spaces and delete the unnecessary ones, look at the amaount and make sure they are on the same currency and no negative amount, and possibly raise complaint to the stakeholder where necessary.

### See it — expected output
- 1. There are two columns A(Input) and B(FormulaResult)
2. There are 3 rows
3. Key cells are; A2, A3, A4, B2,B3.

- An excel sheet with an incomplete data on cell B3

### Try it — Scenario 1
> Finance has an Orders spreadsheet and wants to know: "What's the total sales value for the Electronics category only?"
> 
> Write a SUMIF formula that sums `order_value` where `product_category` equals "Electronics".

- 1. Opened the Orders worksheet
2. OrderID A1, Customer	B1, ProductCategory C1, ProductName D1, Quantity E1, OrderValue F1
3. Selected the cell where I wanted the total sales to appear on H1

- SUMIF
=SUMIF(C:C,“Electronics“,F:F)

- No values

### Try it — Scenario 2
> Your manager needs customer cities added to the orders sheet: "Can you pull in each customer's city from the Customers tab, matched by customer_id?"
> 
> Write an XLOOKUP (or VLOOKUP) formula that looks up customer_id in the Customers sheet and returns the city column.

- 1. Opened the Orders worksheet
2. OrderID A1, Customer	B1, ProductCategory C1, ProductName D1, Quantity E1, OrderValue F1
3. Selected the cell where I wanted the total sales to appear on H1

- =SUMIF(C:C,“Electronics“,F:F)

- Error due to values attached

---
