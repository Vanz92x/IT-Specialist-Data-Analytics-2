# IT-Specialist-Data-Analytics-2

# Evaluate and explain the results of data analyses
Evaluate and explain the results of data analyses is an important process in interpreting the meaning of data that has been collected and analyzed. It involves identifying patterns, trends, relationships, or significant findings in data and providing an understanding of the significance of those findings.

## Hypothesis Testing
Hypothesis testing is a statistical technique utilized to evaluate assertions or hypotheses about a population through the examination of sample data. The primary objective is to determine if there's enough evidence to support or reject a claim regarding a particular population parameter.

This process generally involves two hypotheses:

* the null hypothesis (H0), and

* the alternative hypothesis (H1).

>First, import and execute the library:
```python
import pandas as pd
from scipy import stats
from statsmodels.stats import weightstats as stests
```

>load a dataset and checking:
<div align="center"><img src="https://github.com/Vanz92x/IT-Specialist-Data-Analytics-2/assets/165736197/e7ac8f41-452b-4f51-b7f3-71b9988c10fb" /></div>

## Paired Sample T-Test
* The paired sample t-test is also called dependent sample-t test.
  
* Its an uni-variate that test for a significant difference between 2 related variables.

> Here's an example, to see if the new coating does have a significant effect on driving range.

H0: is there's no significant difference between the distance traveled by the current ball without coating and the new ball with coating

H1: is there's a significant difference between the distance traveled by the current ball without coating and the new ball with coating

<div align="center"><img src="https://github.com/Vanz92x/IT-Specialist-Data-Analytics-2/assets/165736197/8a3f43e3-0f70-44ee-801c-6a8f08dda214" /></div>

* Alpha is a significance level that indicates the limit for accepting or rejecting the null hypothesis in statistical analysis. Commonly used alpha values are 0.05 or 5%, although sometimes other values such as 0.01 or 0.10 may also be used depending on the context.

<div align="center"><img src="https://github.com/Vanz92x/IT-Specialist-Data-Analytics-2/assets/165736197/cb95e45d-6144-4d3b-9379-5f99d29f702c" /></div>

After we use an alpha of 5 percent or 0.05, it turns out that the p-value is 0.209 > alpha 0.05, so that means we accept H0, which means there's no significant difference between the distance traveled by the current ball without coating and the new ball with coating.




