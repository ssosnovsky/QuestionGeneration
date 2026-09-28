
---
<!-- Total tokens: 0 -->
# Chapter: seg_99 Heading：chapter 8: confidence intervals




---
<!-- Total tokens: 9154 -->
# Section: seg_101 Heading：8.1 a single population mean using the normal distribution

- **Confidence Interval For A Population Mean**: An interval estimate for μ when σ is known, with format (x̄ − EBM, x̄ + EBM), based on the normal sampling distribution of x̄.
- **Point Estimate Of The Population Mean**: The sample mean x̄ used as the estimate of the unknown population mean μ.
- **Error Bound For A Population Mean (EBM)**: The margin of error for estimating μ when σ is known; EBM = z_{α/2} · (σ/√n) and depends on the confidence level.
- **Confidence Level (CL)**: The percent of confidence intervals that contain the true population parameter under repeated sampling; CL = 1 − α.
- **Alpha (α)**: The probability that the confidence interval does not contain the true parameter; α is split equally with α/2 in each tail of the standard normal distribution.
- **Z-Score For Confidence Level (z_{α/2})**: The critical value from Z ~ N(0, 1) with right-tail area α/2 (left-tail area 1 − α/2), used to compute EBM.
- **Standard Error Of The Mean**: The standard deviation of the sampling distribution of x̄, given by σ/√n.
- **Sampling Distribution Of The Sample Mean**: For known σ, x̄ is (approximately) normally distributed with mean μ and standard deviation σ/√n, justifying the use of the normal distribution for intervals.
- **Conditions For Using A Z-Interval For A Mean**: Requires data from a random sample and a known population standard deviation σ.
- **Confidence Interval Construction Steps**: Compute x̄; find z for the stated CL; calculate EBM; form x̄ ± EBM; write a context-specific interpretation.
- **Interpretation Of A Confidence Interval**: State CL, the parameter (μ), and the interval; template: “We estimate with ___% confidence that the true population mean (context) is between ___ and ___.”
- **Effect Of Changing The Confidence Level**: Increasing CL increases EBM and widens the interval; decreasing CL decreases EBM and narrows the interval.
- **Effect Of Changing The Sample Size**: Increasing n decreases EBM, narrowing the interval; decreasing n increases EBM, widening the interval.
- **Working Backwards From A Confidence Interval**: EBM = (upper − lower)/2; x̄ = (upper + lower)/2 (or upper − EBM).
- **Sample Size For A Desired Margin Of Error**: Required n = (z^2 σ^2)/(EBM^2) with z = z_{α/2}; always round up to the next integer.


---
<!-- Total tokens: 5563 -->
# Section: seg_103 Heading：8.2 a single population mean using the student t distribution

- **Student's T-Distribution**: Probability distribution used for inference about a single population mean when the population standard deviation is unknown and the sample standard deviation s is used; its shape depends on degrees of freedom and has heavier tails than the standard normal.

- **When To Use Student's T-Distribution**: Use whenever the population standard deviation is unknown and s is used as an estimate for σ, regardless of sample size.

- **T-Score**: Standardized statistic t = (x̄ − μ) / (s / √n) that measures how far the sample mean is from the population mean; follows a Student's t-distribution with n − 1 degrees of freedom under the stated assumptions.

- **Degrees Of Freedom**: The quantity df = n − 1 arising from the calculation of the sample standard deviation; represents the number of deviations that can vary freely.

- **Properties Of The Student's T-Distribution**: Mean 0 and symmetric; heavier tails and greater spread than the standard normal; approaches the standard normal as degrees of freedom increase.

- **Assumptions For Using Student's T-Distribution**: Simple random sample from a population that is approximately normally distributed with unknown μ and σ.

- **Notation For Student's T-Distribution**: T ~ t_df, where df = n − 1.

- **Error Bound For The Mean (EBM)**: Margin of error for a population mean when σ is unknown, EBM = t_(α/2) × s / √n, where t_(α/2) is the t critical value with right-tail area α/2 and df = n − 1.

- **Confidence Interval For A Population Mean (σ Unknown)**: Interval estimate given by (x̄ − EBM, x̄ + EBM).

- **Student's T Table**: A table that provides t critical values corresponding to specified degrees of freedom and confidence levels or tail areas.


---
<!-- Total tokens: 9132 -->
# Section: seg_105 Heading：8.3 a population proportion

- **Population Proportion**: The true proportion of successes in a population, denoted p (the success probability in a binomial model).
- **Binomial Distribution For Counts**: The model for the number of successes X in n independent trials with success probability p, denoted X ~ B(n, p).
- **Sample Proportion (p′ Or p̂)**: The estimated proportion of successes in a sample, defined as X/n; a point estimate of p.
- **Complement Proportions (q And q′)**: The failure proportions defined by q = 1 − p and q′ = 1 − p′.
- **Normal Approximation For Sample Proportion**: For large n with p not near 0 or 1, P′ is approximately normal with mean p and standard deviation sqrt(pq/n).
- **Z-Score For Sample Proportion**: The standardized statistic z = (p′ − p) / sqrt(pq/n) under the normal model for proportions.
- **Confidence Interval For A Population Proportion**: The interval (p′ − EBP, p′ + EBP) estimating the true proportion p.
- **Error Bound For A Proportion (EBP)**: The margin of error EBP = z_{α/2} sqrt(p′ q′ / n), computed with sample proportions because p and q are unknown.
- **Conditions For Proportion Confidence Interval**: The method is valid only if np′ > 5 and nq′ > 5.
- **Identifying A Proportion Problem**: Problems with a binomial setup for counts of successes and no mention of a mean or average.
- **“Plus-Four” Confidence Interval For p**: An adjustment adding two successes and two failures (use x + 2 and n + 4) to improve accuracy; use when confidence level ≥ 90% and sample size ≥ 10.
- **Sample Size For Estimating A Proportion**: Required n to achieve a desired error bound is n = (z_{α/2}^2 p′ q′) / EBP^2.
- **Conservative Choice Of p′ For Sample Size**: When p′ is unknown, use p′ = q′ = 0.5 to maximize p′q′ = 0.25 and obtain the largest required n.
- **Confidence Level And α**: The relationship α = 1 − CL with z_{α/2} used in the interval; the confidence level is the long-run proportion of such intervals that contain the true p.


---
<!-- Total tokens: 5263 -->
# Section: seg_107 Heading：8.4 confidence interval (home costs)

- **Confidence Interval**: An interval estimate for the mean cost of a home at a stated confidence level.
- **Confidence Level**: The specified percentage associated with the interval (e.g., 90%, 95%, 99%).
- **Alpha (α)**: The combined area in both tails outside the confidence interval.
- **Tail Area (α/2)**: The area in each tail outside the confidence interval.
- **Error Bound For The Mean (EBM)**: The amount added to and subtracted from the sample mean to obtain the interval’s upper and lower limits.
- **Sample Mean (X̄)**: The mean of the sample sale prices used in constructing the interval.
- **Sample Standard Deviation (Sx)**: The standard deviation computed from the sample sale prices.
- **Sample Size (N)**: The number of sampled homes used in the analysis.
- **Random Variable X̄**: The sample mean defined in words as the random variable representing the mean sale price from a sample.
- **Estimated Distribution For X̄**: The assumed distribution (in words and symbols) used to model X̄ when building the confidence interval.
- **Confidence Interval Limits**: The lower and upper endpoints of the confidence interval placed on the number line.
- **Interval Width**: The distance between the lower and upper limits of the confidence interval.
- **Interpretation Of A Confidence Interval**: The explanation of what the interval conveys about the mean in general and for this study.
- **Effect Of Confidence Level On EBM And Width**: How changes in confidence level affect the error bound and the width of the interval.
- **Random Sampling**: Selecting homes randomly to form a sample for estimating the mean cost.


---
<!-- Total tokens: 3966 -->
# Section: seg_109 Heading：8.5 confidence interval (place of birth)

- **Confidence Interval**: The interval to be computed for the proportion of students in this school who were born in this state at a specified confidence level.
- **Error Bound For A Proportion (EBP)**: The error bound associated with the confidence interval for the sample proportion.
- **Confidence Level**: The specified percentage (e.g., 50%, 80%, 95%, 99%) that determines the confidence interval and its error bound.
- **Combined Tail Area (Alpha)**: The total area in both tails of the distribution used for the confidence interval, denoted α.
- **Tail Area (Alpha/2)**: The area in each tail of the distribution used for the confidence interval, denoted α/2.
- **Sample Proportion (P′)**: The random variable representing the sample proportion for this survey.
- **Sample Size (n)**: The number of students surveyed in the class.
- **Number Born In This State (x)**: The count of surveyed students who were born in this state.
- **Estimated Distribution**: The distribution stated for use when constructing the confidence interval for the sample proportion.
- **Upper And Lower Limits**: The endpoints of the confidence interval to be placed on a number line along with the sample proportion.
- **Interpretation Of Confidence Interval**: The explanation of what a confidence interval means in general and for this particular study.
- **Effect Of Confidence Level On Error Bound And Interval Width**: The relationship describing how EBP and the width of the confidence interval change as the confidence level increases.


---
<!-- Total tokens: 23458 -->
# Section: seg_111 Heading：8.6 confidence interval (women's heights)

- **Confidence Interval (CI)**: An interval estimate for an unknown population parameter that depends on the desired confidence level, information about the distribution, and the sample size.
- **Confidence Level (CL)**: The percent probability that a constructed confidence interval contains the true population parameter.
- **Confidence Interval General Form**: (lower bound, upper bound) = (point estimate − error bound, point estimate + error bound).
- **Error Bound For A Population Mean (EBM)**: The margin of error for estimating a population mean; depends on confidence level, sample size, and the known or estimated population standard deviation.
- **Error Bound For A Population Proportion (EBP)**: The margin of error for estimating a population proportion; depends on confidence level, sample size, and the estimated proportion of successes.
- **Parameter**: A numerical characteristic of a population.
- **Point Estimate**: A single number computed from a sample used to estimate a population parameter.
- **Standard Deviation**: The square root of the variance measuring dispersion from the mean; denoted s for a sample and σ for a population.
- **Degrees Of Freedom (Df)**: The number of objects in a sample that are free to vary.
- **Normal Distribution**: A continuous distribution with mean μ and standard deviation σ, denoted X ~ N(μ, σ).
- **Standard Normal Distribution**: The normal distribution with mean 0 and standard deviation 1.
- **Student's T-Distribution**: A continuous, symmetric distribution centered at zero, more spread out than the normal, approaching the standard normal as n increases; defined by degrees of freedom df = n − 1.
- **t-Score**: The standardized statistic t = (x̄ − μ) / (s/√n) that follows the Student’s t-distribution with n − 1 degrees of freedom.
- **Critical Z-Value**: The z-score with area to the right equal to α/2, used to compute EBM when σ is known.
- **Critical T-Value**: The t-score with area to the right equal to α/2, used to compute EBM when σ is unknown.
- **Alpha (α)**: The proportion of confidence intervals that do not contain the population parameter; α = 1 − CL.
- **Sampling Distribution Of The Sample Mean**: The distribution of x̄ is normal with mean μ and standard deviation σ/√n (under normality or by the central limit theorem).
- **Sample Proportion (p′)**: The statistic x/n estimating the population proportion, with q′ = 1 − p′.
- **Sampling Distribution Of The Sample Proportion**: The distribution of p′ is binomial and can be approximated by normal with mean p and variance pq/n.
- **Confidence Interval For A Single Population Mean (σ Known)**: Use the normal distribution with EBM = z(α/2)·σ/√n and interval (x̄ − EBM, x̄ + EBM).
- **Confidence Interval For A Single Population Mean (σ Unknown)**: Use the Student’s t-distribution with df = n − 1, EBM = t(α/2)·s/√n, and interval (x̄ − EBM, x̄ + EBM).
- **Confidence Interval For A Population Proportion**: (p′ − EBP, p′ + EBP) with EBP = z(α/2)·√(p′q′/n).
- **Plus Four Method**: For small samples in proportion estimates, adjust p′ by using (x + 2)/(n + 4) before constructing the confidence interval.
- **Sample Size For Estimating A Population Mean**: n = (z·σ/EBM)² to achieve a desired margin of error at a given confidence level.
- **Sample Size For Estimating A Population Proportion**: n = z(α/2)²·p′q′/EBP² for a specified margin of error and confidence level.
- **Effect Of Confidence Level And Sample Size On Margin Of Error**: As the confidence level increases, EBM increases; as the sample size increases, EBM decreases.
- **Binomial Distribution**: A discrete random variable counting successes in n independent Bernoulli trials with X ~ B(n, p), mean μ = np, and standard deviation σ = √(npq).
- **Inferential Statistics**: Estimating population parameters based on sample statistics.

