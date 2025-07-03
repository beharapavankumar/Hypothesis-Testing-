# Hypothesis-Testing-
This repository consists of different types of Hypothesis Testing Procedure about the population parameter whether to accept/reject the Null Hypothesis.

# 📊 Inferential Statistics in Python — Case Study-Based Implementation
This Jupyter Notebook provides a practical implementation of key inferential statistical methods using Python. It focuses on applying hypothesis testing techniques across real-world case studies involving Z-tests, T-tests, and ANOVA (F-tests), which are essential tools for decision-making in data science and analytics.

# ✅ Key Techniques Covered

1. Z-Test (One Sample, Two-Tailed)
Scenario: Testing whether the average fabric length in a sample is significantly different from the historical mean (150 cm).

Tools: scipy.stats, statsmodels.stats.weightstats

Concepts Used:

Null Hypothesis (H₀): μ = 150 cm

p-value calculation and interpretation

Z-test selection due to known population standard deviation

Final decision based on p-value < α

2. T-Test (One Sample, Two-Tailed)
Scenario: Quality check of bolt diameters to determine if mean ≠ 10 mm using a small sample (n = 20).

Tools: scipy.stats.ttest_1samp

Concepts Used:

T-test used due to unknown population standard deviation

Alpha level set to 0.1 (90% confidence)

Skewness check for normality

Decision rule: Reject H₀ if p-value < α

3. ANOVA (F-Test)
Scenario: Evaluating the effectiveness of different credit card advertisements (waiver ad vs. standard ad) on customer spending behavior.

Tools: (further code expected in later cells)

Concepts Expected:

Comparing means across 2+ groups

Variance partitioning (between-group vs. within-group)

4. 1-Proportion Z-Test
Scenario: Applied when testing the proportion of a binary categorical variable in a single group.

Reason: Used because there is one discrete variable column.

Use Case: For example, checking if the proportion of success/failure in a population differs from a claimed proportion.

5. Chi-Square Test of Independence
Scenario: Comparing proportions between adults and children to determine if there's a significant difference in categorical distribution.

Hypotheses:

H₀: Proportions of adults = proportions of children (no difference)

H₁: Proportions of adults ≠ proportions of children (there is a difference)

Tool: scipy.stats.chi2_contingency

Reason: Applied because of multiple discrete columns (categorical cross-tab).

This makes your notebook a comprehensive guide on hypothesis testing, covering:

Mean comparison (Z-test, T-test),

Variance comparison (ANOVA),

Proportion comparison (1-prop Z-test),

Categorical independence (Chi-square test)

# 💡 Learning Objectives
Understand how to structure a hypothesis test (H₀ vs. H₁)

Decide between Z-test and T-test based on sample size and standard deviation knowledge

Apply p-value logic to accept or reject the null hypothesis

Demonstrate the complete workflow from data import → test selection → p-value calculation → decision making

# 📌 Requirements
Python libraries: pandas, numpy, scipy, statsmodels, openpyxl

Jupyter Notebook environment

# Author
Behara Pavan Kumar
