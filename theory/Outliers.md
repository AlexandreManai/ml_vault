---
publish: true
tags:
  - theory
  - machineLearning
date: 2024-04-25
link:
---
# Introduction

Statistically an Outlier is a data point which differs from other observations. Reasons for such an instance could be: *variability/error in measurements* or  *novel data*, with errors often excluded from final dataset. 

![[outlier_boxplot.png]]

# Definitions
- *Mean (average) $\bar{x}$*: 
$$ \bar{x} = \frac{1}{n} \sum_{i=1}^n x_i $$
- *Median*: middle value of a dataset when it is ordered in ascending order
$$\begin{cases} x_{\frac{n+1}{2}} & \text{if } n \text{ is odd} \\ \frac{x_{\frac{n}{2}} + x_{\frac{n}{2} + 1}}{2} & \text{if } n \text{ is even} \end{cases}$$
- *First Quartile (Q1)*: median of the data values that fall below the median of the entire dataset (25%)
- *Third Quartile (Q3)*: median of the data values that fall above the median of the entire dataset (75%)
- *Interquartile Range (IQR)*: difference between the third quartile and the first quartile
$$\text{IQR} = Q3 - Q1$$
# Key concepts
An outlier $x$ can be defined as such:
$$\begin{cases} x < Q1 - 1.5 \times \text{IQR} \\ x > Q3 + 1.5 \times \text{IQR} \end{cases}$$
# Challenges

- **Sensitivity to Outliers**
  - The **mean** is highly sensitive to outliers, which can skew the average significantly and lead to misleading interpretations. This sensitivity affects the reliability of mean as a measure of central tendency in datasets with extreme values.

- **Ambiguity in Definitions**
  - Different software and statistical methods may define **quartiles** differently, impacting consistency across analyses. This ambiguity can be particularly challenging when results need to be replicated or compared across different studies or datasets.

- **Sample Size Sensitivity**
  - Small sample sizes can make the **median** and **quartiles** unreliable or non-representative of the overall population. This sensitivity can lead to incorrect conclusions, especially in statistical inference or when trying to generalize findings from a small sample to a larger population.

