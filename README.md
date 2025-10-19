# Data Exploratory Data Analysis (UCI Imports-85)
This repository provides a complete Exploratory Data Analysis (EDA) workflow for the **Automobile (Imports-85) Dataset** and **Laptop Pricing dataset**. 
Automobile dataset was from the UCI Machine Learning Repository.
The project focuses on understanding feature patterns, relationships, and statistical insights before model development.
________________________________________
# 📌 **Dataset Overview**
## 1

- Source: UCI Machine Learning Repository – Automobile Dataset

- Rows: 205

- Attributes: 26 (mix of categorical, continuous, and integer values)

- Common Target Variable: price

## 2
- Laptop Pricing Dataset
________________________________________
# ⚙️ **EDA Workflow**

## Import Data and Assign Column Headers

•	Load the dataset and assign meaningful, descriptive column names for better readability.

•	Display basic information (.info(), .head(), .describe()) to understand data structure and data types.


## Analyzing Individual Feature Patterns Using Visualization

•	Use histograms, boxplots, and count plots to visualize the distribution of each feature.

•	Identify outliers, skewness, and spread for numerical features.

•	Examine the frequency and diversity of categories for categorical variables.


## Correlation Analysis
   
•	Compute and visualize pairwise correlations among numerical variables using the .corr() method.

•	Identify potential linear relationships or multicollinearity among features.


## Focused Correlation Study
   
From Automobile dataset, analyze relationships between the following numerical features:

•	bore
•	stroke
•	compression-ratio
•	horsepower

Generate correlation metrics and interpret the degree of linear association between them.


## Scatterplot with Fitted Regression Line
   
•	Visualize pairwise relationships using scatterplots.

•	Add regression lines to evaluate trends and linear patterns (e.g., seaborn.regplot).

•	Example: horsepower vs. price.


## Categorical Variables
   
•	Examine categorical attributes such as make, fuel-type, body-style, etc.

•	Use bar plots and count plots to visualize category frequencies.

•	Explore relationships between categorical and continuous variables using boxplots or violin plots.


## Descriptive Statistical Analysis
   
•	Summarize central tendency, dispersion, and distribution using:
o	.describe() for numerical data
o	.value_counts() for categorical data

•	Compare mean, median, and standard deviation across different variables.


## Basics of Grouping
   
•	Use groupby() operations to analyze aggregated statistics by categories (e.g., make or drive-wheels).

•	Identify which groups exhibit higher or lower mean prices or performance metrics.


## Heatmap Visualization
    
•	Create a correlation heatmap to visualize relationships among numerical features.

•	Highlight strongly correlated or inverse-correlated variable pairs.


## Pearson Correlation and P-Value
    
•	Calculate Pearson correlation coefficients and corresponding p-values to measure the strength and statistical significance of relationships.

•	Interpret the results to identify which features are meaningfully correlated with key targets like price.

________________________________________
# 📊 **Outcome**

•	Comprehensive understanding of data distribution, feature relationships, and key patterns.

•	Visual and statistical insights to guide further modeling and preprocessing.

•	Reusable EDA pipeline applicable to similar structured datasets.
________________________________________
# 🧰 **Tools & Libraries**

•	Python
•	Pandas, NumPy – data manipulation
•	Matplotlib, Seaborn – visualization
•	SciPy – correlation and statistical testing
