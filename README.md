# DETE Employee Exit Survey Analysis

This project analyzes the employee exit survey data from the Department of Education, Training, and Employment (DETE), Queensland, Australia. It aims to uncover key drivers behind employee turnover, assess workplace experience, and provide actionable recommendations to improve retention.

---

##  Objective

- Identify major factors influencing employee exits (e.g., workload, dissatisfaction, relocation).
- Analyze workplace satisfaction indicators (e.g., morale, development, leadership).
- Evaluate demographic patterns (age, gender, background).
- Recommend data-backed HR strategies for retention.

---

##  Dataset Summary

- **Total Records**: 822
- **Columns**: 56
- **Sections**:
  - Personal & Employment Info
  - Reasons for Leaving
  - Workplace Experience Ratings
  - Demographics

---

##  Data Cleaning & Preprocessing

Performed using **Excel**:
- Replaced blanks and “Not Stated” with standard NA.
- Converted text ratings to numerical values (SA = 5 to SD = 1).
- Calculated tenure using:

'' Tenure = YEAR([Cease Date]) - YEAR([DETE Start Date])''

- Removed rows with missing critical dates.
- Validated consistency across columns.

---

##  Exploratory Data Analysis (EDA)

- Region-wise employee exits (bar chart)
- Classification level distribution
- Reason for exit (frequency analysis)
- Tenure analysis (avg by classification)
- Workplace satisfaction metrics (score distribution)
- Demographic breakdown (gender, age group, diversity)

**Refer to `Final_Presentation.pdf` for charts and detailed findings.**

---

##  Key Insights

- High dissatisfaction & workload concerns among short-tenure staff.
- Lack of promotion and recognition are consistent themes in exits.
- Peer support and supervisor performance rated positively overall.
- Female staff form the majority of exits; NESB & disability data underreported.

---

##  Tools Used

- Microsoft Excel – for data cleaning, transformation, and charts
- PowerPoint – final storytelling and visualization
- (Optional) Jupyter Notebook – for any additional statistical analysis

---

##  Recommendations

- Improve career progression paths and professional development.
- Enhance stress management and work-life balance programs.
- Target retention strategies for early-tenure employees.
- Increase engagement among underrepresented groups.

---

##  Repository Structure

| File                          | Description                              |
|-------------------------------|------------------------------------------|
| `Final_Presentation.pdf`      | Final project slides with all analysis   |
| `Raw_DETE_Data.xlsx`          | Original exit survey data                |
| `Cleaned_DETE_Data.xlsx`      | Preprocessed dataset for analysis        |
| `README.md`                   | Project summary (this file)              |

---





