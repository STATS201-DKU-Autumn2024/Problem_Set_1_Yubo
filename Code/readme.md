# Exploratory Data Analysis (EDA) for AiGen-FoodReview Dataset

This repository contains an exploratory data analysis (EDA) of the AiGen-FoodReview dataset, which includes machine-generated and human-authored restaurant reviews. The EDA provides insights into the data structure, distribution, and correlations among various features to aid in understanding and preparing the dataset for further analysis.

## Overview

The EDA covers the following steps:

1. **Data Loading and Basic Overview**: 
   - Loaded the dataset and displayed its structure to understand the types of variables included.
   
2. **Summary Statistics**:
   - Generated basic statistical summaries to get an overview of numeric features.
   
3. **Missing Value Analysis**:
   - Identified any missing values in the dataset to determine if imputation or data cleaning is necessary.
   
4. **Label Distribution**:
   - Visualized the distribution of the target variable, `label`, which indicates if a review is machine-generated (1) or human (0).
   - The distribution graph for `label` is shown below:

   ![Label Distribution](label_distribution.jpg)

5. **Readability Metrics Distribution**:
   - Plotted histograms for key readability metrics, such as the Automated Readability Index and Flesch Reading Ease, to analyze their distributions.

6. **Correlation Analysis**:
   - Created a correlation heatmap of numerical features to identify relationships and potential multicollinearity.

## Files

- **EDA.ipynb**: The Jupyter Notebook file containing all code for the EDA process.
- **label_distribution.jpg**: A JPEG image of the label distribution plot, showing the counts of machine-generated and human-authored reviews.

## Usage

To explore the EDA steps, you can open and run the `EDA.ipynb` notebook. Ensure you have the necessary libraries installed (`pandas`, `matplotlib`, `seaborn`).

## Dependencies

- Python 3
- pandas
- matplotlib
- seaborn
