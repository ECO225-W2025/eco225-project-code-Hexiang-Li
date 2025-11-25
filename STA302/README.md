# STA302 Final Project: University Ranking & Factors Analysis

This project was completed as part of **STA302: Regression Analysis** at the University of Toronto.  
The objective of this analysis is to investigate how different institutional attributes (e.g., faculty/student ratio, international student percentage, research reputation) influence global university rankings.

---

## Methods

Parts of methods for model evaluation:
- Cross-validation
- Residual diagnostic analysis
- partial F tests

---

## Project Structure
STA302/
│── README.md ← You are here
│── proposal.pdf ← Research proposal
│── final_report.pdf ← Final written report
│── data/
│ └── QS_2025.csv ← QS World University Rankings dataset
│── code/
│ ├── STA302_FINAL_CODE__.Rmd ← Final analysis in R Markdown

---

## Dataset

**Source:** QS World University Rankings 2025  
Includes features such as:
- Academic Reputation Score
- Employer Reputation Score
- Faculty/Student Ratio
- Citations per Faculty
- International Faculty & Student %  

The dataset is already cleaned and stored in:  
`/data/QS_2025.csv`

---

## Technologies Used

- **R (tidyverse, readr, boot, and etc)**
- **Git & GitHub**

---

## Key Findings

- Employer Reputation is the strongest predictor of academic reputation, indicating that universities are judged heavily by graduate success and industry perception.

- International Research Networks and Citations significantly increase academic reputation, showing that global collaboration and research impact are key drivers of prestige.

- Sustainability and Employment Outcomes also contribute positively, suggesting that modern reputation reflects societal responsibility and practical value—not just academic output.

- International Student Ratio and Faculty Student Ratio are not significant, meaning diversity and class size do not meaningfully influence reputation once other factors are considered.

---

### ⭐ If you like this analysis, feel free to star this repository!

