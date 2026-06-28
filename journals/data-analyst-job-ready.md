# Data Analyst Job-Ready Learning Journal

> Last updated: 28 June 2026

---

## Day 1 — Practice: Workbook setup, tables, sorting, filtering, and named ranges

**Phase:** Excel

### What I Did

1. I read the scenario carefully, to ensure I made no mistakes with the instructions
2. I copied the data
3. I opened an Excel workbook
4. I pasted the copied data into the A1
5. I created 2 extra sheets and renamed the the sheet1 Raw sheet, the sheet2 was renamed Tracker and the Sheet3 was renamed Notes.
6. Renaming the sheets is to know the sheet that i will use for workings, while the Raw sheet will not be touched at all to avoid editing the original data, incase I need it later .

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

> Generated from Qode Clarity. Edit lesson notes in Qode Clarity, then push again.
