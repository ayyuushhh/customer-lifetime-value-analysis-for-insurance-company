# Insurance Customer Lifetime Value Prediction & Profitability Analysis

**Domain:** Auto Insurance | Customer Analytics | Predictive Modeling | Business Intelligence  
**Project repository:** [customer-lifetime-value-analysis-for-insurance-company](https://github.com/ayyuushhh/customer-lifetime-value-analysis-for-insurance-company)

## Project Overview

This project focuses on predicting **Customer Lifetime Value (CLV)** for an auto insurance company using customer demographics, policy information, and insurance claim details. CLV represents the value associated with a customer, considering both **present value and potential future value**.

The goal is to develop an analytical framework that can help an insurance business understand customer profitability and make more informed decisions about customer relationships and resource allocation.

## Business Problem

An auto insurance company needs to understand how customer characteristics, policy information, and claims relate to the value of its customer base. Without a structured analytical approach, it can be difficult to distinguish customers with different value profiles and decide where to focus business efforts.

**Key business question:** *How can we estimate the lifetime value of individual insurance customers and identify meaningful customer segments?*

## Project Objectives

- **Predict customer lifetime value:** Build a regression-based modeling framework using quantitative and qualitative customer attributes.
- **Understand value drivers:** Explore demographic, policy, and claim-related features that may be associated with CLV.
- **Identify customer segments:** Apply clustering to the training data to study patterns across customer groups.
- **Support business decisions:** Translate analytical findings into potential applications for customer retention, targeted marketing, and profitability analysis.

## Dataset

The original project description specifies three files:

| File | Purpose |
| --- | --- |
| `Train.csv` | Training data for exploratory analysis, modeling, and clustering |
| `Test.csv` | Unseen data for generating CLV predictions |
| `sample_submission.csv` | Sample submission format with customer IDs and example predictions |

The data is described as containing **customer demographics, policy information, and claim details**. Exact columns, record counts, and data quality statistics should be verified against the dataset before being reported.

## Analytical Workflow

### 1. Data Preparation & Exploratory Data Analysis
- Review feature types, missing values, and data distributions.
- Explore relationships between customer characteristics and CLV.
- Visualize patterns that may be relevant to insurance profitability.

### 2. Customer Lifetime Value Prediction
- Prepare quantitative and categorical features for modeling.
- Train and compare appropriate regression models.
- Evaluate predictions using **Root Mean Squared Error (RMSE)**, the evaluation metric specified in the original project brief.

### 3. Customer Segmentation
- Explore clustering of relevant customer features.
- Compare segments to understand differences in customer profiles and value.
- Interpret the potential business implications of these groups.

## Potential Business Applications

| Business Area | How CLV Analytics Can Help |
| --- | --- |
| **Customer Retention** | Prioritize outreach to customers with high estimated long-term value |
| **Marketing Strategy** | Tailor campaigns to different customer value segments |
| **Portfolio Profitability** | Better understand variation in customer value across the portfolio |
| **Resource Allocation** | Inform where customer engagement efforts may be most valuable |

> **Note:** These are potential business applications of the analytical framework, not verified improvements in revenue, retention, or profitability.

## Model Evaluation

**Primary metric: Root Mean Squared Error (RMSE).** Lower RMSE indicates smaller prediction errors on the evaluated dataset. Actual model results and comparisons should be added after confirming the experiment outputs.

## Project Status & Reproducibility

This README documents the **problem statement, intended analytical workflow, and business relevance** described in the source project brief. It does not claim that a specific model, clustering method, accuracy score, or business improvement has been verified.

To make the repository fully reproducible, include the analysis notebooks/scripts, permitted dataset files or dataset access instructions, dependencies, and verified model evaluation results.

## Author

**Ayush Jha**  
[GitHub Profile](https://github.com/ayyuushhh)
