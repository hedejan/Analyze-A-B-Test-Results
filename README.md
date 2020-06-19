# Analyze A/B Test Results
[Udacity](https://www.udacity.com/course/data-analyst-nanodegree--nd002) Data Analyst Nano-Degree - Project 3

## Objectives
The objective of this project is to understand and use the knowledge of probability, results of an A/B test, and logistic regression models for an e-commerce website dataset to help them understanding if they should implement a new page design or not.

## What Software Do I Need?

To complete this project, I utilized the following tools:

- Python (Numpy, Pandas, Matplotlib, Seaborn, StatsModels, sklearn)
- JupyterLab by Anaconda

### Part I - Probability 

Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

### Part II - A/B Test 

Next, hypothesis testing was conducted assuming the old page is similar or better unless the new page proves otherwise considering a Type I error rate of 5%. 

Both transactions were simulated using np.random,binomial function both under calculated rates and null hypothesis rates and found initial evidence of random chance in the observed difference between the old and new conversion rates.

We then further analyzed the results using statsmodel yet couldn't find significant evidence to reject the null hypothesis based on calculated p-value.

### Part III - Regression

Logistic regression was then performed to confirm results of the previous steps.  Null and alternative hypotheses associated with this regression model were stated and verified to be equal to that of statsmodel. Notice that logistic regression results in a two-sided p-values. 

Next, along with testing if the conversion rate changes for different pages, I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.


## Conclusions 

1) There was no evidence suggesting that those who explore either page will neccessary lead to more conversions.<br>
2) The country of the user did not impact the rate of conversion between the two pages.<br>
3) Given all above, we failed to reject the null hypothsis and couldn't have significant evidence supporting the alternative hypothesis.<br>
4) More research is required to find more critical influence factors.<br>
