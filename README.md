# Temporal Probability of Default Modeling for Mortgage Risk

This repository contains my postgraduate dissertation project focused on Temporal Probability of Default (PD) modeling for mortgage risk using large-scale loan-level mortgage data from the Freddie Mac dataset.

The project combines large-scale data engineering, predictive modeling, temporal validation, and calibration techniques to assess borrower default behavior under changing economic conditions.

---

## Project Overview

The objective of this study was to build an interpretable and economically meaningful mortgage default prediction framework capable of assessing borrower credit risk across different time horizons and macroeconomic scenarios.

The workflow involved:

- Processing large-scale Freddie Mac mortgage performance datasets
- Converting raw fixed-width/text files into optimized Parquet format
- Building analytical datasets using DuckDB for high-performance querying
- Comparing Logistic Regression and XGBoost models for default prediction
- Performing temporal forward and backward validation to test model stability
- Calibrating probability outputs for economic interpretability
- Conducting scenario analysis to evaluate monotonic risk behavior under varying economic conditions

---

## Repository Structure

### `code_reference.ipynb`
Contains the data engineering pipeline used to:
- Extract and process large Freddie Mac mortgage datasets
- Handle large spaced/fixed-width files efficiently
- Convert raw datasets into compressed Parquet format for scalable analytics

### `Untitled63.ipynb`
Contains the primary modeling and analytics workflow:
- Direct querying of Parquet files using DuckDB
- Data preprocessing and feature engineering
- Construction of final analytical datasets
- Logistic Regression vs XGBoost model comparison
- Temporal forward and backward validation
- Model calibration and probability adjustment
- Scenario analysis for stress-testing borrower risk assessment

---

## Technologies Used

- Python
- Pandas
- DuckDB
- Scikit-learn
- XGBoost
- Parquet
- Freddie Mac Single-Family Loan Dataset

---

## Key Concepts Covered

- Probability of Default (PD) Modeling
- Credit Risk Analytics
- Mortgage Risk Assessment
- Temporal Validation
- Model Calibration
- Stress Testing & Scenario Analysis
- Machine Learning for Financial Risk
- Large-Scale Data Engineering

---

## Research Focus

A major focus of the dissertation was evaluating whether model predictions remained temporally stable, economically interpretable, and monotonically consistent under changing economic environments.

The scenario analysis was specifically conducted to validate whether borrower risk estimates behaved logically under stressed, normal, and optimistic economic conditions.

---

## Disclaimer

This project was developed for academic and research purposes.
