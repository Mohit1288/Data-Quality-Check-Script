# Data Quality Check Script

## Overview

This script performs essential data quality checks on a given CSV dataset. The aim is to detect common data issues, including missing values, duplicate rows, and outliers in numerical columns. The script generates a detailed summary report to assist in data assessment.

---

## Features

### The script performs the following data quality checks:
1. **Missing Values**
   - Identifies columns with missing values.
   - Outputs the count of missing values for each column.

2. **Duplicate Rows**
   - Identifies duplicate rows in the dataset.
   - Outputs the total number of duplicate rows.

3. **Outlier Detection**
   - Detects outliers in numerical columns using the Interquartile Range (IQR) method.
   - Outputs the number of outliers detected for each numerical column.

---

## Requirements

- Python 3.6 or later
- Required libraries:
  - `pandas`
  - `numpy`

### Installation
To install the required libraries, run:
```bash
pip install pandas numpy
```

---

## Directory Structure

```
project_directory/
│
├── data/
│   └── wine.csv
│
├── result/
│   └── data_quality_report.txt

```

### Instructions
1. Place the `wine.csv` dataset in the `data/` folder.
2. Run the script `data_quality_check.py` to perform the data quality checks.
3. The summary report will be saved automatically in the `result/` folder as `data_quality_report.txt`.

--- 
