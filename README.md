# Airline-Delay-Cause-Analysis
A data-driven exploration of flight delays using Python, statistical methods, and predictive modeling

## Project Overview
This project analyzes a large-scale dataset of 218,718 airline flight records to identify the factors contributing to arrival delays in the U.S. airline system. The dataset includes 21 different features, covering flight counts, delay causes, weather conditions, carrier performance, and airport-level indicators.
The objective of this analysis is to uncover meaningful patterns behind delay occurrences, compute delay metrics, and ultimately build a model that helps predict or explain airline arrival delays.

## Motivation
Airline delays affect millions of passengers each year, leading to financial losses, operational inefficiencies, and customer dissatisfaction. For analysts, this dataset provides the perfect opportunity to apply foundational skills:
Cleaning and transforming large datasets
Identifying delay patterns through descriptive statistics
Engineering meaningful features (e.g., average delay per flight)
Applying machine learning models to understand drivers of delays
Presenting data-driven insights that can inform real-world decisions
This project demonstrates core data analyst competencies, including data wrangling, exploratory data analysis, visualization, and predictive modeling—skills that are directly transferable to business, transportation, operations, and logistics domains.

## Key Methodologies Used
The project uses a structured, end-to-end analytical workflow:
### 1. Data Loading & Inspection
Loaded dataset using pandas
Inspected shape, column types, missing values
Computed summary statistics to understand distribution patterns
### 2. Data Cleaning & Preprocessing
Detected and handled missing values
Created new analytical features such as
avg_delay = arr_delay / arr_flights
Ensured numeric types were properly formatted for modeling
### 3. Exploratory Data Analysis (EDA)
Reviewed delay metrics by different airlines
Compared arrival delays against flight counts
Investigated which delay causes (weather, carrier, NAS, security, late aircraft) were most significant
Identified outliers and unusual airport behavior
Visualized patterns using histograms, bar charts, scatterplots
### 4. Feature Engineering
Built derived features that improve interpretability
Normalized or scaled features where needed
Prepared selected inputs for regression and classification models
### 5. Predictive Modeling
Used scikit-learn models such as:
Linear Regression → to quantify relationships between delay predictors and arrival delays
Logistic Regression → to classify flights based on thresholded delay categories
Evaluation included:
Coefficient interpretation
Accuracy and regression metrics
Model diagnostics and performance comparison
### 6. Insights & Conclusions
The modeling work helps identify:
Which delay causes most strongly influence arrival delays
How airline operations (e.g., frequency of late aircraft) correlate with longer delays
Whether flight volume affects delay likelihood
Patterns that could guide airline or airport operational improvements

## Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn (LinearRegression, LogisticRegression)
Jupyter Notebook

## Dataset Summary
Rows: 218,718
Columns: 21
Features include:
Flight counts
Arrival and departure delays
Causes of delay (carrier, weather, NAS, security, late aircraft)
Airport and airline identifiers
Derived features such as average arrival delay per flight are included to support analysis
