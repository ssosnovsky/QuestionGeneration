
---
<!-- Total tokens: 0 -->
# Chapter: seg_113 Heading：chapter 9: hypothesis testing with one sample




---
<!-- Total tokens: 4188 -->
# Section: seg_115 Heading：9.1 null and alternative hypotheses

- **Null Hypothesis (H0)**: A statement of no difference between sample means or proportions, or between a sample mean or proportion and a population mean or proportion; the difference equals 0 and the hypothesis includes an equality symbol.
- **Alternative Hypothesis (Ha)**: A claim about the population that contradicts H0 and is the conclusion when H0 is rejected; it never includes an equality symbol and uses ≠, >, or < depending on test wording.
- **Decision Options In Hypothesis Testing**: The two possible decisions are reject H0 if the sample information favors Ha, or do not reject (decline to reject) H0 if the evidence is insufficient to reject H0.
- **Symbol Conventions For Hypotheses**: H0 uses symbols with equality (=, ≥, ≤) while Ha uses ≠, >, or <; the choice of symbol depends on the wording of the test.
- **Acceptable Equality Notation In H0**: Using “=” in H0 is acceptable even when Ha uses “>” or “<” because the decision is only to reject or not reject H0.


---
<!-- Total tokens: 3652 -->
# Section: seg_117 Heading：9.2 outcomes and the type i and type ii errors

- **Type I Error**: Rejecting the null hypothesis when the null hypothesis is true.
- **Type II Error**: Not rejecting the null hypothesis when the null hypothesis is false.
- **Alpha (α)**: Probability of a Type I error; P(Type I error) = probability of rejecting the null hypothesis when the null hypothesis is true.
- **Beta (β)**: Probability of a Type II error; P(Type II error) = probability of not rejecting the null hypothesis when the null hypothesis is false.
- **Power Of The Test**: Probability of rejecting the null hypothesis when it is false; equal to 1 - β.


---
<!-- Total tokens: 4159 -->
# Section: seg_119 Heading：9.3 distribution needed for hypothesis testing

- **Student's T-Distribution**: Used to test a single population mean when the population standard deviation is unknown and the sample mean distribution is approximately normal; requires a simple random sample from an approximately normal population and uses the sample standard deviation; remains valid with sufficiently large samples even if the population is not approximately normal.
- **Z-Test For A Single Population Mean**: Uses the normal distribution to test a single population mean when the population standard deviation is known; requires a simple random sample and either a normally distributed population or a sufficiently large sample size.
- **Normal Distribution For A Single Population Proportion**: Used to test a single population proportion with a large sample; requires binomial conditions and the normal approximation criteria np > 5 and nq > 5.
- **Binomial Conditions**: A fixed number of independent trials, each with success/failure outcomes and the same probability of success p.
- **Population Mean (μ)**: The parameter representing the population mean in single-mean hypothesis tests.
- **Sample Mean (x̄) As Point Estimate**: The estimated value of μ used in testing a single population mean.
- **Population Proportion (p)**: The parameter representing the population proportion in single-proportion hypothesis tests.
- **Sample Proportion (p′)**: The estimated value of p, defined as x/n where x is the number of successes and n is the sample size.
- **Complement Probability (q)**: Defined as 1 − p and used in proportion testing conditions.
- **Simple Random Sample**: The required sampling method for hypothesis tests of a single mean or a single proportion.


---
<!-- Total tokens: 4541 -->
# Section: seg_121 Heading：9.4 rare events, the sample, decision and conclusion

- **Rare Event**: A sample outcome that would be very unlikely if the null hypothesis were true, prompting doubt about the null assumption.
- **Null Hypothesis (H0)**: An assumption about a population property that is subjected to testing.
- **Alternative Hypothesis (Ha)**: A statement that contradicts the null hypothesis, often expressing a directional claim.
- **p-Value**: The probability that, if the null hypothesis is true, results from another randomly selected sample would be as extreme or more extreme than those observed; smaller values indicate stronger evidence against H0.
- **Significance Level (Alpha, α)**: A preset probability of a Type I error used as a threshold for decision-making.
- **Type I Error**: Rejecting the null hypothesis when the null hypothesis is true.
- **p-Value Decision Rule**: If α > p-value, reject H0; if α ≤ p-value, do not reject H0.
- **Statistical Significance**: The sample results are significant when p-value < α and not significant when p-value ≥ α.
- **Interpretation Of Non-Rejection**: Not rejecting H0 does not mean H0 is true; it indicates insufficient evidence to cast serious doubt on H0.
- **Conclusion Statement**: After making the decision, write a conclusion about the hypotheses in terms of the given problem.


---
<!-- Total tokens: 13515 -->
# Section: seg_123 Heading：9.5 additional information and full hypothesis test examples

- **Level Of Significance (Alpha)**: The preconceived or preset α selected before collecting sample data; if unspecified, a common standard is 0.05.
- **P-Value**: The area under the test distribution in the left tail, right tail, or split between both tails corresponding to the sample result; interpreted as the probability of obtaining a result as extreme or more if the null hypothesis is true.
- **Left-, Right-, And Two-Tailed Tests**: Classification of hypothesis tests based on whether the p-value lies in the left tail, right tail, or is split evenly between both tails.
- **Alternative Hypothesis**: Specifies whether the test is left-, right-, or two-tailed and never includes an equal sign.
- **Decision Rule Using P-Values**: Reject H0 when p-value < α; do not reject H0 when p-value > α.
- **Evidence Strength From P-Value**: Smaller p-values provide more confidence in rejecting H0; larger p-values provide more confidence in not rejecting H0.
- **Null Hypothesis Parameter Value**: The parameter value used in test calculations comes from H0, not from the sample data.
- **Type I Error**: Rejecting the null hypothesis when the null hypothesis is true.
- **Type II Error**: Not rejecting the null hypothesis when the null hypothesis is false.
- **Z-Test For A Single Mean**: A hypothesis test for a population mean using the normal distribution when the population standard deviation is known.
- **Sampling Distribution Of The Sample Mean (Known σ)**: When σ is known, X̄ is normal with mean μ and standard deviation σ/√n.
- **T-Test For A Single Mean**: A hypothesis test for a population mean using Student’s t distribution when σ is unknown and the data are from a normal distribution.
- **Degrees Of Freedom (t-Test)**: For a single-mean t-test, df = n − 1.
- **One-Proportion Z-Test**: A hypothesis test for a single population proportion using the normal distribution of the sample proportion.
- **Sampling Distribution Of The Sample Proportion**: P′ ~ N(p, pq/n), where p is the population proportion and q = 1 − p.
- **Sample Proportion (P′)**: The estimated proportion computed as p′ = x/n.
- **Conditions For One-Proportion Z-Test**: Sufficiently large np and nq, two independent outcomes, and a fixed probability of success.
- **Critical Value Approach**: Traditional decision method comparing the test statistic (z-score from data) to a critical value (z-score from α).
- **Actual Level Of Significance**: Another term for the p-value.
- **Significance Level Choice For Critical Issues**: Use a very low α to minimize the chance of a Type I error when consequences are serious.


---
<!-- Total tokens: 24710 -->
# Section: seg_125 Heading：9.6 hypothesis testing of a single mean and single proportion

- **Hypothesis**: A statement about a population parameter; the statement assumed true is the null hypothesis and the contradictory statement is the alternative hypothesis.
- **Null Hypothesis**: The hypothesis assumed to be true and tested; it must include equality (equals, less than or equal to, or greater than or equal to).
- **Alternative Hypothesis**: The contradictory claim to the null; written with <, >, or ≠.
- **Hypothesis Testing**: A procedure using sample evidence to decide whether a stated hypothesis should be rejected or not rejected.
- **Level Of Significance**: The probability of a Type I error (rejecting a true null); denoted α and preset before testing.
- **p-Value**: The probability of the observed result (or more extreme) occurring by chance assuming the null hypothesis is true; smaller values indicate stronger evidence against the null.
- **Type I Error**: Rejecting the null hypothesis when it is true.
- **Type II Error**: Not rejecting the null hypothesis when it is false.
- **Power Of The Test**: The quantity 1 − β; the likelihood of correctly accepting a true alternative hypothesis.
- **Binomial Distribution**: A discrete distribution for the number of successes in a fixed number of independent Bernoulli trials with success probability p.
- **Normal Distribution**: A continuous distribution with mean μ and standard deviation σ; if μ = 0 and σ = 1, it is the standard normal distribution.
- **Student's t-Distribution**: A continuous, symmetric distribution centered at zero, flatter than the normal, approaching the standard normal as sample size increases; each distribution is defined by degrees of freedom.
- **Central Limit Theorem**: For sufficiently large samples, the distributions of sample means and sample sums are approximately normal regardless of population shape; the mean of sample means equals the population mean.
- **Standard Error Of The Mean**: The standard deviation of the sampling distribution of the sample mean, σ/√n.
- **Decision Rule Using p-Value**: If α > p-value, reject H0; if α ≤ p-value, do not reject H0.
- **Student's t-Test For A Single Mean**: Use when data are from a simple random sample and the population is approximately normal or the sample size is large, with unknown standard deviation.
- **Normal Test For A Single Mean**: Use when data are from a simple random sample and the population is approximately normal or the sample size is large, with known standard deviation.
- **Normal Test For A Single Proportion**: Use for a single population proportion when data meet binomial conditions and both np and nq are greater than five.
- **Rare Event**: An event with low probability that occurs; its occurrence informs decisions to reject or not reject a null hypothesis.
- **Degrees Of Freedom**: For the t-distribution, one less than the number of data items.

