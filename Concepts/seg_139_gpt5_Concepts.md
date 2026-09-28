
---
<!-- Total tokens: 0 -->
# Chapter: seg_139 Heading：chapter 11: the chi-square distribution




---
<!-- Total tokens: 3747 -->
# Section: seg_141 Heading：11.1 facts about the chi-square distribution

- **Chi-Square Distribution Notation**: Denoted X ~ χ2 with df degrees of freedom; the random variable symbol is often χ2 but may be any uppercase letter.
- **Degrees Of Freedom**: df represents degrees of freedom and depends on how the chi-square is used; for practice, df = n − 1, and the three major uses calculate df differently.
- **Chi-Square Mean**: For the χ2 distribution, the population mean equals the degrees of freedom (μ = df).
- **Chi-Square Standard Deviation**: For the χ2 distribution, the population standard deviation is σ = 2(df).
- **Sum Of Squared Standard Normals**: A χ2 random variable with k degrees of freedom equals the sum of k independent, squared standard normal variables.
- **Distribution Shape**: The chi-square curve is nonsymmetrical and skewed to the right.
- **Family Of Chi-Square Curves**: There is a different chi-square curve for each value of df.
- **Nonnegativity Of Test Statistic**: The chi-square test statistic is always greater than or equal to zero.
- **Normal Approximation For Large Degrees Of Freedom**: When df > 90, the chi-square distribution approximates the normal distribution.
- **Mean Location Relative To Peak**: The mean (μ) is located just to the right of the peak of the chi-square curve.


---
<!-- Total tokens: 6242 -->
# Section: seg_143 Heading：11.2 goodness-of-fit test

- **Goodness-Of-Fit Test**: A hypothesis test that determines whether sample data fit a specified distribution using a chi-square framework.
- **Chi-Square Test Statistic**: The sum across categories of (O − E)² / E, measuring discrepancy between observed and expected frequencies.
- **Observed Values (O)**: The data values recorded for each category.
- **Expected Values (E)**: The frequencies expected in each category if the null hypothesis is true.
- **Degrees Of Freedom**: The number of categories minus one (df = k − 1).
- **Right-Tailed Test**: The test is almost always right-tailed; larger discrepancies produce larger statistics in the right tail of the chi-square distribution.
- **Expected Count Requirement**: Each expected cell frequency must be at least five to validly use the test.
- **Hypotheses For Goodness-Of-Fit**: H0 states the data fit the specified distribution; Ha states the data do not fit the specified distribution.
- **Test Distribution**: The chi-square distribution with degrees of freedom equal to the number of categories minus one.
- **P-Value For Goodness-Of-Fit**: The right-tail probability P(χ² > calculated statistic) under the chi-square distribution with the appropriate degrees of freedom.


---
<!-- Total tokens: 5497 -->
# Section: seg_145 Heading：11.3 test of independence

- **Test Of Independence**: A hypothesis test using a contingency table of observed frequencies to determine whether two factors are independent.
- **Contingency Table**: A table of observed (data) values organized by the categories of two factors for conducting a test of independence.
- **Observed Frequency (O)**: The data count recorded in a cell of the contingency table.
- **Expected Frequency (E)**: The cell count expected under independence, computed as (row total × column total) ÷ total surveyed; each expected count must be at least five.
- **Chi-Square Test Statistic**: The sum over all cells of (O − E)²/E (with i × j terms), measuring the discrepancy between observed and expected counts.
- **Degrees Of Freedom For Independence Test**: (Number of columns − 1) × (Number of rows − 1).
- **Hypotheses For Independence Test**: Null hypothesis states the two factors are independent; alternative hypothesis states they are not independent (dependent).
- **Right-Tailed Test**: The test of independence is always right-tailed because larger differences between observed and expected values produce larger statistics in the right tail of the chi-square distribution.
- **Independence Of Events**: Two events A and B are independent if P(A AND B) = P(A)P(B).
- **P-Value For Independence Test**: The probability P(χ² > observed test statistic) under the appropriate chi-square distribution.


---
<!-- Total tokens: 3891 -->
# Section: seg_147 Heading：11.4 test for homogeneity

- **Test For Homogeneity**: A test used to determine whether two populations have the same distribution; calculated using the same procedure as the test of independence.
- **Null Hypothesis**: The distributions of the two populations are the same.
- **Alternative Hypothesis**: The distributions of the two populations are not the same.
- **Test Statistic**: Use a χ2 test statistic computed in the same way as the test for independence.
- **Degrees Of Freedom**: df = number of columns − 1.
- **Expected Cell Frequency Condition**: The expected value for each cell must be at least five to use this test.
- **Minimum Cell Count Requirement**: All values in the table must be greater than or equal to five.
- **Common Uses**: Comparing two populations.
- **Applicable Variable Type**: The variable is categorical with more than two possible response values.
- **Interpretation Limitation**: The test indicates whether distributions are the same or not but does not show how they differ.


---
<!-- Total tokens: 1921 -->
# Section: seg_149 Heading：11.5 comparison of the chi-square tests

- **Chi-Square Goodness-Of-Fit Test**: Used to decide whether a population with an unknown distribution fits a known distribution; applies to a single qualitative question or single outcome from a single population; H0: the population fits the given distribution; Ha: the population does not fit the given distribution.
- **Chi-Square Test Of Independence**: Used to decide whether two variables (factors) are independent or dependent; involves two qualitative questions or experiments with a contingency table; H0: the two variables are independent; Ha: the two variables are dependent.
- **Chi-Square Test Of Homogeneity**: Used to decide if two populations with unknown distributions have the same distribution; involves a single qualitative question or experiment given to two different populations; H0: the two populations follow the same distribution; Ha: the two populations have different distributions.


---
<!-- Total tokens: 5516 -->
# Section: seg_151 Heading：11.6 test of a single variance

- **Test Of A Single Variance**: A hypothesis test for a single population variance that assumes the underlying distribution is normal.
- **Null And Alternative Hypotheses For Single Variance Test**: Statements formulated in terms of the population variance σ² (or the population standard deviation σ).
- **Test Statistic For Single Variance**: The quantity (n − 1)s²/σ² comparing the sample variance to the hypothesized population variance.
- **Degrees Of Freedom**: The value df = n − 1 used in this test.
- **Chi-Square Distribution For Single Variance Test**: The sampling distribution for the test statistic is χ² with df = n − 1.
- **Random Variable In Single Variance Test**: The sample standard deviation s treated as the random variable.
- **Tail Types For Single Variance Test**: The test can be right-tailed, left-tailed, or two-tailed.
- **Sample Variance (s²)**: The variance computed from the sample.
- **Population Variance (σ²)**: The variance of the population referenced in the hypotheses.


---
<!-- Total tokens: 6370 -->
# Section: seg_153 Heading：11.7 lab 1: chi-square goodness-of-fit

- **Chi-Square Goodness-Of-Fit Test**: A hypothesis test that evaluates whether sample data fit a specified distribution by comparing observed and expected counts across categories.
- **Chi-Square Distribution**: The reference distribution used to conduct the goodness-of-fit hypothesis test.
- **Null Hypothesis (H0)**: The statement that the data follow the specified distribution.
- **Alternative Hypothesis (Ha)**: The statement that the data do not follow the specified distribution.
- **Observed Frequency**: The count of sample observations in each category.
- **Expected Frequency**: The count predicted for each category under the hypothesized distribution.
- **Expected Frequency Requirement**: Each category must have an expected count of at least five; categories may be combined to meet this condition.
- **Uniform Distribution**: The hypothesized model X ~ U(lowest value, highest value) used for testing and partitioned into fifths using specified percentiles.
- **Exponential Distribution**: The hypothesized model X ~ Exp(1/x̄) used for testing.
- **Decay Parameter (Exponential)**: The exponential rate parameter specified as 1/x̄.
- **Cells (Categories)**: Intervals defined to tally observed and expected counts for the test.
- **Percentiles And Quartiles**: Cut points (e.g., 20th, 40th, median, quartiles) used to define category boundaries.
- **Test Statistic**: The computed value used with the chi-square distribution to perform the hypothesis test.
- **P-Value**: The area under the chosen distribution corresponding to the test statistic used to make the decision.
- **Decision And Conclusion**: The final judgment based on the p-value and a complete-sentence summary of the result.
- **Sample Mean (x̄)**: The sample average used to set the exponential decay parameter.


---
<!-- Total tokens: 16668 -->
# Section: seg_155 Heading：11.8 lab 2: chi-square test of independence

- **Chi-Square Test Of Independence**: Assesses whether two factors are independent by comparing observed values to expected values using the chi-square distribution; the test is right-tailed and requires adequate expected cell counts.
- **Null Hypothesis (Independence Test)**: The two factors are independent.
- **Contingency Table**: A table that displays sample values for two different factors that may be dependent or contingent on one another; it facilitates determining conditional probabilities.
- **Degrees Of Freedom (Independence)**: df = (i − 1)(j − 1), where i is the number of rows and j is the number of columns.
- **Expected Cell Count**: E = (row total)(column total) / total surveyed.
- **Expected Cell Frequency Condition**: Each observation or cell category must have an expected value of at least five.
- **Chi-Square Test Statistic (Independence)**: Σ (O − E)² / E, where O = observed values and E = expected values.
- **Right-Tailed Test (Independence)**: The chi-square test of independence is right-tailed.

