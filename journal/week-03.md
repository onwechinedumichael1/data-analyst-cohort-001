# Week 3

[← Back to journal index](index.md)

## Lessons — 1/1 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 12 | 17 Jul 2026, 15:14 |

### Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

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

**Practice work**

---
<!-- framework:solve -->
