# Excel Mini Project: Data Cleaning

## Overview
This mini project demonstrates essential data cleaning tasks performed using Microsoft Excel. The objective was to prepare a small, inconsistent dataset for downstream analysis by applying standard cleaning techniques, formatting corrections, and text normalization.

## Key Cleaning Steps

### 1. **Standardized Text Case**
- **Column Cleaned:** `President`
- **Issue:** Names were inconsistently capitalized (mix of upper and lower case).
- **Fix:** Used the `UPPER()` function to convert all names to uppercase for consistency.

### 2. **Special Character Replacement**
- **Column Cleaned:** `Prior`
- **Issue:** Contained special character `â€“` instead of a standard hyphen `-` in date ranges.
- **Fix:** Used `REPLACE()` function to clean and standardize to a valid hyphen format.

### 3. **Whitespace Trimming**
- **Column Cleaned:** `Vice President`
- **Issue:** Contained multiple irregular/unreal spaces.
- **Fix:** Applied the `TRIM()` function to remove all leading, trailing, and excess spaces.

### 4. **Data Type Normalization**
- **Column Cleaned:** `Salary`
- **Issue:** Column was set to a custom data type format that could interfere with calculations.
- **Fix:** Converted to numeric data type for consistent mathematical operations.

### 5. **Date Formatting**
- **Column Cleaned:** `Date`
- **Issue:** Mixed use of long and short date formats across rows.
- **Fix:** Standardized entire column to **short date format** to ensure uniformity.

## Files Included
- `Uncleaned Data Set.xlsx` – Original dataset with raw inconsistencies
- `Cleaned Data Set.xlsx` – Cleaned version after applying all transformations

## Tools Used
- **Microsoft Excel**
  - Text Functions: `UPPER()`, `TRIM()`, `REPLACE()`
  - Format Cells: Number, Date
  - Manual column value pasting after transformations

## Purpose
This exercise demonstrates hands-on familiarity with data cleaning principles — an indispensable step in any data analytics pipeline. Although the dataset is small, the approach reflects practical best practices for preparing structured data.

---

