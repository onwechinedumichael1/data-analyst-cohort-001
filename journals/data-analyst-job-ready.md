# Data Analyst Job-Ready Learning Journal

> Last updated: 27 June 2026

---

## Day 1 — Learn: Workbook setup, tables, sorting, filtering, and named ranges

**Phase:** Excel

### What I Did

1. Create week-01-branch-transactions.xlsx with three sheets: RawTransactions, Tracker, Notes
2. Create week-01-branch-transactions.xlsx with three sheets: RawTransactions, Tracker, Notes
3. Paste the 8-row sample data into cell A1 of RawTransactions
4. Copy the data to Tracker → Ctrl+T → name the table TransactionsTable
5. Sort TransactionsTable by Amount, largest first — confirm TXN007 (£12,500) is row 1
6. Filter Status to Pending and Review only — confirm 4 of 8 rows visible
7. Name the Amount column TransactionAmounts and the Status column ReviewStatus
8. In cell J1 of Tracker: =SUM(TransactionAmounts) — confirm result is 30010
9. In Notes: answer the three reflection questions in plain sentences
10. the Create week-01-branch-transactions.xlsx link https://us.wps.com/l/cbEaafvoZ0fkQofi

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

- YES

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

> Generated from Qode Clarity. Edit lesson notes in Qode Clarity, then push again.
