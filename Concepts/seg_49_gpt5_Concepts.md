
---
<!-- Total tokens: 0 -->
# Chapter: seg_49 Heading：chapter 4: discrete random variables




---
<!-- Total tokens: 3788 -->
# Section: seg_51 Heading：4.1 probability distribution function (pdf) for a discrete random variable

- **Discrete Probability Distribution Function (PDF)**: A probability model for a discrete random variable where each probability is between zero and one, inclusive, and the sum of all probabilities is one.
- **P(x) Notation**: The probability that the random variable X takes on the value x.
- **Probability Distribution Table (PDF Table)**: A two-column table labeled x and P(x) that lists values of X and their corresponding probabilities, with the probabilities summing to one.


---
<!-- Total tokens: 6079 -->
# Section: seg_53 Heading：4.2 mean or expected value and standard deviation

- **Law Of Large Numbers**: As the number of trials increases, the difference between an event’s theoretical probability and its relative frequency approaches zero.
- **Expected Value (Mean)**: The long-term average outcome of an experiment, denoted μ; computed by summing x·P(x) over all values of a random variable.
- **Expected Value Table**: A table with columns for x, P(x), and x·P(x) used to calculate the expected value (long-term average).
- **Standard Deviation Of A Probability Distribution**: The measure of spread for a probability distribution, denoted σ; computed as the square root of the sum of (x – μ)²·P(x) over all values.
- **Probability Distribution Function**: A modeling pattern used to match probability problems to known distributions for calculation; each distribution has distinct characteristics and serves as a tool for problem solving.


---
<!-- Total tokens: 7671 -->
# Section: seg_55 Heading：4.3 binomial distribution

- **Binomial Experiment**: An experiment with a fixed number of trials (n), each trial has two possible outcomes (success or failure) with probabilities p and q where p + q = 1, and trials are independent and conducted under identical conditions.
- **Probability Of Success (p) And Failure (q)**: p denotes the probability of success on a single trial; q denotes the probability of failure on a single trial; p + q = 1.
- **Binomial Random Variable (X)**: The number of successes obtained in the n independent trials of a binomial experiment.
- **Binomial Distribution Mean**: μ = n p.
- **Binomial Distribution Variance**: σ² = n p q.
- **Binomial Distribution Standard Deviation**: σ = sqrt(n p q).
- **Bernoulli Trial**: A two-outcome experiment with constant probabilities (characteristics two and three) where n = 1.
- **Binomial Distribution Notation**: X ~ B(n, p), where n is the number of trials and p is the probability of success on each trial.
- **Binompdf**: A function that computes P(X = value) for a binomial distribution.
- **Binomcdf**: A function that computes P(X ≤ value) for a binomial distribution.


---
<!-- Total tokens: 6102 -->
# Section: seg_57 Heading：4.4 geometric distribution

- **Geometric Experiment**: A sequence of one or more Bernoulli trials repeated until the first success, with the number of trials potentially unbounded and constant probabilities p (success) and q (failure) where p + q = 1.
- **Probability Of Success (p) And Failure (q)**: p is the probability of success on each trial; q = 1 − p; these probabilities remain the same for each trial.
- **Geometric Random Variable (X)**: The number of independent trials until the first success; takes values 1, 2, 3, …
- **Geometric Distribution Notation**: X ~ G(p), where G denotes the Geometric Probability Distribution Function and p is the parameter (probability of success per trial).
- **Mean Of Geometric Distribution**: μ = 1/p.
- **Variance Of Geometric Distribution**: σ² = (1/p)(1/p − 1).
- **Standard Deviation Of Geometric Distribution**: σ = √[(1/p)(1/p − 1)].


---
<!-- Total tokens: 3975 -->
# Section: seg_59 Heading：4.5 hypergeometric distribution

- **Hypergeometric Experiment**: Sampling from two groups, designating a first group of interest, without replacement, with dependent selections, and not Bernoulli trials.
- **Hypergeometric Probability Distribution**: The distribution governing the outcomes of a hypergeometric experiment.
- **Group Of Interest (First Group)**: The designated group among the two from which the counted items are drawn for the probability question.
- **Random Variable X**: The number of items from the group of interest in the sample.
- **Hypergeometric Notation**: X ~ H(r, b, n) indicates that X has a hypergeometric distribution.
- **Parameters (r, b, n)**: r = size of the group of interest (first group); b = size of the second group; n = size of the chosen sample.
- **Mean Of Hypergeometric Distribution**: The expected value mu = n r / (r + b).


---
<!-- Total tokens: 5964 -->
# Section: seg_61 Heading：4.6 poisson distribution

- **Poisson Distribution**: A probability model for the number of events occurring in a fixed interval of time or space when events occur at a known average rate and independently of the time since the last event.
- **Interval Of Interest**: The fixed time or space span over which event occurrences are counted in the Poisson model.
- **Random Variable For Poisson**: X equals the number of occurrences in the interval of interest and takes values 0, 1, 2, …
- **Poisson Notation And Parameter**: X ~ P(μ), where μ (also denoted λ) is the mean number of occurrences for the interval of interest.
- **Poisson Approximation To The Binomial**: A Poisson model can approximate a binomial distribution when p is small and n is large; under this approximation, the Poisson mean is μ = np.


---
<!-- Total tokens: 6155 -->
# Section: seg_63 Heading：4.7 discrete distribution (playing card experiment)

- **Discrete Distribution**: A distribution used to model discrete outcomes for the experiment.
- **Theoretical Distribution**: The distribution that provides expected probabilities for values of X.
- **Empirical Data**: Data obtained from conducting the card-picking experiment and recording outcomes.
- **Simulation Distribution**: A distribution produced by technology-generated simulation for comparison with a theoretical distribution.
- **Long-Term Probabilities**: Probabilities considered over many repetitions of the experiment.
- **Theoretical Probability**: A probability determined by theory for an event in the experiment.
- **Random Variable X**: The number of diamonds picked in ten trials.
- **Distribution Notation X ~ B( , )**: Notation indicating the assumed distribution of X with two values to be specified.
- **Theoretical PDF Chart**: A table listing x and P(x) for the theoretical distribution.
- **Probability Notation P(x)**: Notation used to denote the probability of X taking specified values or ranges.
- **Relative Frequency**: The calculated frequency of each x relative to the total number of trials in the class data.
- **RF Notation**: Abbreviation RF used for relative frequency in expressions such as RF(x = 3).
- **Histogram**: A graph constructed for the empirical data and for the theoretical distribution.
- **Mean (x̄)**: The calculated mean from the empirical data.
- **Standard Deviation (s)**: The calculated standard deviation from the empirical data.
- **Theoretical Mean (μ)**: The mean of the theoretical distribution.
- **Theoretical Standard Deviation (σ)**: The standard deviation of the theoretical distribution.
- **Comparison Of Distributions**: Analysis of similarities and differences among the theoretical, empirical, and simulation distributions.


---
<!-- Total tokens: 24550 -->
# Section: seg_65 Heading：4.8 discrete distribution (lucky dice experiment)

- **Bernoulli Trials**: An experiment with two possible outcomes (success and failure) for each trial, with constant probability p of success and q = 1 − p of failure.

- **Binomial Experiment**: A statistical experiment with a fixed number n of independent, identically conducted trials, each having two outcomes (success/failure) with probabilities p and q.

- **Binomial Probability Distribution**: A discrete random variable X counting successes in n Bernoulli trials; notation X ~ B(n, p) with probability P(X = x) = (n choose x) p^x q^(n − x).

- **Probability Distribution Function (PDF)**: A mathematical description (formula or table) of a discrete random variable’s outcomes and their probabilities, where each probability is between 0 and 1 and the probabilities sum to 1.

- **Random Variable (RV)**: A variable whose value is determined by the outcome of a random experiment; denoted by uppercase letters (e.g., X), with specific values observed after the experiment.

- **Expected Value**: The long-term average (mean) of a discrete random variable; denoted μ and given by μ = Σ xP(x).

- **Standard Deviation Of A Probability Distribution**: A measure of how far the outcomes of a statistical experiment are from the mean of the distribution.

- **Geometric Experiment**: A process of Bernoulli trials with all failures except the last (a success), potentially continuing indefinitely, with constant probabilities p and q.

- **Geometric Distribution**: A discrete random variable X denoting the number of trials until the first success; notation X ~ G(p) with P(X = x) = p(1 − p)^(x − 1).

- **Hypergeometric Experiment**: Sampling without replacement from two groups, focusing on a group of interest; selections are not independent and do not constitute Bernoulli trials.

- **Hypergeometric Probability Distribution**: A discrete random variable X counting successes from the group of interest in n draws without replacement; notation X ~ H(r, b, n), where r and b are group sizes.

- **Poisson Probability Distribution**: A discrete random variable counting events in a fixed interval occurring with a known mean and independently of the time since the last event; notation X ~ P(μ) with P(X = x) = (e^−μ μ^x)/x!; often used to approximate the binomial when n is large and p is small.

- **Law Of Large Numbers**: As the number of trials increases, the difference between theoretical probability and relative frequency approaches zero.

