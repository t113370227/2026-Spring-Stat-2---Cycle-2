# Project Cycle 2

## Group Information
- **Group Number:** [1]
- **Member Names:** [113370227,112310316]

---

## Project Overview
This project is based on **YRBS_2007.csv** and focuses on:

- **confidence intervals**
- **one-sample inference**
- **exploratory data analysis (EDA)**

The goal is to answer one statistical question about a **population proportion** and one statistical question about a **population mean**.

---

## Dataset Used
- **Dataset:** `YRBS_2007.csv`

---

## Selected Variables

### 1. Behavior Variable for Proportion Analysis
- **Variable:** `CurrentCigaretteUse`
- **Recoded Variable:** `CurrentCigaretteUse_binary`
- **Meaning of Success:** student currently uses cigarettes
- **Benchmark Proportion:**  
  \[
  p_0 = 0.20
  \]

### 2. Continuous Variable for Mean Analysis
- **Variable:** `BMIPCT`
- **Meaning:** Body Mass Index Percentile
- **Benchmark Mean:**  
  \[
  \mu_0 = 65.0
  \]

---

## Research Questions

### Proportion Analysis
Is the proportion of students who currently use cigarettes different from **0.20**?

### Mean Analysis
Is the mean BMIPCT of students different from **65.0**?

---

## Project Structure

```text
project-cycle-2/
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── summary/
├── report/
└── references/