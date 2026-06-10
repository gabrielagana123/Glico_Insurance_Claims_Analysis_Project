# Healthcare Insurance Claims Analytics Dashboard

## Project Overview

This project analyzes healthcare insurance claims data for employees insured under a corporate health insurance scheme. The objective is to understand healthcare utilization patterns, identify major cost drivers, detect potential abuse of insurance benefits, and provide actionable recommendations for healthcare cost management.

As a Data Analyst at GLICO Healthcare with a background in Pharmacy, I leveraged healthcare domain knowledge and data analytics techniques to evaluate employee claims behavior, provider utilization patterns, medication trends, and insurance limit exceedances.

---

## Business Problem

Employees of Concentrix Ghana are enrolled in a corporate health insurance plan administered by GLICO Healthcare. While health insurance improves access to healthcare services, it also introduces challenges such as:

* Excessive healthcare utilization
* Potential abuse of insurance benefits
* High-cost providers
* Rising claims expenditure
* Use of pediatric medications by adult beneficiaries
* Difficulty identifying high-risk claimants

The organization seeks to answer the following questions:

1. How much is being spent on healthcare claims?
2. Which providers account for the highest costs?
3. What percentage of claims originate from hospitals versus pharmacies?
4. How much do admissions contribute to overall healthcare costs?
5. What proportion of claims involve pediatric medications?
6. Which employees frequently exceed their monthly insurance limits?
7. Are demographic factors such as marital status and number of children associated with higher utilization?

---

## Dataset

A realistic synthetic healthcare insurance dataset was generated to simulate employee healthcare utilization throughout 2025.

### Fact Table

**Claims_Data**

Contains:

* Claim ID
* Employee ID
* Visit Date
* Provider Name
* Facility Type
* Diagnosis
* Drug Name
* Drug Category
* Quantity
* Unit Price
* Total Cost
* Claim Status
* Admission Status

### Dimension Tables

#### Employees

Contains:

* Employee ID
* Gender
* Age
* Marital Status
* Number of Children
* Department
* Job Level
* Insurance Monthly Limit

#### Providers

Contains:

* Provider Name
* Facility Type
* Ownership Type

#### Drugs

Contains:

* Drug Name
* Drug Category
* Formulation
* Therapeutic Class

---

## Tools Used

* Microsoft Excel

  * Data Cleaning
  * Exploratory Data Analysis (EDA)
  * Pivot Tables
  * Data Validation

* Power BI

  * Data Modeling
  * DAX Measures
  * Interactive Dashboard Development
  * Data Visualization

---

## Data Preparation

The following preprocessing steps were performed:

* Data type validation
* Missing value checks
* Creation of Year-Month reporting periods
* Cost variance calculations
* Insurance limit analysis
* Claims aggregation by employee and month
* Provider utilization analysis
* Medication categorization

---

## Key Metrics

The dashboard tracks:

* Total Claims
* Total Healthcare Cost
* Total Admissions
* Total Pediatric Claims
* Total Adult Claims
* Cost Variance
* Percentage Hospital Claims
* Percentage Pharmacy Claims
* Percentage Pediatric Claims
* Percentage Adult Claims
* Percentage Cost Contribution by Provider Type
* Employee Insurance Limit Exceedance Rate

---

## Dashboard Pages

### Page 1: Claims Overview

Provides a high-level summary of healthcare utilization.

Visuals include:

* Total Claims KPI
* Total Cost KPI
* Total Admissions KPI
* Hospital vs Pharmacy Claims
* Hospital vs Pharmacy Cost Contribution
* Pediatric vs Adult Claims Distribution
* Monthly Cost Trend
* Provider Cost Analysis

### Page 2: Employee Utilization Analysis

Focuses on employee behavior and potential abuse patterns.

Visuals include:

* Top Chronic Exceeders
* Insurance Limit Exceedance Rate
* Exceedance by Job Level
* Exceedance by Marital Status
* Exceedance by Number of Children
* Monthly Exceedance Trends

---

## Key Insights

The analysis aims to identify:

* Employees who consistently exceed monthly insurance limits
* Providers contributing disproportionately to healthcare expenditure
* Cost differences between hospital and pharmacy visits
* Impact of admissions on total claims cost
* Utilization patterns across demographic groups
* Potential misuse of pediatric medications

---

## Recommendations

Based on the findings, GLICO Healthcare can:

1. Monitor employees with repeated limit exceedances.
2. Audit providers with unusually high average claim costs.
3. Implement utilization alerts for employees approaching monthly limits.
4. Review pediatric medication claims submitted by adult beneficiaries.
5. Strengthen provider cost controls and reimbursement policies.
6. Develop targeted wellness programs for high-utilization groups.

---

## Project Outcome

This project demonstrates how healthcare insurance data can be transformed into actionable business insights using Excel and Power BI. The resulting dashboard supports data-driven decision-making for insurers, employers, healthcare providers, and policy administrators.

---

## Author

Gabriel Agana

Doctor of Pharmacy Candidate | Data Analyst | Machine Learning Enthusiast

Kwame Nkrumah University of Science and Technology (KNUST)
