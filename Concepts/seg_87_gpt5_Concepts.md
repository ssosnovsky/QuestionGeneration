
---
<!-- Total tokens: 0 -->
# Chapter: seg_87 Heading：chapter 7: the central limit theorem




---
<!-- Total tokens: 5851 -->
# Section: seg_89 Heading：7.1 the central limit theorem for sample means (averages)

- **Central Limit Theorem For Sample Means**: As sample size n increases, the distribution of the sample mean X̄ approaches normal with mean μ and variance σ²/n.
- **Sampling Distribution Of The Mean**: The distribution of X̄ formed from sample means; it approaches a normal distribution as n increases.
- **Mean Of The Sampling Distribution**: The expected value of X̄ equals the population mean μ (i.e., μ is the average of both X and X̄).
- **Variance Of The Sampling Distribution**: The variance of X̄ equals the population variance divided by the sample size n.
- **Standard Error Of The Mean**: The standard deviation of X̄; σ_{x̄} = σ/√n; describes how far, on average, the sample mean is from the population mean in repeated samples of size n.
- **Z-Score For Sample Means**: The standardized value for X̄ given by z = (x̄ − μ) / (σ/√n), distinct from the z-score for individual observations.
- **Sample Size Interpretation (n)**: n is the number of values averaged in each sample, not the number of times the experiment is performed.
- **Normalcdf For Sample Mean Probabilities**: Calculator function normalcdf(lower, upper, mean, standard error of the mean) for finding probabilities of sample means, using the original mean and standard deviation with sample size n.
- **InvNorm For Sample Mean Percentiles**: Calculator function invNorm(area to the left, mean, standard error of the mean) for finding percentiles of sample means; k denotes the kth percentile.


---
<!-- Total tokens: 5090 -->
# Section: seg_91 Heading：7.2 the central limit theorem for sums

- **Central Limit Theorem For Sums**: As sample size n increases, the sum ΣX of n observations tends to follow a normal distribution with mean nμX and standard deviation σX times the square root of n.

- **Random Variable ΣX**: The sum (total) of n values drawn from the original distribution of X.

- **Mean Of Sums**: The mean of the sums distribution is n times the mean of the original distribution (nμX).

- **Standard Deviation Of Sums**: The standard deviation of the sums distribution is the original standard deviation multiplied by the square root of the sample size (σX√n).

- **Z-Score For Sums**: The standardized value for a single observed sum Σx is (Σx − nμX) divided by σX times the square root of n.

- **Normalcdf For Sums**: Calculator function to find probabilities for sums using normalcdf(lower, upper, n×mean, √n×standard deviation).

- **InvNorm For Sums**: Calculator function to find percentiles for sums using invNorm(area to the left, n×mean, √n×standard deviation).


---
<!-- Total tokens: 8274 -->
# Section: seg_93 Heading：7.3 using the central limit theorem

- **Central Limit Theorem For Sample Means**: For large sample sizes, the sampling distribution of the mean X̄ is approximately normal with mean μ and standard deviation σ/√n; use this to compute probabilities and percentiles for sample means.
- **Central Limit Theorem For Sums**: For large sample sizes, the distribution of the sum ΣX is approximately normal with mean nμ and standard deviation √n·σ; use this to compute probabilities and percentiles for totals.
- **Appropriate Use Of The CLT**: Use the CLT when finding probabilities or percentiles for means or sums; for individual values, do not use the CLT and instead use the variable’s own distribution.
- **Law Of Large Numbers**: As sample size increases, the sample mean x̄ approaches the population mean μ, with the sampling distribution of x̄ becoming normal and its standard deviation decreasing as n grows.
- **Standard Error Of The Mean**: The standard deviation of the sampling distribution of X̄ equals σ/√n and decreases as sample size n increases.
- **Normal Approximation To The Binomial**: When np > 5 and nq > 5 (better if both ≥ 10), a binomial X ~ B(n, p) is approximated by a normal distribution with mean μ = np and standard deviation σ = √(npq), where q = 1 − p.
- **Continuity Correction Factor**: When using the normal approximation to a binomial distribution, adjust x by ±0.5 (use x ± 0.5) to improve the approximation.


---
<!-- Total tokens: 5926 -->
# Section: seg_95 Heading：7.4 central limit theorem (pocket change)

- **Central Limit Theorem**: Properties to be demonstrated and compared by examining how distributions of averages change as n changes.
- **Sample Size (n)**: The number surveyed at a time within each sample (e.g., n = 1, 2, 5).
- **Average (x̄)**: The calculated average of recorded change values for each sampling scenario.
- **Statistic S (s)**: A calculated statistic recorded alongside x̄ for each sample size.
- **Histogram**: A graph constructed with five to six intervals and scaled axes to display the collected data or averages.
- **Smooth Curve Through Histogram**: A curve drawn through the tops of the bars to describe the general shape of the distribution.
- **Approximate Distribution Notation (X ~ …)**: Notation used to state the approximate distribution of the data.
- **Approximate Distribution Of Averages Notation (X̄ ~ …)**: Notation used to state the approximate distribution of the averages.
- **Random Survey**: Random selection of classmates, pairs, or groups to collect data.


---
<!-- Total tokens: 15917 -->
# Section: seg_97 Heading：7.5 central limit theorem (cookie recipes)

- **Central Limit Theorem**: For sufficiently large sample size n from a population with mean μ and standard deviation σ, the sample mean X̄ and the sample sum ΣX have approximately normal distributions: X̄ ~ N(μ, σ/√n) and ΣX ~ N(nμ, √n·σ). The mean of the sample means equals μ, and the mean of the sample sums equals nμ. The standard deviation of the sample means is the standard error of the mean.

- **Central Limit Theorem For Sample Means (Averages)**: For large n, the distribution of sample means is approximately normal with mean equal to the population mean and standard deviation equal to the population standard deviation divided by √n.

- **Central Limit Theorem For Sums**: For large n, the distribution of sample sums is approximately normal with mean nμ and standard deviation √n·σ, regardless of the population’s shape.

- **Sampling Distribution**: The probability distribution of a statistic (such as mean, proportion, or standard deviation) computed from all simple random samples of size n from a population.

- **Standard Error Of The Mean**: The standard deviation of the sampling distribution of the sample mean, equal to σ/√n.

- **Normal Distribution**: A continuous distribution with pdf f(x) = (1/(σ√(2π))) e^{-(x−μ)²/(2σ²)}; notation X ~ N(μ, σ). The standard normal is the case μ = 0, σ = 1.

- **Mean**: A measure of central tendency; sample mean x̄ = (sum of sample values)/(number of sample values) and population mean μ = (sum of population values)/(number of population values).

- **Law Of Large Numbers**: As sample size increases, the sample mean x̄ tends to get closer to the population mean μ.

- **Z-Score For Sample Means**: The standardized value of a sample mean given by z = (x̄ − μx)/(σx/√n).

- **Z-Score For Sums**: The standardized value of a sample sum given by z = (Σx − nμx)/(√n·σx).

