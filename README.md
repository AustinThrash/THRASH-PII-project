# Overview

Objective: To identify key health indicators that predict the likelihood of an individual being diagnosed with diabetes using the CDC Diabetes Health Indicators dataset from 2014.

# Dataset Description:

Source: UC Irvine Machine Learning Repository, gathered from the CDC.
Size: Over 250,000 observations and 21 features.
Features include demographics (age, gender, income, education), health behaviors (smoking, drinking, physical activity), and health conditions (BMI, blood pressure, cholesterol).
Main Research Question: What are the key health indicators that predict diabetes diagnosis?

<https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators>

Cleaned dataset is included in project under "data/raw-data/diabetes.csv"

# Methods:

Data acquisition and cleaning.
Exploratory data analysis.
Statistical analysis using correlation matrices, logistic regression, decision trees, and machine learning classifiers.
Splitting data into training and test sets (80/20 split).

## Data Cleaning:

The code to clean the data is located under "code/processing-code/processingfile-v1.qmd"

Running it should produce a clean dataset under "data/processed-data/processeddata.rds"

## Data Exploration:

EDA code is located under "code/eda-code/EDA-Code.qmd"

This code will explore the data and generate tables and figures related to the exploration.
Figures are all located under "results/figures"

## Statistical Analysis:

All modeling and statistical analysis code is located under "code/analysis-code/statistical_analysis_code.qmd"

The code will fit the model and generate metrics that can be evaluated to compare models.

## Manuscript:

Located under "products/manuscript/Manuscript.qmd"

This file should be ran last and includes all figures made as well as the test results, can be viewed without running anything as all files and figures are included in the project.
