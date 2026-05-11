Derivable Judgement: A Statistical Decision-Making Model
Project Overview

This project focuses on the application of inferential statistical techniques to analyze healthcare-related data and derive meaningful conclusions from the dataset. The objective of this project is to understand how statistical analysis supports data-driven decision-making in healthcare research.

The project includes both theoretical and practical implementation of statistical concepts such as hypothesis testing, confidence intervals, p-values, critical values, t-tests, chi-square tests, ANOVA, covariance, and correlation.

A synthetic healthcare dataset was generated and analyzed using Python in Google Colab. Statistical tests and visualizations were performed to identify relationships between health-related variables including age, BMI, smoking status, diabetes, hypertension, blood pressure, cholesterol level, and glucose level.

Objectives
Apply inferential statistics on healthcare data
Perform hypothesis testing using statistical methods
Analyze relationships between variables
Generate insights using statistical interpretation
Visualize healthcare data using charts and graphs
Understand the practical implementation of statistical concepts
Dataset Information

The project uses a healthcare dataset containing 1000 records with 15 attributes.

Dataset Fields
Column Name	Description
record_id	Unique identifier for each record
age_group	Age category of individuals
age	Age of individuals
weight	Weight of individuals
gender	Gender information
region	Geographic region
smoking_status	Smoking habit of individuals
exercise_frequency	Exercise frequency
bmi	Body Mass Index
blood_pressure	Blood pressure level
diabetes	Diabetes diagnosis
hypertension	Hypertension diagnosis
cholesterol_level	Cholesterol level
glucose_level	Glucose level
visit_date	Date of health check-up
Technologies Used
Programming Language
Python
Development Environment
Google Colab
Python Libraries
Pandas
NumPy
SciPy
Matplotlib
Seaborn
Statistical Techniques Used

The following inferential statistical techniques were implemented in this project.

Hypothesis Testing

Used to determine whether significant relationships exist between variables.

Example Hypotheses
H0: Smoking has no effect on diabetes prevalence
H1: Smoking affects diabetes prevalence
Confidence Interval

Used to estimate the range within which the true population parameter lies.

Formula

CI = x̄ ± z(σ / √n)

t-Test

Used to compare BMI values between smokers and non-smokers.

Formula

t = (x̄1 - x̄2) / √[(s1² / n1) + (s2² / n2)]

Chi-Square Test

Used to analyze relationships between categorical variables such as smoking status and diabetes.

Formula

χ² = Σ[(O - E)² / E]

ANOVA Test

Used to compare BMI means across multiple age groups.

Formula

F = Variance Between Groups / Variance Within Groups

Covariance

Used to measure how two variables change together.

Formula

Cov(X,Y) = Σ[(X - X̄)(Y - Ȳ)] / (n - 1)

Correlation

Used to measure the strength and direction of relationships between variables.

Formula

r = Σ[(x - x̄)(y - ȳ)] / √[Σ(x - x̄)² Σ(y - ȳ)²]

Data Visualization

Several visualization techniques were used to better understand the dataset and statistical relationships.

Visualizations Included
Count Plot
Histogram
Scatter Plot
Box Plot
Correlation Heatmap
Null Value Heatmap

These visualizations helped identify trends, distributions, outliers, and relationships among healthcare variables.

This project successfully demonstrated the practical implementation of inferential statistics in healthcare analysis. Different statistical methods such as confidence intervals, hypothesis testing, t-tests, chi-square tests, ANOVA, covariance, and correlation were applied to derive meaningful conclusions from healthcare data.

The project highlighted how statistical analysis can support evidence-based decision-making and help identify relationships among healthcare variables. The use of Python, Google Colab, and visualization libraries enabled efficient analysis and interpretation of the dataset.

Repository Structure
Inferential-Statistics-Project

Author:Swarna Ajay Pathak
