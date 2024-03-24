# A/B Testing for Landing Page Conversion with Python

In this project, we demonstrate the use of statistical tests to analyze A/B testing results for a website's landing page conversion rates. The goal is to determine whether a new landing page (variant B) significantly outperforms the existing page (variant A) in terms of user conversion.

## Overview

A/B testing is a randomized control experiment comparing two versions (A and B) to identify which one performs better on a given metric. In this case, our metric is the conversion rate of visitors to a website. We use the one-sample t-test and the two-sample t-test, both crucial statistical tests, to ascertain if the difference in conversion rates between the two versions is statistically significant.

## Steps Involved

1. **Define the Hypothesis**: Our null hypothesis is that there is no difference in conversion rates between the old and new landing pages. The alternative hypothesis suggests a significant difference.

2. **Exploratory Data Analysis (EDA)**: Initial analysis to understand the dataset's structure, missing values, unique users, returning users, etc.

3. **Statistical Analysis**:
   - **Discrete Metrics Analysis**: Understanding the conversion rates by landing page.
   - **Fisher's Exact Test**: Assessing the significance of the association between landing page type and conversion.
   - **Pearson’s Chi-Squared Test**: Evaluating the independence between categorical variables (landing page and conversion).

## Conclusion

The results from the Fisher's Exact Test and Pearson’s Chi-Squared Test provide evidence to accept or reject our hypothesis. Depending on the p-values obtained, we can conclude whether the new landing page significantly affects the conversion rate compa
