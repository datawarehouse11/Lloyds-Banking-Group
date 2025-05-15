# Lloyds Banking Group - Customer Churn Analysis

This repository contains materials related to a customer churn analysis project completed as part of the Lloyds Banking Group Data Science job simulation on Forage. The project focuses on understanding customer behavior and developing a predictive model to identify customers at risk of churn.

## Project Overview

The primary objective of this project was to analyze customer data to uncover key insights into customer behavior and build a machine learning model to predict customer churn. This analysis aims to enable Lloyds Banking Group to proactively identify at-risk customers and implement targeted retention strategies.

The project encompassed the following key stages:

1.  **Data Gathering and Exploratory Analysis (EDA):** Focused on understanding customer behavior by identifying and collecting relevant data, performing EDA to uncover patterns, and cleaning/preprocessing data for modeling.
2.  **Model Selection, Building, and Evaluation:** Involved choosing an appropriate machine learning algorithm, training the model, and evaluating its performance using relevant metrics.
3.  **Recommendations and Business Implications:** Providing actionable insights and recommendations to Lloyds Banking Group based on the analysis and model predictions, with suggestions for customer retention strategies.

## Repository Contents

This repository includes the following files:

* **`LLoyds Banking Group.ipynb`**:  This Jupyter Notebook contains the core data analysis and model building steps. It include:
    * Data loading and exploration.
    * Data cleaning and preprocessing.
    * Feature engineering.
    * Model training and evaluation.
    * Visualization of results.
* **`Customer_Churn_Data_Large.xlsx`**: This is the primary dataset used for the analysis. It contains customer data related to demographics, transactions, customer service interactions, and online activity.
* **`LLoyds Banking Group - Data Science job sim(Forage).pdf`**:  This document confirms the completion of the Forage job simulation, highlighting skills in data gathering, EDA, and model building.
* **`Lloyds Banking Group.docx`**:  This document outlines the tasks involved in the job simulation, including data gathering, EDA, model building, and reporting.

## Data Description

The analysis is based on a dataset that includes information across several dimensions:

* **Customer Demographics:** Age, Gender, Marital Status, Income Level.
* **Transaction History:** Transaction Dates, Amount Spent, Product Categories.
* **Customer Service Interactions:** Type and Resolution Status of Interactions.
* **Online Activity:** Last Login Date, Login Frequency, Service Usage.
* **Churn Status:** A binary variable indicating whether a customer has churned (1) or not (0).

## Analysis and Modeling

The analysis focused on:

* **Exploratory Data Analysis (EDA):** Uncovering patterns and trends in customer data to understand factors influencing churn.  EDA tasks included analyzing demographic trends, spending patterns, and customer service interactions.
* **Model Selection:** The Random Forest Classifier was chosen as the primary model due to its ability to handle mixed data types, robustness to outliers, and feature importance ranking.
* **Model Training and Evaluation:** The model was trained and evaluated using appropriate metrics (e.g., precision, recall, F1-score, ROC-AUC) and techniques (e.g., cross-validation).
* **Feature Importance:** Identifying the key predictors of churn to inform targeted interventions.

## Key Findings and Recommendations (Inferred from Documents)

The analysis led to findings and recommendations such as:

* **Identification of Key Churn Drivers:** Determining which factors (e.g., transaction behavior, customer service issues, online engagement) are most strongly correlated with customer churn.
* **Customer Segmentation:** Segmenting customers based on their risk of churn to tailor retention strategies.
* **Targeted Retention Strategies:** Recommending specific actions to retain at-risk customers, such as personalized communication, incentives, or improvements to customer service.
* **Insights into Customer Service Interactions:** Analyzing the types and resolution status of customer inquiries to identify areas for improvement in customer service processes.

## Libraries Used (Inferred)

The following Python libraries were used in this analysis:

* **`pandas`**:  For data manipulation and analysis.
* **`numpy`**:  For numerical computations.
* **`scikit-learn` (`sklearn`)**:  For machine learning algorithms (Random Forest), model selection, and evaluation metrics.
* **`matplotlib`** and **`seaborn`**:  For data visualization.

## Getting Started

To explore the analysis, open the `LLoyds Banking Group.ipynb` notebook using Jupyter Notebook or JupyterLab. Ensure you have the necessary Python libraries installed.

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
