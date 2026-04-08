# Variable Definitions

## Dataset
- **Dataset Name:** YRBS_2007.csv
- **Project Type:** Confidence Intervals and One-Sample Inference

---

# 1. Behavior Variable for Proportion Analysis

## Variable Name
`CurrentCigaretteUse`

## Variable Type
Categorical / Behavior Variable

## Purpose in This Project
This variable is used for the **population proportion analysis**.

## Statistical Question
Is the proportion of students who currently use cigarettes different from **0.20**?

## Meaning of the Variable
`CurrentCigaretteUse` measures whether a student has used cigarettes recently, based on the coding provided in the dataset.

## Original Coding Used
- **Code 1** = did not currently use cigarettes
- **Codes 2–7** = currently used cigarettes at some level
- Other values or missing values are treated as invalid / missing for the recoded analysis

## Binary Variable Created
`CurrentCigaretteUse_binary`

## Binary Coding Meaning
- **1** = success = student currently uses cigarettes
- **0** = failure = student does not currently use cigarettes

## Benchmark Value
- **Population benchmark proportion:**  
  \[
  p_0 = 0.20
  \]

## Final Use in Analysis
The recoded binary variable is used for:
- sample proportion
- confidence interval for population proportion
- one-sample proportion hypothesis test

---

# 2. Continuous Variable for Mean Analysis

## Variable Name
`BMIPCT`

## Variable Type
Continuous Variable

## Purpose in This Project
This variable is used for the **population mean analysis**.

## Statistical Question
Is the mean BMIPCT of students different from **65.0**?

## Meaning of the Variable
`BMIPCT` represents **Body Mass Index Percentile**.

## Valid Values Used
For this project, valid BMIPCT values are treated as:
- values from **0 to 100**

Values outside this range are treated as invalid and removed before analysis.

## Missing / Invalid Handling
The following values are excluded from analysis:
- missing values (`NaN`)
- non-numeric values
- values below 0
- values above 100

## Benchmark Value
- **Population benchmark mean:**  
  \[
  \mu_0 = 65.0
  \]

## Final Use in Analysis
This variable is used for:
- sample mean
- sample standard deviation
- confidence interval for population mean
- one-sample t-test

---

# 3. Notes on Final Sample Size

The final sample size may differ between variables because:
- some students may have missing responses
- some values may be invalid after cleaning
- the behavior and continuous variables are analyzed separately

Therefore, the final usable sample size should always be reported separately for:
- `CurrentCigaretteUse_binary`
- `BMIPCT`