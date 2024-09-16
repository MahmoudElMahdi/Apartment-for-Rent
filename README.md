# Statistical Data Analysis Using Regression and Inference

## Overview

This project focuses on statistical data analysis techniques such as **regression analysis**, **statistical inference**, and **descriptive analysis**. The goal is to explore a dataset, gain insights, and determine the key factors that influence the rental price of apartments using Python and various data analysis tools.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Exploration and Descriptive Analysis](#data-exploration-and-descriptive-analysis)
- [Regression Analysis](#regression-analysis)
- [Statistical Inference](#statistical-inference)
- [Conclusion and Recommendations](#conclusion-and-recommendations)
- [Methodology](#methodology)
- [Discussion](#discussion)
- [Limitations and Future Work](#limitations-and-future-work)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

The objective of this analysis is to assess statistical data analysis skills, focusing on **multiple linear regression** and **statistical inference**. The assignment explores the factors affecting rental prices and utilizes Python for data analysis.

## Dataset

The dataset used is from **Kaggle**: [Apartments for Rent Classified Dataset](https://www.kaggle.com/datasets/adithyaawati/apartments-for-rent-classified).

### Key features:
- **Sample size**: 10,000 apartments
- **Variables**: Includes details like `id`, `category`, `title`, `price`, `bedrooms`, `bathrooms`, `square_feet`, `location`, and `amenities`.

## Data Exploration and Descriptive Analysis

Key steps include:
- **Summary statistics**: Examining basic statistics for important variables such as `price`, `square_feet`, `bathrooms`, and `bedrooms`.
- **Data visualizations**: Analyzing rental prices across states and cities, and exploring correlations between features and price.
- **Data transformations**: Outlier removal and price normalization are applied for better analysis results.

## Regression Analysis

- **Dependent Variable**: Rental price.
- **Independent Variables**: Number of bedrooms, bathrooms, square footage, state, and price per square foot.
- **Model Used**: Multiple Linear Regression using **Statsmodels** and **sklearn**.
- **Results**: 
    - Adjusted **R-squared** of 0.964, indicating that approximately 96.4% of the variance in rental prices is explained by the model.

## Statistical Inference

- **F-Test**: A large F-statistic indicates that the predictors collectively explain a significant portion of the variability in the rental price.
- **P-values**: The model is statistically significant with a p-value of 0.0, providing strong evidence against the null hypothesis.

## Conclusion and Recommendations

- **Key Findings**: Bedrooms, bathrooms, square footage, and location significantly impact rental prices.
- **Recommendations**:
  - **For landlords**: Helps set competitive pricing.
  - **For renters**: Provides insights into key features that affect rental costs.

## Methodology

- **Data Preprocessing**: Outliers were removed, and transformations were applied to `price` for improved model performance.
- **Software Used**: Python (Pandas, Statsmodels, sklearn).
- **Validation**: 80/20 train-test split was employed.

## Discussion

- **Findings**: Positive correlations were found between rental prices and the number of bathrooms and bedrooms. Larger apartments and the presence of amenities also influenced prices.
- **Comparison with literature**: The results align with previous studies on rental pricing factors.

## Limitations and Future Work

- **Limitations**: Potential bias from the dataset's origin and limited granularity on the quality of amenities.
- **Future Work**: Expanding the dataset and incorporating more granular data could improve the robustness of the results.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MahmoudElMahdi/Apartment-for-Rent.git
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
## Usage
1. Run the Jupyter notebook to explore the dataset and perform regression analysis.
2. Use the scripts folder for additional Python scripts for data preprocessing and model estimation.
## License
This project is licensed under the MIT License. See the LICENSE file for details.
## Acknowledgements
Dataset from Kaggle.

