## Portugal Real Estate Data Analysis Project

## Project Overview

This project focuses on **data cleaning, exploratory data analysis (EDA), and business insight generation** using a large-scale real estate dataset from Portugal.  
The analysis supports **data-driven decision-making** to help a real estate company achieve a **10% increase in property sales within 6 months**.

## Business Objective

The main business objective of this project is:

**To identify market trends and key pricing factors that can increase property sales in Portugal by 10% within a 6-month period.**

---

## Data Source

The dataset used in this project is **Portugal Real Estate Listings 2024**, sourced from Kaggle.

- **Source**: Kaggle  
- **Dataset Link**: https://www.kaggle.com/datasets/luvathoms/portugal-real-estate-2024  
- **Initial Dataset Size**:
  - 135,536 rows  
  - 25 columns  

The dataset includes property price, district, property type, total area, number of bedrooms, energy certificate, parking availability, and other listing attributes.

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Jupyter Notebook / Google Colab  
- Google Spreadsheet (Pivot Tables & Aggregation)  
- Google Slides (Business Presentation)

---

## Project Workflow

### 1. Data Understanding
- Reviewed dataset structure using `df.info()` and `df.describe()`
- Identified missing values, incorrect data types, and outliers
- Evaluated column relevance for analysis and business use

---

### 2. Data Cleaning & Preparation

The following data cleaning steps were performed:

1. Calculated missing value counts and percentages  
2. Dropped columns with **more than 70% missing values**  
3. Removed rows with missing values in the `Price` column  
4. Handled missing values:
   - Numerical columns filled with **median**
   - Categorical columns filled with **mode**
5. Standardized data types:
   - Numerical → `int` / `float`
   - Categorical → `object`
   - Boolean → `bool`

**Dataset after cleaning:**
- Rows: 135,236  
- Columns: 19  
- No missing values  
- Consistent and analysis-ready schema

---

### 3. Exploratory Data Analysis (EDA)

Key analysis topics include:

- Property price distribution
- Average price by district
- Property type availability
- Impact of property size and number of bedrooms on price
- Market price segmentation (low, medium, high)
- Impact of energy certificate on property price
- Impact of parking availability on property price

---

## Project Deliverables
- Jupyter Notebook: Data cleaning & EDA using Python
- Google Spreadsheet: Pivot tables and aggregated analysis
- Google Slides: Business insight presentation

Links:
Spreadsheet: https://docs.google.com/spreadsheets/d/1a1KJ3pINz5a0BGdunkJhEjNX7r24S53u1xTwVv6ntVY
Slides: https://docs.google.com/presentation/d/1KpxMMYi_yI8ObgFf5tF6B_SKTdm_vHGO

---

## Role & Skill Highlight

This project demonstrates skills in:
- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- Business Problem Translation into Data Questions
- Spreadsheet-based Analysis & Reporting
- Insight Generation & Actionable Recommendations
