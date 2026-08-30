# Week 5

[← Back to journal index](index.md)

## Lessons — 3/4 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Learn: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | Complete | 7 | 27 Aug 2026, 04:09 |
| Practice: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | Complete | 5 | 28 Aug 2026, 10:24 |
| Clean and validate: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | Complete | 5 | 29 Aug 2026, 19:09 |
| Analyze: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | In progress | 5 | 30 Aug 2026, 02:09 |

### Learn: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Note:** A&E was entered into PatientData
- **Note:** The column appeared in this format
- **Note:** A: PatientID, B: WaitTime_h, C: Staff, D: Acuity by: =MODE.SNGL(PatientData)
- **Note:** Identified Wait Time as CB2:B9, Staff as C2: C9, and Acuity as D2: D9,
- **Note:** The Average was gotten by this formula =AVERAGE (PatientData! B2:B9) = 2.50Hours, = Mean
- **Note:** The Median is calculated by using this formula
- **Note:** =MEDIAN(PatientData !B2:B9) = 1.65 hours
- **Note:** I Calculated the mode of Acuity value

### Practice: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Note:** We completed a hands on exercise applying Mean, Media, Mode, Standard Deviation, Correlation, Outliers, and sampling bias in plain English
- **Applied:** We used today's skill to improve Customer behaviour stats statistics
- **Note:** We saved the file, query, or query note book we produced
- **Built:** We wrote one sentence  what the output actually show
- **Built:** We updated or created the Project with README with problems, method, evidence, validation limitation, and next step

### Clean and validate: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Verified:** missing values was checked, duplicates checked, wrong types checked, bad dates checked, and identified
- **Verified:** all the identified issues were fixed and logged in the note of what i changed and why i changed them.
- **Note:** I recorded before and after row count
- **Note:** I saved the cleaned version separately from the raw file
- **Built:** I updated / created the project README with problem, method, evidence, validation, limitation, and next step.

### Analyze: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Note:** Answered three business questions using customers behaviour stats brief
- **Explained:** Question 1: which subject has the highest average score?
- **Note:** Formula: =AVERAGE (B2:B9) = Maths=66.4, =AVERAGE (C2:C9) = English=72.4, =AVERAGE(D2:D9) = Science=62.8
- **Note:** Plain text answer, English has the highest average score at 72.4
- **Explained:** Question 2: Which subject has the most consistent score?
- **Note:** Formula
- **Note:** =STDEV.S(B2:B9) =Maths=20.8, =STDEV.S(C2:C9) = English =14.7, =STDEV.S(D2:D9)= Science= 21.3.
- **Note:** Plain English answer
- **Why it matters:** English is the most consistent subject because it has the lowest standard deviation of 14.7.
- **Explained:** Question 3: Is there a relationship between maths and Science Science Scores?
- **Note:** Formula: CORREL(B2:B9,D2:D9) = Correlation (r) = O.998
- **Note:** Plain sentence answer: Maths and Science scores have an almost perfect positive correlation (r) = 0.998, meaning students who score highly in maths tends also to score highly in science
