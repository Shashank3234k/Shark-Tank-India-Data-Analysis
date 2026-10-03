# Startup Investment Analysis — Shark Tank India

## Objective

Analyze Shark Tank India startup investment data to identify funding patterns, investor participation, deal success rates, valuation trends, and startup funding behavior.

## Tools Used

* Python
* Pandas
* NumPy
* Tableau
* Jupyter Notebook

## Dataset

**Shark Tank India Dataset**

* 117 startup pitches
* 28 attributes
* Funding, valuation, equity, deal, and shark participation information

## Project Workflow

### 1. Data Inspection

* Loaded the Shark Tank India dataset.
* Examined dataset dimensions, columns, and data types.
* Checked for missing values.
* Checked for duplicate records.

### 2. Data Quality Assessment

* No missing values were found.
* No duplicate records were found.
* Numeric and categorical columns were verified.
* Dataset required minimal preprocessing.

### 3. Investment Analysis

Analyzed:

* Total startups and successful deals
* Deal success rate
* Total funding
* Average funding per startup
* Ask amount vs. actual deal amount
* Ask valuation vs. deal valuation
* Number of sharks participating in each deal

### 4. Investor Analysis

Analyzed shark participation using individual investor deal columns to identify investment activity across the sharks.

### 5. Startup Funding Analysis

Identified the startups receiving the highest deal amounts and compared funding patterns across startups.

## Key Findings

| Metric            |       Result |
| ----------------- | -----------: |
| Total Startups    |          117 |
| Successful Deals  |           65 |
| Deal Success Rate |       55.56% |
| Total Funding     | ₹3,742 Lakhs |
| Average Funding   | ₹31.98 Lakhs |
| Duplicate Rows    |            0 |
| Missing Values    |            0 |

### Investor Participation

Based on the analyzed deal records:

* Aman — 28 deals
* Peyush — 27 deals
* Anupam — 24 deals
* Namita — 22 deals
* Ashneer — 21 deals
* Vineeta — 15 deals
* Ghazal — 7 deals

### Top Funding

The highest deal amount identified was:

**Aas Vidyalaya — ₹150 Lakhs**

Several other startups received deals of ₹100 Lakhs.

## Shark Collaboration Analysis

| Sharks Invested | Startups |
| --------------: | -------: |
|               0 |       52 |
|               1 |       22 |
|               2 |       20 |
|               3 |       14 |
|               4 |        5 |
|               5 |        4 |

This analysis shows how frequently startups received investments from one or multiple sharks.

## Tableau Dashboard

The dashboard will visualize:

* Investment KPIs
* Shark-wise investment activity
* Deal success rate
* Top funded startups
* Ask amount vs. deal amount
* Valuation comparison
* Number of sharks per deal
* Funding trends

## Deliverables

* Python analysis notebook
* Cleaned dataset
* Tableau dashboard
* Industry/investor trend report
* Founder/startup success pattern summary

## Conclusion

This project analyzes Shark Tank India investment data to understand startup funding behavior and investor participation. The analysis combines Python-based data analysis with Tableau visualization to transform startup investment data into meaningful business insights.
