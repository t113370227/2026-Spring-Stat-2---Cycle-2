# Recoding Rules

## Dataset
- **Dataset Name:** YRBS_2007.csv

This file documents the cleaning and recoding rules used in this project.

---

# 1. General Data Cleaning Rules

The following general cleaning steps were applied before analysis:

- variables used in the project were converted to numeric where necessary
- missing values were kept as missing (`NaN`)
- invalid values were excluded from the final analysis
- cleaned data were saved as:

```text
data/processed/yrbs_cleaned.csv