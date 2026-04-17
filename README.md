# LEVEL 2 
## TASK 1: REGRESSION ANALYSIS  
### Codveda Technologies - Data Analysis Intern  
**Eyitene Ejiro Marvin |ID :- CV/A1/65350**

---

## Project Overview
This project focuses on **Simple Linear Regression Analysis** using the Iris dataset.  
The goal is to predict **petal length** based on **sepal length** while fully understanding each step of the machine learning workflow.

---

## Objectives
- Perform basic **data cleaning and preprocessing**
- Explore relationships between variables
- Build a **Simple Linear Regression model**
- Evaluate model performance using:
  - Mean Squared Error (MSE)
  - R-squared (R²)
- Interpret model coefficients and results

---

## Data Cleaning (Brief)
Although the Iris dataset is clean, the following checks were performed:

- Checked for **missing values** → None found  
- Checked for **duplicate rows** → None found  
- Verified **data types** for all columns  
- Selected only relevant numerical features for regression  

---

## Dataset Description
The dataset contains the following features:

- `sepal_length`
- `sepal_width`
- `petal_length` (Target Variable)
- `petal_width`
- `species`

---

## Methodology

### 1. Feature Selection
- Predictor (X): `sepal_length`  
- Target (y): `petal_length`

  
### 4. Model Evaluation
- Mean Squared Error (MSE)
- R-squared Score (R²)

---

## Results

- **Intercept (β0):** -7.31  
- **Slope (β1):** 1.89  

### Interpretation:
- For every **1 cm increase in sepal length**,  
  **petal length increases by ~1.89 cm**

---

## Model Performance

- **Mean Squared Error (MSE):** 0.854  
- **R-squared (R²):** 0.708  

### Insight:
- The model explains **~70.8% of the variation** in petal length  
- Remaining variation is due to other features not included in the model  

---

## Visualization
The regression line shows a **positive linear relationship** between sepal length and petal length, confirming that larger sepals tend to have longer petals.

---

## Tools & Libraries
- Python  
- Pandas  
- Matplotlib 
- Scikit-learn  

---

## Key Learnings
- Understanding how **linear regression works mathematically**
- Importance of **feature selection**
- Interpreting **model coefficients and evaluation metrics**
- Difference between **training and testing performance**

---

## Conclusion
This project demonstrates how a simple linear regression model can capture relationships between variables.  
While the model performs reasonably well, adding more features could improve prediction accuracy.

---

### 1. Train-Test Split
- 80% training data  
- 20% testing data  

### 2. Model Training
A **Linear Regression model** from `scikit-learn` was used

# TASK 2: TIME SERIES ANALYSIS (EDA) 
## Stock Prices Time Series Analysis

---

## Project Overview
This project focuses on **Time Series Analysis** of stock price data to understand how prices change over time.  

The goal is not just to generate plots, but to **analyze trends, seasonality, and patterns step by step**, ensuring a deep understanding of each concept.

---

## Data Cleaning
Before analysis, basic data preprocessing was performed:

- Converted the `Date` column to datetime format  
- Set the `Date` column as the index for time series operations  
- Checked for missing values and ensured key columns were clean  
- Removed or handled missing values in important features where necessary  

---

## Objectives

### 1. Time Series Visualization
- Plotted stock prices over time  
- Identified overall **trends and fluctuations**  

### 2. Moving Average Smoothing
- Applied rolling averages (e.g., 7-day, 30-day)  
- Reduced noise to better observe **short-term and long-term trends**  

### 3. Time Series Decomposition
- Decomposed the data into:
  - **Trend** → Long-term movement  
  - **Seasonality** → Repeating patterns  
  - **Residuals** → Random noise  

- Used `statsmodels` to understand underlying components of the series  

---

## Key Concepts Learned
- Understanding time-based data and indexing  
- Identifying trends and patterns in stock prices  
- Using moving averages for smoothing  
- Breaking down time series into interpretable components  
- Interpreting seasonality and irregular fluctuations  

---

## Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Statsmodels  

---

