# Predicting Data Science and STEM Salaries

This repository contains a project that aims to predict data science and STEM salaries using permutation tests and bootstrapping techniques. The analysis investigates whether higher education (e.g., a Master's degree) and years of industry experience are significant predictors of annual compensation. The project also explores the interaction between these predictors and their impact on salary.

## Introduction

This project investigates the potential benefits of obtaining higher education (e.g., a Master’s degree) versus gaining industry experience when predicting salary levels in data science and STEM fields. By employing permutation tests, bootstrapping, and linear regression models, the analysis attempts to predict salary levels using years of experience and education as key factors.

## Dataset

The dataset used in this project contains information on over 62,000 individuals working in data science and STEM. The data includes features such as:
- **Total Yearly Compensation** (Numeric)
- **Years of Experience** (Numeric)
- **Education Level** (Categorical: Bachelor’s, Master’s, etc.)

The data was sourced from [Kaggle](https://www.kaggle.com/datasets/jackogozaly/data-science-and-stem-salaries).

## Methods

The project uses the following approaches:
- **Permutation Tests**: To evaluate if education levels significantly affect compensation.
- **Bootstrapping**: To assess correlations between years of experience and total compensation.
- **Linear Regression Models**: Four different models were used to predict salaries:
  - Education level only
  - Years of experience only
  - Both education level and years of experience
  - Interaction between education level and years of experience

## Usage

To run the analysis:

1. Load the dataset into your preferred environment (R or Python).
2. Use the provided scripts to perform permutation tests, bootstrapping, and linear regression modeling.
3. Examine the results and plots provided for insight into how education and experience predict salary.

## Results

Key findings include:

- Education Level: Higher education levels, such as a Master's degree, correlate with higher average salaries.
- Years of Experience: A positive correlation was found between years of experience and compensation, but the effect is not linear.
- Model Performance: The model with interaction between education and years of experience had the highest adjusted R² value (~0.18), but still did not explain much of the variance in salary.

## License
This project is licensed under the [MIT License](./LICENSE). See the [LICENSE](./LICENSE) file for more details.
