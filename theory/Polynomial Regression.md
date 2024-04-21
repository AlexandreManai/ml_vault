---
publish: true
tags:
  - theory
  - paper
  - machineLearning
date: 2024-04-21
link:
---
# Introduction

* Polynomial Regression is a form of regression analysis in which the relationship between the independent variable $x$ and the dependent variable $y$ is modeled as an nth degree polynomial.
* It is used to capture the non-linear relationship between variables which cannot be modeled accurately with simple linear regression.
* Key applications include curve fitting, forecasting, and exploring more complex data patterns in various scientific fields.

# Definitions
- **Dependent Variable (y)**: The variable we are trying to predict or estimate.
- **Independent Variable (x)**: The variable used to predict the value of the dependent variable.
- **Error Term ($\epsilon$)**: The difference between the actual value and the predicted value, representing randomness or unexplained factors.

# Key Concepts
- **Equation of a Polynomial Line**: $y = a_0 + a_1x + a_2x^2 + \dots + a_nx^n$ where $a_0, a_1, \dots, a_n$ are coefficients.
- **Best Fit Polynomial**: The polynomial line that best fits the observed data according to the least squares criterion.
- **Degree of the Polynomial**: The highest power of the independent variable in the polynomial, which determines the curve's complexity.

# Algorithms/Methods
- [[Least Squares Method]]

# Challenges
- Overfitting especially with high-degree polynomials
- Determining the right degree of the polynomial for the best model fit
- Computational complexity increases with the degree of the polynomial

# Further Reading and Resources
- **Courses**: [Coursera's "Machine Learning" by Andrew Ng.](https://www.coursera.org/specializations/machine-learning-introduction?utm_medium=sem&utm_source=gg&utm_campaign=B2C_EMEA_machine-learning-introduction_stanford_FTCOF_specializations_country-multiple-set1&campaignid=20858198833&adgroupid=160248022555&device=c&keyword=coursera%20machine%20learning&matchtype=p&network=g&devicemodel=&adposition=&creativeid=692451745355&hide_mobile_promo&gad_source=1&gclid=Cj0KCQjw8pKxBhD_ARIsAPrG45mnMwI5IrE6wywZPgX5o-fx2pZd3F6Nvv306UNbvr2xENAp1A8VXA8aAupKEALw_wcB)
