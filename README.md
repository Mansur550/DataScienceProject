Loan Approval Classification – Data Science Project
Overview

This project focuses on data preprocessing, exploratory data analysis, and preparation of a loan approval dataset for machine learning and data science tasks. The objective is to clean, transform, and analyze loan application data to make it suitable for predictive modeling and data-driven decision making.

The project is implemented using R and demonstrates core techniques used in data science, artificial intelligence, and machine learning workflows.

Dataset Description

The dataset is derived from the Loan Approval Classification Dataset.

Sample records: 201

Total variables: 14

Target variable: loan_status

1 = Approved

0 = Rejected

Features

Numerical variables:

person_age

person_income

person_emp_exp

loan_amnt

interest_rate

credit_score

Categorical variables:

person_gender

person_education

person_home_ownership

loan_purpose

loan_grade

previous_loan_defaults_on_file

The dataset initially contained missing values, noisy entries, and outliers which were handled during preprocessing.

Tools and Technologies

R

RStudio

dplyr

ggplot2

Key Tasks Performed
Data Cleaning

Identified missing values (NA and empty strings)

Replaced missing numerical values using mean imputation

Replaced missing categorical values using mode imputation

Checked and handled duplicate records

Handling Noisy Data

Corrected misspelled categorical values (for example gender and home ownership)

Standardized categorical variables for consistency

Outlier Detection and Treatment

Used boxplots and interquartile range (IQR)

Replaced outliers with mean values for selected numerical features

Data Transformation

Converted categorical variables to numeric where required

Converted numeric target variables to categorical labels

Applied min–max normalization to numerical variables

Exploratory Data Analysis

Visualized missing values using bar plots

Generated descriptive statistics

Compared income, age, employment experience, and credit score across loan status categories

Sampling and Data Splitting

Applied oversampling to balance gender classes

Split the dataset into training (80%) and testing (20%) sets



Results

Missing values and noisy data successfully removed

Dataset balanced using oversampling

Clean and normalized data prepared for machine learning models

Meaningful statistical insights generated through EDA

Learning Outcomes

Strong understanding of data preprocessing techniques

Practical experience with exploratory data analysis

Exposure to real-world data issues in AI and machine learning

Improved proficiency in R for data science applications

Future Work

Build machine learning models for loan approval prediction

Compare multiple classification algorithms

Perform feature selection and model optimization

Extend analysis using the full dataset

A