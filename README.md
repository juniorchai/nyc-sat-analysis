# 🗽 NYC High School SAT Performance — EDA

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-EDA-lightblue) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Overview
Exploratory data analysis of **375 NYC public high schools** using SAT score data.  
The project identifies top-performing schools, compares borough-level trends, and explores relationships between subjects and participation rates.

## Research Questions
| # | Question |
|---|----------|
| 1 | Which schools score ≥80% on the Math section (≥640)? |
| 2 | What are the Top 10 schools by combined SAT score? |
| 3 | Which borough has the largest variation in SAT performance? |
| 4 | How do boroughs compare across Math, Reading, and Writing? |
| 5 | How correlated are the three SAT subjects? |
| 6 | Does participation rate affect overall SAT scores? |

## Key Findings
- 🏆 **10 schools** hit the Math threshold; Stuyvesant leads at **754**
- 📊 **Manhattan** has the most unequal SAT scores (std = 230)
- 🗺️ **Staten Island** scores highest across all subjects; Bronx scores lowest
- 📈 Reading & Writing are near-perfectly correlated (**r = 0.99**)
- 📉 Higher participation → lower scores (**r = -0.38**) — selective schools skew the data

## Visualizations
| Chart | Insight |
|-------|---------|
| Best Math Schools (bar) | 10 schools above threshold |
| Top 10 Combined SAT (bar) | Stuyvesant dominates |
| Std Dev by Borough | Manhattan most unequal |
| Subject Scores by Borough | Staten Island leads all 3 |
| Math vs Reading scatter | Strong correlation (r=0.93) |
| Participation vs Score scatter | Negative correlation (r=-0.38) |

## Tools & Libraries
- **Python 3.9** · **Pandas** · **NumPy** · **Matplotlib**

## Dataset
`schools.csv` — 375 NYC public high schools with SAT averages  
*(DataCamp Project — extended with additional analysis)*

## How to Run
```bash
git clone https://github.com/junior-wong/nyc-sat-analysis
cd nyc-sat-analysis
pip install pandas numpy matplotlib
jupyter notebook nyc_sat_extended.ipynb
```

---
*Part of my Data Analytics Portfolio — [github.com/junior-wong](https://github.com/junior-wong)*
