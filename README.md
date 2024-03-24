
# A/B Testing for Landing Page Conversion

## Introduction
This project focuses on performing A/B testing to evaluate the effectiveness of a new landing page design compared to the original design in terms of conversion rate. A/B testing is a powerful statistical tool that helps in decision-making by comparing two versions (A and B) to determine which one performs better on a given metric.

## Methods Used

### One-sample vs. Two-sample T-tests
- **One-sample T-test**: Used for comparing a single sample to a known population mean. It's applicable when we aim to see if the mean of our sample significantly differs from the population mean.
- **Two-sample T-test**: Utilized when comparing the means of two independent samples. This is relevant for our project as we are comparing the conversion rates between two different landing page designs.

### Steps in Performing A/B Testing
1. **Define the Hypothesis**: Start by defining the null hypothesis (no significant difference in conversion rates) and the alternative hypothesis (a significant difference in conversion rates).
2. **Determine Sample Size**: Calculate the sample size needed using the baseline conversion rate, minimum detectable effect, significance level, and desired power.

### Collecting and Preparing the Data
Data is collected and prepared for analysis. This involves cleaning the data and ensuring it's suitable for the A/B test.

## Installation
The analysis is conducted using Python. Required libraries include `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, and `nltk`. These can be installed via pip:

```bash
pip install pandas numpy matplotlib seaborn statsmodels nltk
