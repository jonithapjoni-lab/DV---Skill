# week 11 - Automobile Dataset Analysis and Data Cleaning

## 1. Introduction
The Automobile Dataset contains technical specifications, engine characteristics, fuel consumption details, and pricing information about different automobile models.

This project focuses on cleaning and analyzing automobile data using Python.

## 2. Objectives
- Understand the automobile dataset.
- Identify and handle missing values.
- Remove invalid characters.
- Convert columns into correct data types.
- Calculate Power-to-Weight Ratio.
- Calculate Combined MPG.
- Analyze automobile body styles.
- Analyze engine locations.
- Export the cleaned dataset.

## 3. Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 4. Dataset
**Dataset Name:** Automobile Dataset

The dataset contains information about:
- Car manufacturers
- Horsepower
- Engine size
- Fuel consumption
- Vehicle weight
- Body style
- Engine location
- Price

## 5. Project Workflow

### Step 1: Import Libraries
Imported Pandas, NumPy, Matplotlib, and Seaborn.

### Step 2: Load Dataset
Loaded the Automobile dataset using Pandas.

### Step 3: Explore Dataset
- Displayed first five records.
- Displayed last five records.
- Checked dataset shape and columns.
- Viewed dataset information.
- Generated statistical summary.

### Step 4: Data Cleaning
- Replaced '?' with missing values.
- Identified missing values.
- Converted numerical columns.
- Filled missing values using manufacturer-wise median.
- Used overall median for remaining missing values.

### Step 5: Data Type Conversion
Converted horsepower, peak-rpm, price, bore, and stroke into appropriate numerical data types.

### Step 6: Feature Engineering
Created two new columns:

1. **Power-to-Weight Ratio**
   - Calculated using horsepower and curb weight.

2. **Combined MPG**
   - Calculated using city MPG and highway MPG.

### Step 7: Data Analysis
Performed analysis based on:
- Body Style Analysis
- Engine Location Analysis

Calculated average horsepower, engine size, curb weight, price, and combined MPG.

### Step 8: Final Data Validation
- Checked remaining missing values.
- Checked duplicate records.
- Displayed the final cleaned dataset.

### Step 9: Export Dataset
Saved the cleaned dataset as:

`automobile_cleaned.csv`

## 6. Expected Output
- Cleaned automobile dataset.
- Missing values handled.
- Correct numerical data types.
- New calculated features.
- Body style analysis.
- Engine location analysis.
- Exported CSV file.

## 7. Conclusion
This project demonstrates how Python can be used for automobile dataset cleaning, preprocessing, feature engineering, and analysis.

The cleaned dataset is ready for further data analysis and exploration.
