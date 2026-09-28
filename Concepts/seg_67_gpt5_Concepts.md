
---
<!-- Total tokens: 0 -->
# Chapter: seg_67 Heading：chapter 5: continuous random variables




---
<!-- Total tokens: 3677 -->
# Section: seg_69 Heading：5.1 continuous probability functions

- **Continuous Probability Density Function (PDF)**: A function f(x) defined so that the area between f(x) and the x-axis over any interval equals the probability that the variable lies in that interval; the total area is 1.
- **Zero Probability At A Point**: For continuous distributions, the probability at an exact value is zero, P(X = x) = 0.
- **Cumulative Distribution Function (CDF)**: P(X ≤ x) (equivalently P(X < x) for continuous distributions) giving the area to the left under the density.
- **Right-Tail Probability (Complement Rule)**: For continuous distributions, P(X > x) = 1 − P(X < x), giving the area to the right.


---
<!-- Total tokens: 8037 -->
# Section: seg_71 Heading：5.2 the uniform distribution

- **Uniform Distribution**: A continuous probability distribution in which all outcomes within a specified interval are equally likely.
- **Uniform Distribution Notation**: X ~ U(a, b), where a is the lowest possible value of x and b is the highest.
- **Probability Density Function (Uniform)**: f(x) = 1/(b − a) for a ≤ x ≤ b.
- **Mean Of A Uniform Distribution**: μ = (a + b)/2.
- **Standard Deviation Of A Uniform Distribution**: σ = (b − a)/√12.
- **Interval Endpoints Inclusivity**: In uniform distribution problems, determine whether the interval includes or excludes its endpoints.
- **Probability Over An Interval (Uniform)**: Probabilities are computed as rectangle area: P(c < X < d) = (base)(height) with base d − c and height 1/(b − a).
- **Percentile In A Uniform Distribution**: A value k such that P(X < k) = p, obtained by the area under the constant density on [a, b].
- **Conditional Probability In A Uniform Distribution**: Conditioning on a sub-interval (e.g., X > c) restricts the support and yields a new uniform density on that interval; alternatively use P(A|B) = P(A AND B)/P(B).


---
<!-- Total tokens: 8022 -->
# Section: seg_73 Heading：5.3 the exponential distribution

- **Exponential Distribution**: A continuous distribution used to model the time until an event occurs or the waiting time between events.
- **Decay Parameter (m)**: The parameter of the exponential distribution defined by m = 1/μ.
- **Distribution Notation**: X ~ Exp(m), indicating X follows an exponential distribution with decay parameter m.
- **Probability Density Function (Exponential)**: f(x) = m e^(-mx) for x ≥ 0.
- **Cumulative Distribution Function (Exponential)**: P(X < x) = 1 − e^(−mx).
- **Survival Function (Exponential)**: P(X > x) = e^(−mx).
- **Mean And Standard Deviation (Exponential)**: The mean μ equals the standard deviation σ, with μ = 1/m and σ = μ.
- **Percentile Formula (Exponential)**: For left-tail probability A, the percentile k is k = ln(1 − A)/(-m).
- **Memoryless Property (Exponential)**: P(X > r + t | X > r) = P(X > t) for all r ≥ 0 and t ≥ 0.
- **Relationship To Poisson Distribution**: If independent inter-event times are exponential with mean μ, the event count per unit time is Poisson with mean λ = 1/μ; conversely, Poisson event counts imply exponential interarrival times.


---
<!-- Total tokens: 15505 -->
# Section: seg_75 Heading：5.4 continuous distribution

- **Probability Density Function (PDF)**: For a continuous random variable, a nonnegative function f(x) with total area 1 where the area under f(x) between a and b equals P(a < X < b).
- **Cumulative Distribution Function (CDF)**: A function F(x) = P(X ≤ x) that gives the probability a random variable is less than or equal to x.
- **Uniform Distribution**: A continuous distribution on [a, b] with equally likely outcomes; notation X ~ U(a, b); pdf f(x) = 1/(b − a) for a ≤ x ≤ b; cdf P(X ≤ x) = (x − a)/(b − a).
- **Exponential Distribution**: A continuous distribution for waiting times; notation X ~ Exp(m) with m > 0; pdf f(x) = m e^(−mx) for x ≥ 0; cdf P(X ≤ x) = 1 − e^(−mx); mean μ = 1/m; standard deviation σ = 1/m; has the memoryless property.
- **Decay Parameter**: The rate m of an exponential distribution representing how probabilities decay, appearing in f(x) = m e^(−mx) and equal to 1/μ.
- **Memoryless Property**: For an exponential random variable X, P(X > x + k | X > x) = P(X > k), indicating future probabilities do not depend on past information.
- **Poisson Distribution**: The distribution of the number of events X in one unit of time when events occur independently at rate λ, with P(X = k) = (λ^k e^(−λ)) / k!.
- **Exponential–Poisson Relationship**: If waiting time between events T ~ Exp(λ), then the number of events X per unit time follows a Poisson distribution with mean λ.
- **Conditional Probability**: The likelihood of an event occurring given that another event has already occurred.

