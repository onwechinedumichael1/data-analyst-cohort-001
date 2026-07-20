# Data Analyst Job-Ready Learning Journal

> Last updated: 20 July 2026

## Summary

- Track: Data Analyst Job-Ready
- Weeks with evidence: 4
- Lesson entries captured: 22

| Week | Evidence entries | Completed | Last updated |
| --- | ---: | ---: | --- |
| [Week 1: Day 1: Workspace Setup](#week-1-day-1-workspace-setup) | 1 | 1 | 07 Jul 2026, 19:20 |
| [Week 1: Workbook setup, tables, sorting, filtering, and named r](#week-1-workbook-setup-tables-sorting-filtering-and-named-r) | 7 | 7 | 07 Jul 2026, 19:21 |
| [Week 2: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, a](#week-2-formulas-sum-average-countifs-nested-if-vlookup-a) | 7 | 7 | 14 Jul 2026, 21:02 |
| [Week 3: Cleaning data: duplicates, TRIM/PROPER, text-to-columns](#week-3-cleaning-data-duplicates-trimproper-text-to-columns) | 7 | 6 | 20 Jul 2026, 23:20 |

---

## Week 1: Day 1: Workspace Setup

### Lesson 1: Set up your data analyst portfolio

| Field | Value |
| --- | --- |
| Lesson slug | `da-setup-day-1` |
| Phase | Setup |
| Saved/updated | 07 Jul 2026, 19:20 |
| Completed tasks | 12 |
| Lesson complete | Yes |

### What I Did

- **Built:** Created a free GitHub account
- **Note:** Install VS Code on my computer
- **Note:** I Installed Git
- **Built:** I Created your portfolio repo on GitHub
- **Note:** I Cloned the repo into VS Code
- **Built:** I Created your evidence folders
- **Note:** I Set up Excel or Google Sheets
- **Note:** I Connected Qode Clarity to your repo
- **Built:** Wrote my intro README
- **Note:** What we did on 23/6/26
- **Note:** We went to official website of python
- **Note:** Downloaded and installed python..@ below
- **Note:** https://www.python.org/downloads/macos
- **Note:** Installed
- **Verified:** Checked for version (python 3-V)
- **Note:** We went to Jupyter notebook official website @
- **Applied:** Copied and installed command used
- **Note:** https://jupyter.org/install
- **Note:** We launched the notebook
- **Note:** python3 -m pop install notebook
- **Note:** python3 -m Jupyter notebook

### To Explore Further



---

## Week 1: Workbook setup, tables, sorting, filtering, and named r

### Lesson 1: Learn: Workbook setup, tables, sorting, filtering, and named ranges

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-01-learn` |
| Phase | Excel |
| Saved/updated | 07 Jul 2026, 19:21 |
| Completed tasks | 11 |
| Lesson complete | Yes |

### What I Did

- **Note:** Create week-01-branch-transactions.xlsx with three sheets: RawTransactions, Tracker, Notes
- **Note:** Create week-01-branch-transactions.xlsx with three sheets: RawTransactions, Tracker, Notes
- **Note:** Paste the 8-row sample data into cell A1 of RawTransactions
- **Note:** Copy the data to Tracker → Ctrl+T → name the table TransactionsTable
- **Note:** Sort TransactionsTable by Amount, largest first — confirm TXN007 (£12,500) is row 1
- **Verified:** Filter Status to Pending and Review only — confirm 4 of 8 rows visible
- **Note:** Name the Amount column TransactionAmounts and the Status column ReviewStatus
- **Verified:** In cell J1 of Tracker: =SUM(TransactionAmounts) — confirm result is 30010
- **Note:** In Notes: answer the three reflection questions in plain sentences
- **Note:** the Create week-01-branch-transactions.xlsx link https://us.wps.com/l/cbEaafvoZ0fkQofi

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Learn: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-06-27 | **Method:** SOLVE

> **Scenario:** Scenario: A bank branch manager receives a raw transaction export and needs it turned into a usable tracker — a structured workbook with a raw-data sheet, a clean Table, sort and filter views, and named ranges that make later formulas readable.

### S — Split the problem
- A bank branch manager receives a raw transaction export and needs it turned into a usable tracker,  a structured workbook with a raw-data sheet, a clean Table, sort and filter views, and named ranges that make later formulas readable. The task asked me to sort data, filter data, SUM data and place the answer on the first row for easy identification at a glance.

- I am starting from a raw transaction export, copy and saved as RawTransactions, never to edit, copied to another sheet as Tracker, my working area.

- The finished work showcased several things, that was hard to identify, due to the presence of large amount of data, which need to sorted, classed, sorted, identified and hidden data showcased, in other words, the finished workbook showed the specifically what is needed to work work with, either the highest TransactionsAmount, where it came from, date and product or SUM of the transactions at a glance, instead of going through the bulk of raw data, used formulas also, to make it readable.

### O — Observe the data
The workbook contains 3 worksheets, RawTransactions, Tracker, and Notes, the worksheets has columns (A,B,C,D,E,F,G) and headers (Sample data (Transaction ID), Date, Branch, Customer type, Amount, Status) in 8 transaction records, from row 2 to row 9.
Header are inconsistent and arranging the data for easy linkage between data of similar records in areas like performance, amount and date.

### V — Verify your logic
- By checking the formula reference on the formula bar, to see confirm that the area of interest is actually and correctly captured, as well as the interested formula is writing as it should, you can also try to manually run the simpler kind of formula use, to check if the given result is same as expected by using a known value.

- Used a known value of 25 (E13) and 20(F13) as the values to be =SUM(E13:F13) and i expected 45 and I got 45.

- Yes, any of the edge cases can alter the expected result or cause error in the data preparation, for instance, blank cells can reduce the value of the result of the formulation, text of ten instead of 10 in a cell will give an error result as the formula will only capture numbers and not texts, also, space before the value used for the formulation will affect the result negatively, and duplicate value will of course alter the real expected result. to avoid these scenarios, it is important to always check that these mistakes do not happen by testing each of the scenario to check result.

### E — Evolve the solution
- I did the following; I copied the raw data from the practice or exercise information. 
Opened excel, clicked on a blank workbook, clicked on cell A1 and pasted the 8-row sample data provided by my instructor. The data went upto 8-rows.
Renamed the sheet from sheet1 to RawTransactions, clicked on + to add a New sheet, renamed the new sheet to Tracker and pasted the Raw data copied from the Assessment details, before I then clicked on the + icon on the status bar to add another worksheet, which i renamed Note.

- =SUM(TransactionAmounts) and clicked the enter key, and the data generated is 30010.

- I can use this method and handle data work of vary upto 50 rows or more


---
<!-- framework:five-how -->

## Learn: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-06-27 | **Method:** 5-HOW

> **Scenario:** Scenario: A bank branch manager receives a raw transaction export and needs it turned into a usable tracker — a structured workbook with a raw-data sheet, a clean Table, sort and filter views, and named ranges that make later formulas readable.

### Write it — code the solution
- I did the following; I copied the raw data from the practice or exercise information. 
Opened excel, clicked on a blank workbook, clicked on cell A1 and pasted the 8-row sample data provided by my instructor. The data went upto 8-rows.
Renamed the sheet from sheet1 to RawTransactions, clicked on + to add a New sheet, renamed the new sheet to Tracker and pasted the Raw data copied from the Assessment details, before I then clicked on the + icon on the status bar to add another worksheet, which i renamed Note.

- =SUM(TransactionAmounts)

- F9

### Explain it — pseudocode
I did the following; I copied the raw data from the practice or exercise information. 
Opened excel, clicked on a blank workbook, clicked on cell A1 and pasted the 8-row sample data provided by my instructor. The data went upto 8-rows.
Renamed the sheet from sheet1 to RawTransactions, clicked on + to add a New sheet, renamed the new sheet to Tracker and pasted the Raw data copied from the Assessment details, before I then clicked on the + icon on the status bar to add another worksheet, which i renamed Note.

### Compare it — analogy
**My analogy:** This concept is like when you return from market and the purchased items are all mixed up in the big bag, it is time to separate the toiletry from the edibles and kept them separately for easy identification and usage.

**Why it works:** Here you are checking if you actually bought everything you needed to purchase.

**Where it breaks down:** it is limited to certain amount of goods to be counted, big data cannot be counted by the traditional way or separated.

### Use it — job story
**My role:** Junior data analyst in a company,

**The problem:** Loan, it is at amount of 12,500, described as Loan from Manchester.

When i opened the workbook, and I clicked on any cell in the column, clicked on Home, clicked on filter, and selected from highest to lower, and it was sorted, starting from the highest value.

### See it — expected output
- Column A is seen to contain text labels Row A and Row B
Column B contains numeric values, which are 150.00 (Key cell. ColumnB: Row A) and 89.50 (Key cell: Column B: Row B)

- It is seen to have A column labelled Column A, a number in Column B. and a formula Result column.

### Try it — Scenario 1
> Finance has an Orders spreadsheet and wants to know: "What's the total sales value for the Electronics category only?"
> 
> Write a SUMIF formula that sums `order_value` where `product_category` equals "Electronics".

- I followed the instruction, and the functions that the Manager described.

- =A2*1.1A3*11

- 30010, that’s the total sum of the formula, used on the column of interest as described in the formula bar.

### Try it — Scenario 2
> Your manager needs customer cities added to the orders sheet: "Can you pull in each customer's city from the Customers tab, matched by customer_id?"
> 
> Write an XLOOKUP (or VLOOKUP) formula that looks up customer_id in the Customers sheet and returns the city column.

- I opened excel, clicked on open new sheet, opened the sheet, created sheet 2, and sheet 3, renamed the sheets RawTransactions, Trackers and Notes respectively, 
copied the data to the Tracker sheet so that the original RawTransactions data would remain unchanged. 
The raw sheet acts as a backup and a reliable source of data. If I edited the raw sheet directly, I could accidentally delete or change important information, making it difficult to identify errors or restore the original data.

- =A2 1.1

- The result is the SUM of the data on the column, to the total sum of 30010.

---

### Lesson 2: Practice: Workbook setup, tables, sorting, filtering, and named ranges

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-01-practice` |
| Phase | Excel |
| Saved/updated | 28 Jun 2026, 15:53 |
| Completed tasks | 4 |
| Lesson complete | Yes |

### What I Did

- **Note:** I read the scenario carefully, to ensure I made no mistakes with the instructions
- **Note:** I copied the data
- **Note:** I opened an Excel workbook
- **Note:** I pasted the copied data into the A1
- **Built:** I created 2 extra sheets and renamed the the sheet1 Raw sheet, the sheet2 was renamed Tracker and the Sheet3 was renamed Notes.
- **Note:** Renaming the sheets is to know the sheet that i will use for workings, while the Raw sheet will not be touched at all to avoid editing the original data, incase I need it later .

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Practice: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-06-28 | **Method:** SOLVE

> **Scenario:** Sector: Retail
> 
> Scenario: A supermarket chain has exported this week's product sales across four city branches. Your job: build the same structured workbook you built for the bank — raw sheet untouched, a named Table in Tracker, sorted by Revenue, filtered to show only Returned and Pending rows.

### S — Split the problem
- This task asked me to recreate workflow from scratch, follow the instruction, rename sheet, save a the data in a Rawsheet, and another in sheet2, which is renamed Tracker where all the work will take place, so that the originality of the data is preserved in the RawSheet.

- I started from a raw data of purchases, given in the scenario.

- the finished workbook looks different from the raw data in the column F1 where revenue was renamed to SaleRevenue and a SUM(F2:F9) was shown at cell J1 as 1178

### O — Observe the data
I saw the table showing variable data each day and these records are not following any pattern, making it unpredictable. There, i observed that this exercise is important for institutions and businesses to be able to manage the institution perfectly.

### V — Verify your logic
- I will check if the formula is correct by manually adding up all the number in the named range.

- by testing with a named value, like 2 and 2 in different cells as a named range, and got 4, it is correct because 2+2=4.

- The edge cases that could break this is making mistakes with the named ranged, or using ranges without numbers, you will get NAME? as an outcome, which is error

### E — Evolve the solution
- i clicked the excel, it loaded, i copied the data fro the scenario, and pasted it on cell A1, and on another sheet (Sheet2) which i will rename to Tracker, and i will not tamper with the data on the sheet+, which i later renamed Rawsheet, and i will do all the work in the Tracker sheet.

- =SUM(F2:F9)

- I will always read the reference on the formula bar, to ensure that i am using the correct named range, and I will ensue that I never tampered with the raw data saved on Rawsheet.,


---
<!-- framework:five-how -->

## Practice: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-06-28 | **Method:** 5-HOW

> **Scenario:** Sector: Retail
> 
> Scenario: A supermarket chain has exported this week's product sales across four city branches. Your job: build the same structured workbook you built for the bank — raw sheet untouched, a named Table in Tracker, sorted by Revenue, filtered to show only Returned and Pending rows.

### Write it — code the solution
- . I opened the software
. Clicked on blank worksheet
. Clicked on A1, where I pasted the copied data
. Right-Clicked when my cursor is resting on the Sheet1, clicked on rename, to change the name to RawSheet.
. Clicked on + on the sheet title bar, to add another sheet to the existing sheet(s), this action gave rise to Sheet2
. I performed the same action above to rename the sheet2 to Tracker, where i did all the work, renaming and =SUM(F1:F9)

- =SUM(F2:F9)

- SaleRevenue

### Explain it — pseudocode
1. I read the instruction on the scenario
2. I copied the data
3. I launched the software for the work, which is excel
4. I clicked on blank sheet, and the sheet is loaded
5. I clicked A1 and pasted the copied data into the cell.
6. I created another sheet2, and renamed Tracker, where I performed all the works, this is to allow the data pasted on Sheet1 renamed to Rawsheet, to be preserved for references, if there is need or mistake on the one used for working.
7. I continued with remaninh the Revenue column name to SaleRevene.
8. I used formula =SUM(f2:f9) to get the SUM of the Namedranges as,which is correct as 1178
9.I tried toclick on the F2 and drag it down to check if the formula is correct.I also added manually because the data is not bulky, and i got the same value.

### Compare it — analogy
**My analogy:** Delivery van, picking packages and parcels from the post office or the personnel in-charge of sorting these items according to the location they are going, from among parcels.

**Why it works:** each van going to different respective location, makes delivery precise and timely. Same as these filtering, sorting and named ranges, helps fasten work delivery, accuracy, reference and accurate, so long the formula is accurate, and checked by testing simple known values.

**Where it breaks down:** one personnel cannot deliver the items to all the different locations and meet up,same as sorting 1million items manually, or using other means rather than the SQL,

### Use it — job story
**My role:** Junior Data Analyst, to build the structured workbook, similar to that of the bank.

**The problem:** Dairy category of cheese product, from Southwark store, generated 275 SaleRevenue

I used the filter query to filter from the highest to the lowest, after making the SaleRevenue the ranged name, by clicking the enter key, the workshop was rearranged, showing the highest store, with the highest SaleReveneu, and the product with the products category.

### See it — expected output
- The spreadsheet layout has seven columns and 9 rows, the column carries the title of data listed under, while the rows describes the characteristics of a product.

- The final result shows a workbook, with SaleID, Date of transactions, the store name, the product and the product category, the status of the item, if it is sold, returned or pending, as well as the salerevenue, with the result of entire salerevenue as 1178.

### Try it — Scenario 1
> Finance has an Orders spreadsheet and wants to know: "What's the total sales value for the Electronics category only?"
> 
> Write a SUMIF formula that sums `order_value` where `product_category` equals "Electronics".

- . open the excel app
. click to launch
. click of blank sheet
. copy the given data and paste in on A1, by clicking on A1.
. Rename Sheet1 ro Rawsheet.
. click on the + icon next to sheet1 that was renamed.
. Rename sheet2 to Tracker, copy and paste the Rawsheet information.
. to format, i highlighte from A1 and dragged it down to G9
. Rename Revenue column title to SaleReveneu.
. click on J1 and use this formula to sum (=SUM(F2:F9) and click enter key, the result will be 1178.
. I then clicked Save As, to be able to rename the workbook to.

- SUM, =SUM(F2:F9)

- 1178

### Try it — Scenario 2
> Your manager needs customer cities added to the orders sheet: "Can you pull in each customer's city from the Customers tab, matched by customer_id?"
> 
> Write an XLOOKUP (or VLOOKUP) formula that looks up customer_id in the Customers sheet and returns the city column.

- . open the excel app
. click to launch
. click of blank sheet
. copy the given data and paste in on A1, by clicking on A1.
. Rename Sheet1 ro Rawsheet.
. click on the + icon next to sheet1 that was renamed.
. Rename sheet2 to Tracker, copy and paste the Rawsheet information.
. to format, i highlighte from A1 and dragged it down to G9
. Rename Revenue column title to SaleReveneu.
. click on J1 and use this formula to sum (=SUM(F2:F9) and click enter key, the result will be 1178.
. I then clicked Save As, to be able to rename the workbook to.

- SUM, =SUM(F2:F9)

- 1178

---

### Lesson 3: Clean and validate: Workbook setup, tables, sorting, filtering, and named ranges

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-01-clean-validate` |
| Phase | Excel |
| Saved/updated | 05 Jul 2026, 02:04 |
| Completed tasks | 4 |
| Lesson complete | Yes |

### What I Did

- **Note:** I learnt how to clean messy data table and make it error free for analysis
- **Why it matters:** I learnt how to fix each issue and log what I changed and the importance of doing so for business
- **Note:** I learnt that it is important to keep the before and after version of the cleaning data
- **Note:** I learnt that it is important to save the cleaned version of the work separately from the messy one.
- **Note:** I studied what data is all about, how to describe data, Data name, formats, types and structure.
- **Note:** Studied Data life cycle
- **Note:** as (Collect, Store, Prepare, Analyse, Visualise Decide, Archive)
- **Note:** Classify data. judge data quality
- **Note:** Differentiate between data and information
- **Note:** Studied why data matters eg Hospital, Police, Business, Football.
- **Note:** Classification by measurement scale
- **Note:** Identified Data structure (Structured, semi-Structure and unstructured)

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

### Lesson 4: Analyze: Workbook setup, tables, sorting, filtering, and named ranges

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-01-analyze` |
| Phase | Excel |
| Saved/updated | 05 Jul 2026, 02:12 |
| Completed tasks | 4 |
| Lesson complete | Yes |

### What I Did

- **Note:** I answered three business questions using branch transactions tracker workbook
- **Note:** I showed the exact formula, query, or code for each answer.
- **Built:** I wrote each answer in one plain sentence
- **Built:** I wrote one limitation of my analysis

### To Explore Further



---

### Lesson 5: Visualize: Workbook setup, tables, sorting, filtering, and named ranges

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-01-visualize` |
| Phase | Excel |
| Saved/updated | 06 Jul 2026, 19:54 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Built:** I built a chart
- **Note:** The chart is presented with line chart with markers, only A&E data plus Paediatrics when I did the stretch task appeard
- **Note:** I changed the title: A&E average wait times are failing-6- month trend
- **Note:** I named the Y-axis: Minutes
- **Note:** Data label only on June (141 min)
- **Note:** The chart has no gridlines, no chart border, A&E line is red and Paediatrics line is blue
- **Note:** The chart link: https://us.wps.com/l/cbEaauu4xISE0PmM

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Visualize: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-07-07 | **Method:** SOLVE

> **Scenario:** Sector: Healthcare
> 
> Scenario: A hospital operations manager needs to present A&E waiting-time performance to the board. The board has 90 seconds per slide. Your chart must communicate the trend immediately — no table, no explanation needed, just the visual.

### S — Split the problem
- 1. who is the audience ?
2. Who is presenting the information?
3. What information needs to be presented ?
4. How much time does the audience have for each slide?
5. What is the main purpose of the visual?
6. What type of presentation aid is required?
7. What should be excluded from the slide?
8. What chart type would best meet this requirement?
9. What is the key design requirement?
10. Which chart would best meet this requirement?

- The audience: 1
The data. 1
The visual:4
The time-to-understand constraints: 2

- 1. What A&E waiting-time data (Jan–Jun) should be included in the chart?
2. Which chart type best shows the waiting-time trend over time? (A line chart.)
3. How can the chart be formatted so the board understands the trend within 90 seconds? (Clear title, red line, data label on June, no gridlines or border.)
4. What unnecessary information (such as other departments, tables, or extra text) should be removed to keep the visual simple?
5. Is the finished chart presentation-ready and does it clearly show that A&E waiting times are falling?

---

### Lesson 6: Portfolio proof: Workbook setup, tables, sorting, filtering, and named ranges

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-01-portfolio-proof` |
| Phase | Excel |
| Saved/updated | 07 Jul 2026, 00:24 |
| Completed tasks | 5 |
| Lesson complete | Yes |

---

### Lesson 7: Review: Workbook setup, tables, sorting, filtering, and named ranges

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-01-review` |
| Phase | Excel |
| Saved/updated | 07 Jul 2026, 00:51 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Note:** I revised the previous days activities, practised tasks and updated my practice notes with a new targets
- **Note:** Rated my confidence on each main skill
- **Note:** Identified gaps to fill.
- **Built:** Created the project README with problem, method, evidence, validation, and limitations

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Review: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-07-07 | **Method:** SOLVE

> **Scenario:** Sector: Cross-industry
> 
> Scenario: It is end of Week 1. Before you start Week 2 (formulas: SUM, AVERAGE, COUNTIFS, VLOOKUP), you need to know exactly which Excel skill still feels shaky. Week 2 builds directly on this week's foundation — a gap now becomes a compounding problem later.

### S — Split the problem
- 1. What week is this?
2. What are you supposed to do before the start of week2?
3. Do you know exactly which Excel skill still feels shaky on these formulas: (SUM, AVERAGE, COUNTIFS, VLOOKUP)?
4. What week work  is week2 work built on ?
5. What is the future consequence of a gap now?

- 1. Audience: 2
2. The data: 2

- ok

### O — Observe the data
- Targets

- Presentation-ready file.

- Wrong Chart type

### V — Verify your logic
- Formula

- SUM

- Bad calculation

### E — Evolve the solution
- Clutter

- Labels

- Both are useful in there own way

---

## Week 2: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, a

### Lesson 1: Learn: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-02-learn` |
| Phase | Excel |
| Saved/updated | 10 Jul 2026, 02:13 |
| Completed tasks | 12 |
| Lesson complete | Yes |

### What I Did

- **Note:** In today`s concept clinic, Titled Understanding Data, data was defined, explained, and classify, Mapping of the lifecycle of data, and judge data quality.
- **Note:** The exercise from todays concept clinic enlightened me on the the following
- **Note:** Data name, formats, types and structure.
- **Note:** Analyses and practices was carried out to ensure comprehension.
- **Note:** The daily 1hr practice, was on ........today and the exercise exposed me to the following
- **Note:** ..... and solved the given tasks,
- **Note:** Practices were carried out, and  an example of the worksheet show via this link:https://us.wps.com/l/cbEaahJ4p0EyCojI
- **Note:** Was able to write one WHY sentence, before touch excel

### To Explore Further



---

### Lesson 2: Practice: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-02-practice` |
| Phase | Excel |
| Saved/updated | 10 Jul 2026, 13:28 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Note:** I learnt the uses and applications of Formulas like
- **Note:** SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP.
- **Note:** These exercises was carried out using real life scenario,  making the learning, practice worthy.
- **Applied:** Todays skill was used to improve Commission calculator workbook
- **Note:** The file, query, notebook produced was saved.
- **Note:** And updated in the GitHub.

### To Explore Further



---

### Lesson 3: Clean and validate: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-02-clean-validate` |
| Phase | Excel |
| Saved/updated | 14 Jul 2026, 18:40 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Note:** First of all, copy the value, gently and paste in the cell (A1)
- **Note:** searched for the missing vale, the error value
- **Verified:** And studied the rows and column brorher.
- **Note:** In todays concept clinic, we were thought on how to create PR, and, and that there are 2 different .
- **Note:** Also we practiced on GitHub parameters, git pull, git push, git commit, among others.

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Clean and validate: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP
**Completed:** 2026-07-14 | **Method:** SOLVE

> **Scenario:** Sector: E-commerce
> 
> Scenario: An e-commerce operations manager has exported the product catalogue from the warehouse system. Before updating the website, you must find and fix every error — because a formula that returns #VALUE! in a price column will display nothing to customers, and a #DIV/0! in a margin calculation will crash the pricing report.

### S — Split the problem
- 1. What and how is the product catalogue
2. What are the rows and columns involved in the export?
3. What formulas are needed?
4. Is any price missing?
5. is the report correct?

- Audience: 1
Data: 4
The visual decision: 4
Time to understand constraints: 2

- 1. Cleaned ?
2. Dataset ?
3. Saved?

### O — Observe the data
- Formulas, targets and actuals

- Presentation ready file.

- Hidden raw issues

### V — Verify your logic
- Identify each error, list and fix them.

- Random Row checks and Total Row counts

- unclear label, bad calculation, or clutter

### E — Evolve the solution
- clutter, labels, colour

- journal push, Read me.

- Journal and screenshot

---

### Lesson 4: Analyze: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-02-analyze` |
| Phase | Excel |
| Saved/updated | 14 Jul 2026, 19:20 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Note:** Answered three business questions using Commission calculator workbook
- **Note:** Showed the exact formula, query, or code for each answer
- **Built:** Wrote each answer in one plain sentence
- **Built:** Updated or created the project README with problem, method, evidence, validation, limitation, and next step

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Analyze: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP
**Completed:** 2026-07-14 | **Method:** SOLVE

> **Scenario:** Sector: Real Estate
> 
> Scenario: A London estate agency needs to review agent performance and postcode trends before their monthly board meeting. The director wants four specific answers about which agents are overpricing listings, which postcodes sell fastest, and whether 3-bed houses beat flats on margin.

### S — Split the problem
- 1. Clean workbook?
2. Who are the audience?

- 1. The Audience: 2.
2. The dat: 1.
3. The-to-understand constraint: 1

- Save under notes/week-02.

### O — Observe the data
- Targets.

- Presentation-ready file.

- hidden raw issues

### V — Verify your logic
- Workbook output

- Total Row count

- unclear label

### E — Evolve the solution
- layout, labels, colour, chart choice, and clutter

- Listing identified errors.

- Journal

---

### Lesson 5: Visualize: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-02-visualize` |
| Phase | Excel |
| Saved/updated | 14 Jul 2026, 19:45 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Built:** Built or improve one chart from this week's work
- **Built:** Added a clear title, labelled axes, and remove clutter
- **Note:** Picked the chart type that fits the data, not the default
- **Built:** Wrote the one sentence this visual should prove in 10 seconds
- **Built:** Updated or created the project README with problem, method, evidence, validation, limitation, and next step

### To Explore Further



---

### Lesson 6: Portfolio proof: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-02-portfolio-proof` |
| Phase | Excel |
| Saved/updated | 14 Jul 2026, 20:45 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Built:** Wrote a short README for Commission calculator workbook
- **Built:** Added a screenshot or exported file as evidence
- **Built:** Wrote one resume bullet point from this week's work
- **Note:** Posted and updated via— LinkedIn, GitHub, or your learning log
- **Note:** Updated or create the project README with problem, method, evidence, validation, limitation, and next step

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Portfolio proof: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP
**Completed:** 2026-07-14 | **Method:** SOLVE

> **Scenario:** Sector: Multi-industry
> 
> Scenario: You have built a commission calculator, applied formulas to student grades, fixed e-commerce catalogue errors, analysed property performance, and built a production dashboard. A recruiter reading your GitHub now sees someone who can apply the same analytical toolkit across five completely different industries. That versatility is your edge.

### S — Split the problem
- 1. Is the dashboard clean?
2. Are you a data analyst?
3. Are you versatile?

- 1. The data: 1
2. The audience: 2
3. The visual decision: 2.

- Save it under notes.

### O — Observe the data
- targets

- Presentation ready file

- Unreadable labels

### V — Verify your logic
- Workbook output

- Row counts, =SUM.

- Bad calculation, unclear label.

### E — Evolve the solution
- Labels, Clutter

- Notes.

- Journal


---
<!-- framework:five-how -->

## Portfolio proof: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP
**Completed:** 2026-07-14 | **Method:** 5-HOW

> **Scenario:** Sector: Multi-industry
> 
> Scenario: You have built a commission calculator, applied formulas to student grades, fixed e-commerce catalogue errors, analysed property performance, and built a production dashboard. A recruiter reading your GitHub now sees someone who can apply the same analytical toolkit across five completely different industries. That versatility is your edge.

### Write it — code the solution
- Document every issues before fixing
Total row counts
Clean and
fix

- XLOOKUP

---

### Lesson 7: Review: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-02-review` |
| Phase | Excel |
| Saved/updated | 14 Jul 2026, 21:02 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Note:** Good with the application of these formulas
- **Note:** COUNTIFS in counting duplicates
- **Note:** nested IF to flag issues
- **Note:** LOOKUP
- **Note:** to validate against reference tables

### To Explore Further



---

## Week 3: Cleaning data: duplicates, TRIM/PROPER, text-to-columns

### Lesson 1: Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-03-learn` |
| Phase | Excel |
| Saved/updated | 17 Jul 2026, 15:14 |
| Completed tasks | 12 |
| Lesson complete | Yes |

### What I Did

- **Note:** Copied and pasted the raw export into RawExport sheet of week-03-customer-cleanup.xlsx
- **Built:** Created CleanedCustomers sheet — all formulas reference RawExport
- **Note:** DuplicateFlag column: =COUNTIF($A$2:$A$9,A2) — highlight any >1 in red
- **Note:** CleanName: =TRIM(PROPER(RawExport!B2)) → paste as Values → confirm C001 = 'John Smith'
- **Note:** CleanEmail: =LOWER(TRIM(RawExport!C2)) — confirm C001 = 'john.smith@email.com'
- **Note:** Text-to-Columns on CityPostcode → split into City and Postcode — confirm Manchester + M1 2AB
- **Applied:** CleanSignupDate: used DATEVALUE to convert all 5 date formats to a date serial
- **Note:** Deleted the duplicate C001 row — confirm 7 unique records remain
- **Note:** Add Data Validation to SignupDate: Date between 01/01/2020 and today
- **Why it matters:** Notes sheet: 3-line Data Quality Summary — issues found, fixed, remaining risks
- **Why it matters:** Identified the messy-input or failure case for this module
- **Note:** Updated the project README with problem, method, evidence, validation, limitation, and next step
- **Note:** The file showing before (RawExport)and after cleaning (TrackerRaw), plus all the issues listed in the Note sheet.
- **Note:** File link: https://1drv.ms/x/c/d13aea9a178ecc2c/IQCjJTqtGNxFSa7HEYMcswQmAVo5M5YPzJILg5kclyDnXvM?e=YCkso6

### To Explore Further



### My Practice Work

---
<!-- framework:solve -->

## Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules
**Completed:** 2026-07-17 | **Method:** SOLVE

> **Scenario:** Sector: Telecoms
> 
> Scenario: A telecoms operations analyst exported 8 subscriber records from the CRM for a Q3 campaign. The export has leading/trailing spaces in names, all-caps emails, city+postcode crammed into one cell, five different date formats, and one duplicate entry. Fix everything before the marketing team imports it.

### S — Split the problem
- 1. what data was exported from the CRM for  Q3 campaign?
2. What names contain leading or trailing spaces that need trimming?
3. Which email addresses are in all caps and need standardising?
4. Which cell contains the city and the post code, and how should they be spilt into separate columns?
5. What date formats are inconsistent, and what format should be used in all?
6. Which record is duplicate that one should be deleted?
7. Is the cleaned dataset ready for the marketing team to import?

- 1. Audience: The marketing team.
2. The data: 8 subscriber records exported from the CRM for Q3 campaign
3. The visual decision: Clean the data by removing the issues (remove duplicates, trimming spaces, standardising email cases and date formats to a consistent one, spliting the city from the postcode into different columns).
4. Time to understand the constraints: Fix everything before the marketing team imports it.

- 1. How do I create a CleanedCustomers sheet while keeping RawExport unchanged?
2. How do I remove the duplicate so the cleaned sheet contains 7 unique rows?
3. How do I split the City/Postcode column into two separate columns?
4. How do I standardise all dates into one consistent format?
5. How do I check that names, emails, dates, and validation rules are correct before saving the workbook as week-03-customer-cleanup.xlsx?

---

### Lesson 2: Practice: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-03-practice` |
| Phase | Excel |
| Saved/updated | 17 Jul 2026, 18:14 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Note:** Completed a hands-on exercise applying Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules
- **Applied:** Used today's skill to improve my Messy customer export cleanup
- **Note:** Saved the file, query, or notebook produced
- **Built:** Wrote one sentence on what the output actually shows
- **Note:** Updated or create the project README with problem, method, evidence, validation, limitation, and next step

### To Explore Further



---

### Lesson 3: Clean and validate: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-03-clean-validate` |
| Phase | Excel |
| Saved/updated | 17 Jul 2026, 18:33 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Verified:** Checked for missing values, duplicates, wrong types, and bad dates
- **Why it matters:** Fixed each issue and log what you changed and why
- **Note:** Recorded a before/after row count
- **Note:** Saved the cleaned version separately from the raw file
- **Note:** Update or create the project README with problem, method, evidence, validation, limitation, and next step

### To Explore Further



---

### Lesson 4: Analyze: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-03-analyze` |
| Phase | Excel |
| Saved/updated | 20 Jul 2026, 08:19 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Note:** I Answered three business questions using Messy customer export cleanup
- **Note:** Showed the exact formula, query, or code for each answer
- **Built:** Wrote each answer in one plain sentence
- **Built:** Wrote one limitation of the analysis
- **Note:** Updated or create the project README with problem, method, evidence, validation, limitation and next step

### To Explore Further



---

### Lesson 5: Visualize: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-03-visualize` |
| Phase | Excel |
| Saved/updated | 20 Jul 2026, 17:16 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Built:** I built or improved one chart from this week`s work
- **Built:** I added a clear title, labelled axes, and removed clutter
- **Applied:** Formula used: =IF(D2>C2*1.05,"Exceeded",IF(D2>=C2,"Met",IF(D2>=C2*0.9,"Near","Below")))
- **Note:** Picked the chart type that fits the data, not the default
- **Built:** Wrote the one sentence this visual should prove in 10 seconds
- **Verified:** 8 rows	 4 columns
- **Note:** Met Traget: R6, R1, R6
- **Note:** Exceeded Targets: R1, R4, R8
- **Note:** Below Target (Immediate Attention): R2, R5
- **Note:** Screenshot attached
- **Note:** This is the link and evidence of the work, showing all stated above: https://us.wps.com/cms/docs/d/cbEaagh8VOz0MNQz
- **Built:** Updated or created the project README with problem, method, evidence, limitation, and the next step

### To Explore Further



---

### Lesson 6: Portfolio proof: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-03-portfolio-proof` |
| Phase | Excel |
| Saved/updated | 20 Jul 2026, 23:04 |
| Completed tasks | 5 |
| Lesson complete | Yes |

### What I Did

- **Built:** I wrote a short README for easy messy customer export cleanup
- **Built:** Added a screen or exported file as evidence
- **Built:** Wrote one resume bullet point from this week`s evidence
- **Note:** Posted a short update on Linkedln, Github or my learning log
- **Note:** Updated the project README with problem, method, evidence, validation, limitation, and next step

### To Explore Further



---

### Lesson 7: Review: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

| Field | Value |
| --- | --- |
| Lesson slug | `da-week-03-review` |
| Phase | Excel |
| Saved/updated | 20 Jul 2026, 23:20 |
| Completed tasks | 5 |
| Lesson complete | In progress |

### What I Did

- **Note:** Reviewed
- **Note:** Rated
- **Note:** Redo
- **Built:** Wrote, gaps fixed
- **Note:** And updated

### To Explore Further



---