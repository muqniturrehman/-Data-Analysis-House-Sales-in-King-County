# House Sales in King County, USA: Final Project

## Overview

This repository contains the final project for the Data Analysis and Predictive Modeling course. The project involves analyzing and predicting housing prices in King County, including Seattle, using various machine learning techniques. The dataset used covers house sales from May 2014 to May 2015 and includes features such as square footage, number of bedrooms, and whether the house has a waterfront view.

## Project Description

As a Data Analyst at a Real Estate Investment Trust, your task is to determine the market price of a house based on its features. This notebook walks through the process of loading data, performing exploratory data analysis, building regression models, and evaluating those models.

## Table of Contents

1. [Instructions](#instructions)
2. [About the Dataset](#about-the-dataset)
3. [Module 1: Importing Data Sets](#module-1-importing-data-sets)
4. [Module 2: Data Wrangling](#module-2-data-wrangling)
5. [Module 3: Exploratory Data Analysis](#module-3-exploratory-data-analysis)
6. [Module 4: Model Development](#module-4-model-development)
7. [Module 5: Model Evaluation and Refinement](#module-5-model-evaluation-and-refinement)
8. [How to Run the Notebook](#how-to-run-the-notebook)
9. [Dependencies](#dependencies)
10. [Contribution](#contribution)

## Instructions

In this project, you will:
- Analyze and preprocess the dataset
- Build and evaluate linear regression models
- Create a pipeline for model training
- Use Ridge regression and polynomial transformations to improve model performance

## About the Dataset

The dataset used is a CSV file containing house sales data for King County. It includes the following columns:
- `id`: A unique identifier for the house
- `date`: The date the house was sold
- `price`: The price of the house (target variable)
- `bedrooms`, `bathrooms`, `sqft_living`, `sqft_lot`, `floors`, etc.

For a complete list of columns and their descriptions, refer to the dataset documentation.

## Module 1: Importing Data Sets

In this module, you will:
- Download and load the dataset
- Display the first few rows and data types of the dataframe

## Module 2: Data Wrangling

In this module, you will:
- Drop unnecessary columns
- Handle missing values by replacing them with the mean

## Module 3: Exploratory Data Analysis

In this module, you will:
- Analyze the distribution of floors in the dataset
- Create box plots to examine price outliers based on waterfront views
- Assess the correlation between `sqft_above` and price

## Module 4: Model Development

In this module, you will:
- Build linear regression models using different features
- Evaluate model performance using R^2 scores

## Module 5: Model Evaluation and Refinement

In this module, you will:
- Split the dataset into training and testing sets
- Perform Ridge regression with and without polynomial features
- Evaluate the performance of these models

## How to Run the Notebook

1. Clone this repository to your local machine using:
    ```bash
    git clone https://github.com/yourusername/house-sales-project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd house-sales-project
    ```

3. Open the Jupyter notebook:
    ```bash
    jupyter notebook Final_Project_House_Sales.ipynb
    ```

4. Follow the instructions in the notebook to complete the analysis.

## Dependencies

The notebook requires the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
