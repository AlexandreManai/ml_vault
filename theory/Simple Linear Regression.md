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

* Simple Linear Regression is a statistical method used to model the relationship between a scalar dependent variable $y$ and one independent variable $x$ .
* It is used in various fields such as economics, finance, biology, and machine learning for predictive analysis.
* Key questions addressed include the prediction of outcomes based on linear relationships and the strength of the correlations between variables.

# Definitions
- **Dependent Variable (y)**: variable that is being predicted or estimated
- **Independent Variable (x)**: variable that is used to predict the value of the dependent variable
- **Error term ($\epsilon$)**: difference between the actual value and the predicted value, accounting for randomness or unexplained factors

# Key concepts

- **Equation of a Line**: $y = mx + b$ where $m$ is the slope and $b$ is the y-intercept
- **Best Fit Line**: Line that best represents the observed data according to the least squares criterion.
- **Diagram of data points and fit line**: ![[simple_linear_regression_plot.png]]

# Algorithms/Methods
- [[Least Squares Method]]

# Challenges
- Addressing assumptions such as linearity and normality of errors
- Limitations in scenarios where relationships between variables are not linear
	- See improvements: [[Multivariate Linear Regression]] and/or [[Polynomial Regression]] 
# Further Reading and Resources
- **Articles**: ["Linear Regression -- Detailed View" - Towards Data Science.](https://towardsdatascience.com/linear-regression-detailed-view-ea73175f6e86#:~:text=Simple%20Linear%20Regression&text=It%20looks%20for%20statistical%20relationship,possible%20to%20accurately%20predict%20Fahrenheit.)
- **Courses**: [Coursera's "Machine Learning" by Andrew Ng.](https://www.coursera.org/specializations/machine-learning-introduction?utm_medium=sem&utm_source=gg&utm_campaign=B2C_EMEA_machine-learning-introduction_stanford_FTCOF_specializations_country-multiple-set1&campaignid=20858198833&adgroupid=160248022555&device=c&keyword=coursera%20machine%20learning&matchtype=p&network=g&devicemodel=&adposition=&creativeid=692451745355&hide_mobile_promo&gad_source=1&gclid=Cj0KCQjw8pKxBhD_ARIsAPrG45mnMwI5IrE6wywZPgX5o-fx2pZd3F6Nvv306UNbvr2xENAp1A8VXA8aAupKEALw_wcB)
