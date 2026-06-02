# Ola-Driver-Attrition-Analysis

## Overview

This project focuses on analyzing driver attrition at Ola using historical driver data from 2019–2020. The objective was to identify the key factors influencing driver churn and provide actionable business recommendations to improve driver retention.

## Problem Statement

Driver attrition is a major challenge for ride-hailing companies. Losing experienced drivers increases acquisition costs and affects operational efficiency. This project analyzes driver demographics, performance metrics, and income trends to understand why drivers leave and what factors contribute to long-term retention.

## Dataset

The dataset contains monthly records of Ola drivers, including:

* Driver ID
* Age
* Gender
* City
* Education Level
* Income
* Date of Joining
* Last Working Date
* Grade
* Quarterly Rating
* Total Business Value

## Project Workflow

### 1. Data Cleaning & Preprocessing

* Handled missing values using appropriate imputation techniques.
* Converted date columns into datetime format.
* Created an Attrition Flag based on Last Working Date.
* Removed inconsistencies and prepared data for analysis.

### 2. Feature Engineering

Created meaningful features such as:

* Driver Tenure
* Income Growth Indicator
* Rating Improvement Indicator
* Attrition Status

### 3. Exploratory Data Analysis (EDA)

Performed detailed analysis on:

* Age Distribution
* Income Distribution
* Business Value Trends
* Quarterly Rating Analysis
* Driver Tenure Analysis
* Attrition Distribution

### 4. Correlation & Relationship Analysis

Investigated relationships between:

* Age and Income
* Education and Business Value
* Rating and Tenure
* Income Growth and Attrition
* Rating Improvement and Attrition

## Key Findings

* Drivers with lower income were more likely to leave the company.
* Higher-rated drivers generally stayed longer.
* Income growth had a positive impact on driver retention.
* Rating improvement was associated with lower attrition.
* Early-tenure drivers showed a higher likelihood of leaving.

## Business Recommendations

* Introduce performance-based incentive programs.
* Provide retention bonuses for long-tenure drivers.
* Monitor low-rated drivers and offer targeted support.
* Create income growth opportunities to improve driver satisfaction.
* Implement city-specific retention strategies.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Business Insight Generation

## Project Outcome

The analysis identified income, performance ratings, and tenure as the most influential factors affecting driver attrition. The insights generated can help Ola develop targeted retention strategies and reduce driver churn.
