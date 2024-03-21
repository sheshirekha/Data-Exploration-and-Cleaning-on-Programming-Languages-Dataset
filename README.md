# Data-Exploration-and-Cleaning-on-Programming-Languages-Dataset
# Programming Language Dataset

## Overview
This dataset contains information about various programming languages, including their features, popularity, release dates, and other relevant attributes. The dataset is intended for exploration and analysis to gain insights into the programming language landscape.

## Files
- `programming_languages.csv`: Main dataset file containing programming language data.
- `README.md`: This file, providing information about the dataset and guidelines for exploration and cleaning.
- `LICENSE`: License information for the dataset.

## Data Exploration
To explore the dataset, follow these steps:

1. Load the dataset into your preferred data analysis environment (Using Pandas).
2. Examine the structure of the dataset using functions like `head()`, `info()`, and `describe()`.
3. Identify the columns present in the dataset and their corresponding data types and remove unwanted columns from the dataset
4. Check for missing values and handle the outliers appropriately using trimming or capping or Interquartile range.
5. Fill the missing values using .fillna(), ffill(), bfill(), .fillna().mean() or median() or mode()
7. Visualize relationships between variables using plots like histograms, scatter plots, and box plots.

## Data Cleaning
Cleaning the dataset ensures that it is accurate, complete, and ready for analysis. Follow these steps for data cleaning:

1. Handle missing values:
   - Decide whether to impute missing values, remove rows with missing values, or leave them as-is based on the context.
   - For numerical variables, consider imputation techniques such as mean, median, or interpolation.
   - For categorical variables, impute missing values with the mode or a separate category.
2. Remove duplicates:
   - Identify and remove duplicate rows from the dataset to avoid bias in analysis.
3. Correct data errors:
   - Review data for inaccuracies or anomalies and correct them as needed.
4. Handle outliers:
   - Identify outliers in numerical variables using statistical methods and decide whether to remove or transform them.

