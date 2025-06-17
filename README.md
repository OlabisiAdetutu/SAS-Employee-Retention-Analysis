# SAS-Employee-Retention-Analysis


This project utilizes an HR dataset in SAS to uncover insights into employee satisfaction, turnover, and workplace patterns.

---

##  Overview

The aim of this project is to perform a comprehensive analysis of an HR dataset using SAS programming. The dataset contains employee-related attributes such as satisfaction level, evaluation scores, number of projects, and more.

By leveraging SAS procedures (e.g., `PROC IMPORT`, `PROC FREQ`, `PROC MEANS`), we conduct a structured exploration to identify factors influencing employee retention and performance. This serves as a foundation for future predictive modeling or HR policy recommendations.

---

##  Motivation

Employee turnover is costly and disruptive. Many organizations struggle to understand why employees leave or stay.

**This project was inspired by three key questions:**

1. What features most differentiate employees who leave vs. those who stay?
2. Are there early signals of employee dissatisfaction?
3. Can we use statistical tools (like SAS) to build a decision-support tool for HR?

---

##  Technical Aspects

- **Language:** SAS
- **Platform:** SAS Studio / SAS Base
- **Procedures Used:**  
  - `PROC IMPORT`: For CSV loading  
  - `PROC CONTENTS`: To view structure  
  - `PROC PRINT`: For quick data previews  
  - `PROC FREQ`: For categorical distributions  
  - `PROC MEANS`: For summarizing numeric variables  

 The code is modular and readable, divided into clear steps:
1. Import data  
2. Explore structure and contents  
3. Analyze distributions  
4. Identify missing data  
5. Set the stage for advanced analysis

---

##  How to Run

1. Open [SAS Studio](https://odamid.oda.sas.com/) or your local SAS environment.
2. Upload both:
   - `HR_comma_sep.csv` → `/folders/myfolders/`
   - `HR_dataset_cleaned.sas` → Your code folder
3. Adjust the `FILENAME REFFILE` path in the script if needed.
4. Run the code step-by-step to explore, analyze, and understand the dataset.

---

##  Dataset Description

The dataset consists of 10 columns related to employee behavior and status:

| Column Name              | Description                            |
|--------------------------|----------------------------------------|
| satisfaction_level       | Employee satisfaction score (0–1)     |
| last_evaluation          | Last performance evaluation (0–1)     |
| number_project           | Number of projects completed          |
| average_montly_hours     | Monthly working hours                 |
| time_spend_company       | Years at the company                  |
| Work_accident            | 1 = had accident, 0 = no accident     |
| left                     | 1 = left company, 0 = still employed  |
| promotion_last_5years    | 1 = promoted in last 5 years          |
| sales                    | Department                            |
| salary                   | Salary category: low, medium, high    |

---

##  Project Structure


HR-Analytics-SAS/
├── data/
│   └── HR_comma_sep.csv             # Original HR dataset (CSV format)
│
├── code/
│   └── HR_dataset_cleaned.sas       # Main SAS analysis script (well-structured)
│
├── README.md                        # Project overview and documentation










---

##  Author

**Adetutu Olabisi**  
MSc Data Science  
 Based in the UK |  Originally from Nigeria  
 | [LinkedIn](linkedin.com/in/adetutu-olabisi)

---

##  License

This project is provided for educational and academic use only.  
Please do not use this dataset for commercial applications.

---

> _“Without data, you're just another person with an opinion.” – W. Edwards Deming_
