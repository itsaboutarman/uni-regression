# Regression Analysis Course Projects
### Amirkabir University of Technology (Tehran Polytechnic)

This repository contains the implementation of projects for the Regression Analysis course, supervised by Dr. Amir Hossein Ghatari. The projects focus on statistical modeling, hypothesis testing, and advanced regression diagnostics using the Python programming language.

## Projects Overview

### [Project 01: Fundamentals of Linear Regression](./Project01)
This project focuses on the practical application of fundamental regression concepts:

* **Simple Linear Regression:** Implementation of models to analyze relationships between variables.
* **Statistical Hypothesis Testing:** Performing ANOVA and statistical tests to evaluate model fit and interpret results.
* **Model Diagnostics:** Comprehensive data analysis including the generation of clear, labeled charts for visual interpretation.
* **Technical Constraint:** Exclusively uses the `statsmodels` library for model fitting, as the use of `sklearn` was prohibited for this project.

### [Project 02: Multiple Linear Regression and Model Selection](./Project02)
Focuses on multivariate analysis and the rigorous validation of classical regression assumptions:

* **Classical Assumptions Verification:** Detailed diagnostics including the **Durbin-Watson test** for residual independence, normality tests, and homoscedasticity checks.
* **Multicollinearity & Influential Points:** Analysis of multicollinearity and identification of outliers or influential points within the dataset.
* **Model Selection Strategies:** Implementation of automated selection methods including **Forward Selection**, **Backward Elimination**, and **Stepwise Selection**.
* **Comparative Analysis:** Evaluation and comparison of different models to determine the most effective final model.

## Technologies Used
- **Programming Language:** Python
- **Key Libraries:** `statsmodels` (Mandatory for regression fitting), `pandas`, `numpy`, `matplotlib`, `seaborn`.

## Repository Structure
The repository is organized as follows:
- **Project01/**: Contains the Jupyter Notebook for initial regression analysis and the student performance dataset.
- **Project02/**: Includes the implementation of multiple regression, diagnostic outputs (VIF, ANOVA), and model selection scripts.
- **Reports/**: Detailed PDF reports for each project covering methodology, statistical interpretations, and final conclusions.
