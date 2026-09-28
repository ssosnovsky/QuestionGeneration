
---
<!-- Total tokens: 0 -->
# Chapter: seg_77 Heading：chapter 6: the normal distribution




---
<!-- Total tokens: 5557 -->
# Section: seg_79 Heading：6.1 the standard normal distribution

- **Standard Normal Distribution**: A normal distribution of standardized values (z-scores) with mean 0 and standard deviation 1; denoted Z ~ N(0, 1).
- **Z-Score**: The number of standard deviations a value x is from the mean μ, calculated as z = (x − μ)/σ; positive values are above the mean, negative values below, and zero equals the mean.
- **Normal Distribution Notation**: X ~ N(μ, σ) indicates a normally distributed random variable with mean μ and standard deviation σ.
- **Standardization (Z-Transformation)**: The transformation z = (x − μ)/σ that converts X ~ N(μ, σ) to Z ~ N(0, 1); the inverse is x = μ + zσ.
- **Empirical Rule (68-95-99.7 Rule)**: In a normal distribution, about 68% of values lie within ±1σ of the mean, about 95% within ±2σ, and about 99.7% within ±3σ.
- **Comparing Values Using Z-Scores**: Z-scores place differently scaled normal data on a common scale, allowing direct comparison relative to their means and standard deviations.


---
<!-- Total tokens: 6769 -->
# Section: seg_81 Heading：6.2 using the normal distribution

- **Area To The Left**: For a normal variable X, P(X < x) equals the area to the left of the vertical line at x.
- **Area To The Right**: P(X > x) equals 1 − P(X < x) and corresponds to the area to the right of the vertical line at x.
- **Inequality Equivalence In Continuous Distributions**: For continuous distributions, P(X < x) = P(X ≤ x) and P(X > x) = P(X ≥ x).
- **Normal Distribution Notation**: X ~ N(μ, σ) denotes X is normally distributed with mean μ and standard deviation σ.
- **Normalcdf Function**: Technology function used to calculate normal probabilities with syntax normalcdf(lower value, upper value, mean, standard deviation).
- **Invnorm Function**: Technology function used to find the value k for a given left-tail area (percentile) with syntax invNorm(area to the left, mean, standard deviation).
- **Percentile**: The value k such that a stated percentage of observations are at or below k and the remainder are at or above k.
- **Quartiles**: Q1 is the 25th percentile and Q3 is the 75th percentile of a distribution.
- **Interquartile Range (IQR)**: A spread measure defined as Q3 − Q1.
- **Critical Value**: The percentile-based cutoff k on the x-axis that separates values at or below k from those at or above k.
- **“At Least” In Probability Statements**: Interpreted as greater than or equal to (≥).
- **Standard Normal Probability Table**: A table that provides the area to the left of a z-score.


---
<!-- Total tokens: 5509 -->
# Section: seg_83 Heading：6.3 normal distribution (lap times)

- **Stratified Sampling**: A sampling method by lap (races 1 to 20) selecting six lap times from each stratum using a random number generator.
- **Random Number Generator**: A tool used to pick six lap times from each stratum.
- **Histogram**: A graph of the data using five to six intervals with scaled axes.
- **Sample Mean (X̄)**: The mean of the sample of lap times, denoted x̄, to be calculated.
- **Sample Standard Deviation (S)**: The standard deviation of the sample of lap times, denoted s, to be calculated.
- **Interquartile Range (IQR)**: A measure defined as Q3 – Q1 and reported as going from Q1 to Q3.
- **Distribution Notation (X ~ Distribution(Parameters))**: Notation specifying the approximate theoretical distribution of X and its parameters.
- **Theoretical Distribution**: A model used to compute percentiles and probabilities for lap times, using a normal approximation based on sample data.
- **Normal Approximation**: An instruction to use a normal distribution based on the sample data to approximate the theoretical distribution.
- **Empirical Probability**: A probability calculated from the collected lap time data (e.g., that a randomly chosen lap time exceeds a specified value).


---
<!-- Total tokens: 14393 -->
# Section: seg_85 Heading：6.4 normal distribution (pinkie length)

- **Normal Distribution**: A continuous random variable with pdf f(x) = (1/(σ√(2π))) e^{-(x−μ)²/(2σ²)}; parameters μ (mean) and σ (standard deviation); notation X ~ N(μ, σ).
- **Standard Normal Distribution**: A normal distribution with μ = 0 and σ = 1; denoted Z ~ N(0, 1).
- **Z-Score**: The linear transformation z = (x − μ)/σ that standardizes X ~ N(μ, σ) to Z ~ N(0, 1); for a value x, the z-score indicates how many standard deviations x is from μ.
- **Interquartile Range (IQR)**: The difference between the third and first quartiles; IQR = Q3 − Q1.
- **Empirical Rule (68-95-99.7)**: In a normal distribution, approximately 68% of values lie within 1σ, 95% within 2σ, and 99.7% within 3σ of the mean.
- **Kth Percentile In A Normal Distribution**: If the corresponding z-score is known, the kth percentile is k = μ + zσ for X ~ N(μ, σ).
- **Probability In Continuous Distributions**: For continuous distributions (including normal), P(X = x) = 0 and thus P(X < a) = P(X ≤ a).
- **Normalcdf Function**: Calculator function for normal probabilities: normalcdf(lower x, upper x, mean, standard deviation).
- **InvNorm Function**: Calculator function for normal percentiles: invNorm(area to the left, mean, standard deviation).

