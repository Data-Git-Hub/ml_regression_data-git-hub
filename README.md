# ml_regression_data-git-hub
Final Project: Regression Analysis - Predicting Life Expectancy Using Regression Analysis: A Data-Driven Approach

## Introduction

This project focuses on predicting life expectancy using a dataset published by the World Health Organization, covering global health, economic, and demographic indicators from 2000 to 2015. The dataset includes information from 193 countries and features variables such as mortality rates, immunization coverage, alcohol consumption, GDP, and education levels. <br>

The goal is to build and compare regression models that identify key predictors of life expectancy. The analytical process includes exploratory data analysis, preprocessing steps such as handling missing values and outliers, feature selection, and model evaluation using metrics like R², MAE, and RMSE. Both linear and polynomial regression models will be implemented, with pipelines used to streamline training and testing. <br>

Ultimately, the project aims to uncover insights that can inform health policy and resource allocation while demonstrating practical applications of regression modeling in a public health context. <br>

## Overview
Businesses and organizations must understand the relationships between different factors to make better decisions. <br>
For example, a company may want to predict a car's fuel efficiency based on its weight and engine size or estimate home prices based on square footage and location. <br>
Regression analysis helps identify and quantify these relationships between numerical features, providing insights that can be used for forecasting and decision-making. <br>

This project demonstrates your ability to apply regression modeling techniques to a real-world dataset. You will: <br>
TBD.

## Dataset 

**Life Expectancy (WHO)**  
Source: [Kaggle - Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)

This dataset, provided by the World Health Organization, includes global health, economic, and demographic indicators from 2000 to 2015. It covers 193 countries and provides variables such as mortality rates, immunization coverage, alcohol consumption, GDP, and education levels, all relevant to analyzing and predicting life expectancy. <br>

## Professional Python Setup and Workflow
We follow professional Python practices. 
Full instructions are available at <https://github.com/denisecase/pro-analytics-01/>. 
A concise version is provided at [WORKFLOW_GUIDE.md](./docs/WORKFLOW_GUIDE.md)

**Important:** VS Code + Pylance may fail to recognize installed packages in Jupyter notebooks.  
See the above guides for troubleshooting and solutions.  

---

## Project Outline

[Go to Introduction and Background](https://github.com/Data-Git-Hub/ml_regression_data-git-hub/blob/main/ml-07.ipynb#introduction-and-background)

### Analytical Framework and Methodology

#### Exploratory Data Analysis (EDA)

#### Data Preparation and Preprocessing

#### Feature Selection and Engineering

#### Regression Modeling Techniques

#### Expected Outcomes and Significance

### Section 1: Import and Inspect the Data

#### 1.1. Load the Dataset and Display the First 10 Rows.

#### 1.2. Check for Missing Values and Display Summary Statistics.

##### 1.2.1. Missing Values and Percentage

##### 1.2.2. Display Summary Statistics

### Reflection 1: What do you notice about the dataset? Are there any data issues?

### Section 2. Data Exploration and Preparation

#### 2.1. Explore Data Patterns and Distribution

##### 2.1.1. Create Histograms, Box Plots, and Count Plots for Categorical Variables

##### 2.1.1.1. Grouped Histogram

##### 2.1.1.2. Grouped Box Plot

##### 2.1.1.3. Development Status Count Plot

##### 2.1.1.4. GDP Level Count Plot

##### 2.1.1.5. Year Group Count Plot

##### 2.1.2. Identify Patterns, Outliers, and Anomalies in Feature Distributions

##### 2.1.2.1. Identify Patterns in Feature Distributions

##### 2.1.2.1.A. Identify Patterns in Feature Distribution Pair Plots

##### 2.1.2.2. Identify Outliers in Feature Distributions

##### 2.1.2.2.A. Visualizing Feature Distributions with Violin Plots

##### 2.1.2.3. Identify Anomalies in Feature Distributions

##### 2.1.3. Check for Class Imbalance in the Target Variable

#### 2.2. Handle Missing Values and Clean Data

##### 2.2.1. Impute or Drop Missing Values

##### 2.2.2. Remove or Transform Outliers 

##### 2.2.3. Convert Categorical Data to Numerical Format Using Encoding

#### 2.3. Feature Selection and Engineering

##### 2.3.1. Create New Features

##### 2.3.1.1. Health Investment Ratio

##### 2.3.1.2. Child Mortality Burden

##### 2.3.1.3. Mean Immunization Rate

##### 2.3.1.4. HIV Impact Score

##### 2.3.1.5. Education-Adjusted Economic Index

##### 2.3.2. Transform or Combine Existing Features to Improve Model Performance 

##### 2.3.2.1. Feature Correlation Analysis to Assess Multicollinearity

##### 2.3.2.2. Drop Highly Correlated Features

##### 2.3.2.3 Combine Correlated Features into Interaction Terms or Composite Indicators

##### 2.3.2.3.A. Combine Adult Mortality and HIV/AIDS

##### 2.3.2.3.B. Combine Schooling and Income Composition of Resources

##### 2.3.3. Scale or Normalize Data

##### 2.3.3.1 Scale Data (Standardization)

##### 2.3.3.2 Normalize Data (Min-Max Normalization)

### Reflection 2: What patterns or anomalies do you see? Do any features stand out? What preprocessing steps were necessary to clean and improve the data? Did you create or modify any features to improve performance?

### Section 3. Feature Selection and Justification

### Section 4. Train a Model (Linear Regression)

### Section 5. Improve the Model or Try Alternates (Implement Pipelines)

### Section 6. Final Thoughts & Insights
---

## README.md (Required)

Include a professional README.md. Include:
- a personalized title
- an introduction to your project
- a clickable link to your notebook file.
- a clickable link to your your peer review Markdown file.
- Instructions on how to set up your virtual environment and run your notebook locally.
   
If starting with an assignment README, remove the parts you do not need to present your project.
---

## Repository Checklist

Verify your repository contains:

- [x] Useful .gitignore (that keeps .venv out of GitHub)
- [x] Professional Jupyter Notebook with numbered sections
- [x] Dataset, stored in a data folder.   
- [x] Useful README.md
- [x] Useful requirements.txt
- [ ] Peer Review (peer_review.md).

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

## Version History
- P6 Sect - 2.0 - Modify README.md adding links to sections of ml-07.ipynb, Section 2
- P6 Sect - 1.0 - Add data folder, life_expectancy_data.csv - Modify ml-07.ipynb - Intro, Section 1
- P6 Init - 0.3 - Add peer_review.md - Modify README.md
- P6 Init - 0.2 - Add ml-07 framework - Modify README.md - Modify requirements.txt - Modify .gitignore
- P6 Init - 0.1 - Add requirements.txt
- P6 Init - 0.0 - Add ml-07.ipynb <br>
## Test History  
- N/A <br>