# Appalytica

## Project Overview

Appalytica analyzes sales and customer behavior from a React Native application, focusing on app crash reports, downloads, and active user counts. The analysis compares global and country-specific performance across Android and iOS platforms.

## Data Analysis Approach

This project uses a Python notebook for a comprehensive analysis, including:

- **Data Cleaning & Preprocessing:** Handling missing values, converting data types, and interpolating time-series data.
- **Exploratory Data Analysis (EDA):** Statistical summaries, distribution plots, box plots, and correlation heatmaps.
- **Time Series Decomposition:** Trend, seasonality, and residual analysis for Android and iOS, including country-specific breakdowns (KSA, UAE, Egypt, Qatar).
- **Advanced Visualization:** Moving averages, growth rates, cumulative downloads, and market share analysis.
- **Hypothesis Testing:** Statistical tests (t-tests, ANOVA, correlation) to validate:
  1. Android converts better than iOS.
  2. Higher crash rates depress conversion (especially on iOS).
  3. KSA leads in downloads; UAE is second; Egypt & Qatar are steady.
  4. Acquisition spikes do not guarantee conversion lifts (iOS risk).
- **Recommendations:** Platform strategy, monitoring priorities, data quality improvements, and business insights for market prioritization.

## Key Insights

- **Android generally outperforms iOS in conversion and downloads.**
- **Crash rates negatively impact conversion, with a stronger effect on iOS.**
- **KSA is the top-performing country, followed by UAE.**
- **Consistent data collection and anomaly detection are recommended for ongoing improvement.**

## Usage

- The main analysis is in `source_code/solution.ipynb`.
- Data is loaded from `dataset/BigData Data - Sheet1.csv`.
- See `deliverables/` for presentation and report.

## Technologies Used

- Python (pandas, numpy, matplotlib, seaborn, scipy, statsmodels)
- Jupyter Notebook

## Deliverables

- Data analysis notebook
- Presentation and report summarizing findings

---

For details, see the notebook and deliverables in this repository.
