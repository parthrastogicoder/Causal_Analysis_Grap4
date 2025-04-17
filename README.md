# GRAP‑4 Impact on Delhi Air Quality

This repository contains the data, analyses, and write‑up for a causal inference study measuring the effect of the Graded Response Action Plan 4 (GRAP‑4) restrictions on Delhi’s Air Quality Index (AQI). Through a series of Difference‑in‑Differences (DiD) regressions, extended parallel‑paths and parallel‑growth checks, and placebo tests, we quantify and validate the policy’s immediate effectiveness in reducing pollution levels.

---

## 📂 Repository Structure

- **`data/`**  
  Raw and intermediate data files, including station‑level AQI readings across Delhi, neighbouring states, and other regions.

- **`reshaped_aqi_data.csv`**  
  Cleaned and reshaped dataset prepared for regression analyses.

- **`FINAL_FINAL.csv`**  
  Consolidated data with treatment indicators and time‑period flags for the DiD models.

- **`CI Term Paper.pdf`**  
  Full term paper detailing motivation, causal model, identification strategy, results, robustness checks, limitations, and conclusions.

- **`preprocessing.ipynb`**  
  Notebook demonstrating data cleaning steps, missing‑value imputation, and construction of treatment/control indicators.

- **`data_stats.ipynb`**  
  Exploratory data analysis: summary statistics, distribution plots, and station‑level comparisons.

- **`main.ipynb`**  
  Core analysis notebook implementing:
  - Canonical 2×2 DiD regression  
  - Extended DiD with multiple pre‑treatment periods  
  - Parallel paths vs. parallel growth diagnostics  
  - Placebo test using Bihar as a control  

---

## 🔍 Analysis Highlights

- **Treatment effect**: A statistically significant reduction in Delhi’s AQI by approximately 147 points one week after GRAP‑4 implementation.
- **Extended checks**: Validation of parallel‑trends through multiple pre‑treatment periods and calculation of double‑difference estimates.
- **Robustness**: Insignificant “effect” in a placebo test confirms the identification strategy’s credibility.

---

## 👤 Author

**Parth Sandeep Rastogi**  
IIIT‑Delhi | roll 2022352  
Email: parth22352@iiitd.ac.in

---
