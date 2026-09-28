
---
<!-- Total tokens: 0 -->
# Chapter: seg_127 Heading：chapter 10: hypothesis testing with two samples




---
<!-- Total tokens: 7405 -->
# Section: seg_129 Heading：10.1 two population means with unknown standard deviations

- **Aspin-Welch T-Test**: Test for comparing two independent population means when population standard deviations are unknown and may be unequal.

- **Assumptions For Independent Two-Sample Test**: Two independent simple random samples from distinct populations; for small samples the population distributions should be normal, while for large samples normality is not required.

- **Standard Error Of The Difference In Means**: The estimated standard deviation of X̄1 − X̄2 computed from the sample standard deviations and sizes to account for variability in the difference.

- **Two-Sample t Test Statistic**: The standardized difference ((x̄1 − x̄2) − (μ1 − μ2)) divided by the standard error, yielding a t-score.

- **Degrees Of Freedom For Welch’s Test**: An approximate value computed by the Welch–Aspin formula for use with the Student’s t-distribution; it may be non-integer and is typically calculated by software.

- **Non-Pooled Variances**: The sample variances are not pooled when testing two means with unknown and possibly unequal population standard deviations.

- **Distributional Approximation Conditions**: The t-approximation is very good when both n1 and n2 are at least five; when n1 + n2 > 30, the normal distribution can approximate the Student’s t.

- **Random Variable For Two-Sample Comparison**: X̄1 − X̄2, the difference between the sample means of the two groups.

- **Cohen’s d**: An effect size measure defined as the difference between two means divided by the pooled standard deviation.

- **Cohen’s Standard Effect Sizes**: Benchmarks for interpreting Cohen’s d where 0.2 is small, 0.5 is medium, and 0.8 is large.

- **Pooled Standard Deviation (For Cohen’s d)**: A combined estimate of variability derived from both samples used in the denominator of Cohen’s d.


---
<!-- Total tokens: 5160 -->
# Section: seg_131 Heading：10.2 two population means with known standard deviations

- **Independent Means With Known Population Standard Deviations**: Two-sample hypothesis testing framework comparing two population means when both population standard deviations are known and both populations are normal.
- **Random Variable X̄1 − X̄2**: The difference between the sample means used to assess the difference in population means.
- **Sampling Distribution Of X̄1 − X̄2**: Normal with mean μ1 − μ2 and parameter (σ1)²/n1 + (σ2)²/n2.
- **Standard Deviation Of X̄1 − X̄2**: (σ1)²/n1 + (σ2)²/n2.
- **Z-Test Statistic For Two Population Means (Known σ1, σ2)**: z = [(x̄1 − x̄2) − (μ1 − μ2)] ÷ [(σ1)²/n1 + (σ2)²/n2].
- **Hypotheses For Comparing Two Means**: H0: μ1 ≤ μ2 (equivalently, μ1 − μ2 ≤ 0) versus Ha: μ1 > μ2 (μ1 − μ2 > 0) for a right-tailed test.
- **Right-Tailed Test Determination**: Use a right-tailed test when the alternative hypothesis specifies “>” based on comparative wording (e.g., “is more effective,” “older than”).
- **p-Value Decision Rule**: Compare α with the p-value; do not reject H0 when α < p-value.
- **Assumptions For Validity**: Two independent groups with both populations normal.


---
<!-- Total tokens: 6543 -->
# Section: seg_133 Heading：10.3 comparing two independent population proportions

- **Conditions For Comparing Two Independent Population Proportions**: Two independent simple random samples; at least five successes and five failures in each sample; each population at least ten or 20 times the sample size.
- **Hypothesis Test For Two Independent Population Proportions**: A procedure to determine whether a difference in estimated sample proportions reflects a true difference in population proportions.
- **Null Hypothesis For Two Proportions**: The population proportions are equal (H0: pA = pB, equivalently pA − pB = 0).
- **Random Variable For Two-Proportion Test**: The difference in sample proportions, P′A − P′B.
- **Pooled Proportion**: The combined estimate used under the null hypothesis, pc = (xA + xB) / (nA + nB).
- **Sampling Distribution Of Difference In Sample Proportions**: Approximately normal with mean 0 and variance pc(1 − pc)(1/nA + 1/nB).
- **Two-Proportion Z-Test Statistic**: z = [(p′A − p′B) − (pA − pB)] / sqrt[pc(1 − pc)(1/nA + 1/nB)].
- **Tail Selection For Two-Proportion Tests**: The alternative hypothesis determines the tail: “is a difference” implies two-tailed (≠), “less than” implies left-tailed (<), and “more popular” implies right-tailed (>).
- **Decision Rule Using P-Value And Alpha**: Compare the p-value to the significance level α to decide whether to reject or not reject H0.
- **Sample Proportion**: The estimated proportion in a group, p′ = x / n.


---
<!-- Total tokens: 5566 -->
# Section: seg_135 Heading：10.4 matched or paired samples

- **Matched Or Paired Samples**: A design in which subjects are matched in pairs and two measurements are taken from the same pair; differences between matched measurements are calculated for analysis.
- **Differences As Data**: The calculated paired differences form the sample used in the hypothesis test.
- **Population Mean Of Differences (μd)**: The parameter representing the mean of the paired differences that is tested in the hypothesis.
- **Paired t-Test For Mean Difference**: A one-sample Student’s t test conducted on the paired differences to test μd, using the t distribution with n − 1 degrees of freedom.
- **Test Statistic For Paired t-Test**: Computed as t = (x̄d − μd) / (sd/√n), where x̄d is the sample mean of the differences, sd is the sample standard deviation of the differences, and n is the number of differences.
- **Assumptions For Paired Samples Test**: Simple random sampling; sample sizes are often small; differences come from a normal population or the number of differences is sufficiently large so the sampling distribution of the mean difference is approximately normal.
- **Random Variable X̄d**: The sample mean of the paired differences used in the t test.
- **Degrees Of Freedom For Paired t-Test**: n − 1, where n is the number of paired differences.


---
<!-- Total tokens: 19638 -->
# Section: seg_137 Heading：10.5 hypothesis testing for two means and two proportions

- **Two Population Means With Unknown Standard Deviations**: A hypothesis test comparing two population means from independent samples when population standard deviations are unknown; uses Student’s t-distribution with degrees of freedom computed without pooling variances.
- **Two Population Means With Known Standard Deviations**: A hypothesis test comparing two population means from independent samples when population standard deviations are known (often approximated by sample standard deviations); uses the normal distribution.
- **Comparing Two Independent Population Proportions**: A hypothesis test comparing two population proportions from independent samples; uses the normal distribution for the difference in estimated proportions.
- **Matched Or Paired Samples**: A t-test on dependent samples where two measurements are taken on the same objects; tests the mean of the paired differences, uses Student’s t-distribution with n − 1 degrees of freedom, and requires normally distributed differences when the number of pairs is small.
- **Degrees Of Freedom (Df)**: The number of objects in a sample that are free to vary.
- **Pooled Proportion**: An estimate of the common population proportion when testing two proportions (p1 and p2).
- **Standard Deviation**: The square root of the variance that measures how far data values are from their mean; denoted s for a sample and σ for a population.
- **Variable (Random Variable)**: A characteristic of interest in a population; denoted by uppercase letters with specific values indicated by lowercase letters; its domain may be non-numeric, and its realized value is known only after performing the experiment.
- **Cohen's D**: A measure of effect size.

