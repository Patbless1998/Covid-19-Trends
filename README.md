# COVID-19 Global Testing and Positivity Analysis

This project analyzes a global COVID-19 dataset to identify trends in testing and positivity rates across countries.

## 📌 Overview

In this analysis, I:
- Loaded and explored real COVID-19 data
- Cleaned the dataset to remove missing or incomplete records
- Aggregated results by country
- Identified the top 10 countries with the highest total tests and positivity rates
- Created visualizations to highlight key insights
- Compiled results into a structured R list

## 🧰 Tools and Libraries

- **R** (via RStudio)
- `dplyr`, `readr`, `tibble`, `ggplot2`, `janitor`
- Git & GitHub for version control

## 📊 Key Findings

- The **United States** conducted the highest number of COVID-19 tests globally.
- **Mexico** and **Iran** had the highest positivity rates among countries with >100,000 tests, indicating possible under-testing.
- Visualizations and summary statistics provide insight into testing efforts and case detection efficiency.

## 📁 Files Included

- `covid_data.Rmd` – Source R Markdown file
- `covid_data.html` – Rendered report (HTML)
- `tested_worldwide.csv` – Original dataset
- `README.md` – This file

## 📈 Dataset Source

[COVID-19 Worldwide Testing Dataset on Kaggle](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

## ✅ How to Run

1. Open `covid_data.Rmd` in RStudio.
2. Run each chunk or use **Knit** to generate the final report.
3. View `covid_data.html` for the visualized output.

---

> This is a beginner-level portfolio project to demonstrate foundational data analysis skills in R.
