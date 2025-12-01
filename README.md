## House Prices Data Analysis and Inference

This project explores a housing market dataset to understand how factors like size, year built, and location influence house prices.  
It includes data cleaning, exploratory analysis, feature engineering, and a simple inferential test to check assumptions about average pricing.

This is my AltSchool Africa second-semester Data Science project, and it demonstrates my ability to work with real datasets, clean them, analyze them, and communicate insights clearly.

---

## 1. Overview

The goal of this project was to analyze a sample of housing market data and uncover meaningful insights that could help buyers, sellers, or analysts understand what drives house prices.

The analysis was performed in Python using a Jupyter Notebook and covers:

- Data loading and inspection  
- Handling missing values and outliers  
- Feature engineering  
- Exploratory Data Analysis (EDA)  
- NumPy operations  
- A basic inferential test  
- Clear explanations of every step  

---

## 2. Key Insights From the Data

### House Prices Distribution  
- Prices were right-skewed, meaning a few very expensive houses raised the overall average.  
- The median price was a more reliable indicator of central tendency than the mean.

### Living Area vs Sale Price  
- There was a strong positive correlation between living area and sale price.  
- Larger homes consistently sold for more, with exceptions based on location and condition.

### Price Per Square Foot  
- Creating a price-per-square-foot feature revealed new patterns.  
- Some smaller homes had a higher price per square foot, showing that location and renovation can matter more than size.

### Outliers  
- A few extremely expensive houses distorted the distribution.  
- Treating or removing them led to clearer visualizations and more dependable insights.

### Inferential Statistics  
- A one-sample t-test was conducted to test whether the average home price exceeds $180,000.  
- The test showed statistically significant evidence that the average price is above this benchmark.

---

## 3. Tools and Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Jupyter Notebook  

---

## 4. What This Project Demonstrates

- Cleaning and preparing a real dataset  
- Designing new features to extract deeper meaning  
- Visualizing relationships in the data  
- Applying simple statistical methods  
- Communicating insights clearly  
- Working in a reproducible way using Jupyter Notebook  
