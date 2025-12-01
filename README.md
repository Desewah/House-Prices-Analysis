House Prices Data Analysis & Inference

This project explores a housing market dataset to understand how factors like size, year built, and location influence house prices.
It includes data cleaning, exploratory analysis, feature engineering, and a simple inferential test to check assumptions about average pricing.

This is my AltSchool Africa second-semester data science Project, and it demonstrates my ability to work with real datasets, clean them, analyze them, and communicate insights clearly.

<br>
1 — Overview

The goal of this project was to analyze a sample of housing market data and uncover meaningful insights that could help buyers, sellers, or analysts understand what drives house prices.

The analysis was performed in Python using a Jupyter Notebook and covers:

Data loading & inspection

Handling missing values and outliers

Feature engineering

Exploratory data analysis (EDA)

NumPy operations

A basic inferential test

Clear explanations of every step

<br>
2 — Key Insights From the Data
House Prices Distribution

Prices were right-skewed, meaning a few expensive houses raised the overall average.

The median price was a more stable measure than the mean.

📏 Living Area vs Sale Price

There was a strong positive correlation between living area and sale price.

Larger homes consistently sold for more, with some exceptions based on location.

Price Per Square Foot

Creating the price per sq ft feature exposed interesting differences:

Some smaller homes had a higher price per square foot, suggesting that location and renovation can influence value more than size.

Outliers

A few expensive houses were distorting the analysis.

Removing or adjusting them produced cleaner visualizations and more reliable trends.

Inferential Statistics

Using a one-sample t-test, I tested whether the average house price exceeds $180,000.

The test result showed statistically significant evidence that the average price is above $180,000.

<br>
3 — Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

Jupyter Notebook

<br>
4 — What This Project Demonstrates

By completing this analysis, I practiced:

Cleaning and preparing a real dataset

Designing new features to extract extra meaning

Visualizing relationships in the data

Applying simple statistical methods

Explaining insights clearly

Working in a reproducible way using Jupyter Notebook

<br>
