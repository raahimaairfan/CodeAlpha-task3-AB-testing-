Overview
This project conducts an A/B testing analysis to evaluate the impact of a change or intervention. The analysis uses statistical techniques to draw actionable insights. The notebook processes and analyzes A/B testing data, providing visualizations and statistical tests to compare the performance of two variants.

Import Libraries:
The analysis starts with importing necessary libraries like numpy, pandas, scipy.stats, matplotlib, and seaborn.

Load Data:
https://www.kaggle.com/code/sergylog/ab-test-data-analysis/notebook

Data Inspection:
Initial inspection of the data to understand its structure and basic statistics.

Data Cleaning:
Remove users with multiple test groups.
Exclude outliers and users with inconsistent data.

Visualization:
Use Seaborn and Matplotlib to visualize the distribution of revenues for control and treatment groups.

Statistical Testing:
Perform T-tests to compare the means of the two groups and draw conclusions:

Result Interpretation:
Based on the p-value, determine whether there is a significant difference between the control and treatment groups.

Conclusion
The notebook provides a thorough analysis of the A/B testing results, including data cleaning, visualization, and statistical testing. The results offer insights into the effectiveness of the tested change or intervention.
