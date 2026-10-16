# Titanic EDA & Survival Analysis using Python

An Exploratory Data Analysis (EDA) project on the Titanic passenger dataset (`tested.csv`) submitted for **Task 3 of the Data Science with Python Internship at Maincrafts Technology**.


## Project Overview
This project addresses real-world data quality issues—such as missing values and unorganized attributes—by applying data cleaning, imputation, and feature engineering to uncover key demographic and socio-economic factors influencing passenger survival.

### Key Deliverables:
1. **Data Imputation:** Imputed missing `Age` values using mean imputation and missing `Fare` values using median imputation. Dropped the sparse `Cabin` feature.
2. **Feature Engineering:**
   * `AgeGroup`: Binned ages into `Child`, `Teen`, `YoungAdult`, `Adult`, and `Senior`.
   * `FamilySize`: Combined family counts ($\text{SibSp} + \text{Parch} + 1$).
   * `Title`: Extracted honorifics (`Mr`, `Mrs`, `Miss`, `Master`, `Rare`).
3. **Exploratory Visualizations:** Generated 6 distinct individual charts detailing passenger distributions, survival proportions, and correlation structures.


## Key Insights & Analytical Findings
* **Age Demographics:** Children (0–12 years) achieved a higher survival rate (**48.0%**) compared to young adults (**36.3%**).
* **Family Size Impact:** Small family units (2–4 members) had significantly higher survival chances (up to **71.4%**) compared to solo travelers (**26.9%**).
* **Port of Embarkation:** Passengers embarking from Queenstown (Q) had the highest survival percentage (**52.2%**).
