# Predictors of Economic Recovery: Digital vs. Demographic (2022)

## Project Overview
This repository contains the analysis and machine learning models used for my Capstone Research Paper. The project examines 179 countries to determine which structural factors—Digital (Broadband/Mobile) or Demographic (Urbanization/Education)—best predicted GDP growth in the post-pandemic recovery year of 2022.

## Key Findings
- **Urbanization** is the leading predictor of 2022 economic recovery.
- **Mobile Connectivity** is significantly more influential than fixed **Broadband**.
- The 2022 recovery was highly volatile, with tourism-dependent island nations leading the growth charts.

## Methodology
- **Data Source:** World Bank API (`wbgapi`)
- **Model:** Random Forest Regressor (Scikit-Learn)
- **Programming:** Python (Pandas, Seaborn, Matplotlib)

## Repository Structure
- `analysis.ipynb`: The main Python notebook containing data acquisition and the ML model.
- `capstone_final_data.csv`: The cleaned dataset used for the final paper.
- `descriptive_stats.csv`: Statistical summary of the 179 countries.

## Installation & Usage
1. Clone this repo: `git clone https://github.com/anuska-mukherjee/capstone-recovery.git`
2. Install dependencies: `pip install wbgapi pandas scikit-learn seaborn matplotlib`
3. Run the notebook to fetch live data and reproduce the model results.

## Author
Anuska Mukherjee
Capstone Project - GIAP Data Analytics
