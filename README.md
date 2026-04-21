# HW 4.3 — STAT 184: Reproducible Data Analysis
**Author:** James Leveque  
**Date:** April 2026

## About This Repository
This repository hosts the work from Homework 4.3, with the data analysis from that assignment. Also, this repository 
establishes a history of version control regarding Homework 4.3. 

## Repository Maintenance Plan
- Work is completed in the hw4.3_work branch and then sent to the README branch
- Issues are tracking tasks that need to be completed/have been completed.
- Commit messages describe exactly what changed and why
- The `main` branch only receives work that is fully completed. 

## HW 4.3 Analysis Plan
This assingment consisted of three different analyses of datasets from previous homeworks:

**1. Busiest Airports Analysis**
Collected annual passenger data (2020–2025) for six major airports from Wikipedia
and ACI. I built a table and line chart showing the annual data from each airport.
With this data, I highlighted the impact of COVID and how different airports recovered 
or were impacted from the pandemic. Overall, Atlanta consistently led while Dubai showed the steepest 
relative recovery.

**2. Monte Carlo Numerical Integration**
Used random sampling to estimate the integral of a Beta(2,2) PDF over [0,1].
Ran simulations at n = 10, 100, 1,000, and 10,000 points to show how accuracy
improves with sample size. True value is 1.0; estimate at n = 10,000 was 1.0015.

**3. GenAI Prompting**
Compared a detailed plan-informed prompt vs. a generic prompt given to Claude
AI for tidying and visualizing a calcium dataset that was given. The plan-informed
response produced correctly labeled, interpretable output while the generic
response used poorly created labels using generic terms "Group A", and informal output.

## Files
- `hw43JL.qmd` — Quarto source file containing all code and narrative
- `hw43JL.pdf` — Rendered PDF submitted for HW 4.3
