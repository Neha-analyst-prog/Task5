# Titanic Dataset
Exploratory Data Analysis

## Overview
Exploratory Data Analysis on Titanic dataset using Python (Pandas, Matplotlib, Seaborn). The goal is to extract patterns, visualize distributions, detect anomalies, and summarize insights.

## Files
- `Task5.ipynb` — colab notebook with step-by-step EDA and plots.
- `titanic_eda_cleaned.csv` — cleaned dataset exported from the notebook.
- Task5_Code and Output.pdf
- `README.md` — this file.

## How to run
1. Clone the repo
2. `pip install -r requirements.txt` (or use conda)
3. Run `jupyter notebook` and open `titanic_eda.ipynb`

## Summary of findings
- Females had higher survival rate than males.
- Passengers in Pclass 1 had the best survival chances.
- Fare is highly skewed; log transform recommended for modeling.
- Age has missing values; consider improved imputations.
