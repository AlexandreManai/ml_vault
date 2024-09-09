---
publish: true
tags:
  - theory
  - machineLearning
date: 2024-05-01
link:
---
# Introduction
- **Median** is a measure of central tendency that identifies the middle value of a data set when arranged in order.
- Unlike mean, median is less sensitive to outliers and skewed data, making it useful in various statistical contexts

![[mean_median_mode.png | 200]]

# Definitions
*Median*
  - If the number of observations (n) is odd, the median is the middle value: $$ x_{\left(\frac{n+1}{2}\right)}$$
  - If n is even, the median is the average of the two middle numbers:  $$\frac{x_{(\frac{n}{2})} + x_{(\frac{n}{2}+1)}}{2} $$
# Challenges
### Median Challenges

1. **Data Sensitivity**:
    - **Problem**: While the median is resistant to outliers, it is very sensitive to changes near the middle of the data set.
    - **Example**: In a data set of 1, 2, 3, 4, 99, shifting the value 4 to 5 will change the median, while changes in 1 or 99 will not affect it.

2. **Odd vs. Even Number of Observations**:
    - **Problem**: The method for calculating median changes based on whether the data set has an odd or even number of observations, which can affect interpretations in small data sets.
    - **Example**: For the data set 1, 2, 3, the median is 2. However, if another observation, say 4, is added, the median becomes $\frac{2+3}{2} = 2.5$ .

3. **Inefficiency in Large Data Sets**:
    - **Problem**: Finding the median in large data sets can be computationally intensive as it requires sorting the data.
    - **Example**: For a data set containing millions of entries, computing the median involves significant computational resources to sort and identify the middle values.

# Further Reading and Resources
- [Wikipedia Link on Median](https://en.wikipedia.org/wiki/Median)

