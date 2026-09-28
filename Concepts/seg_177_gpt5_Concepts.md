
---
<!-- Total tokens: 0 -->
# Chapter: seg_177 Heading：chapter 13: f distribution and one-way anova




---
<!-- Total tokens: 2120 -->
# Section: seg_179 Heading：13.1 one-way anova

- **One-Way ANOVA**: A test used to determine the existence of a statistically significant difference among several group means, using variances to assess whether the means are equal.
- **Assumptions Of One-Way ANOVA**: Conditions required to perform the test: populations are normal; samples are randomly selected and independent; populations have equal standard deviations (or variances); the factor is a categorical variable; the response is a numerical variable.
- **Null Hypothesis (One-Way ANOVA)**: All group population means are equal (H0: μ1 = μ2 = ... = μk).
- **Alternative Hypothesis (One-Way ANOVA)**: At least two group population means are not equal (μi ≠ μj for some i ≠ j).
- **Factor**: A categorical variable.
- **Response**: A numerical variable.
- **Variance Of Combined Data Under H0**: Approximately the same as the variance of each population when all group means are equal.
- **Variance Of Combined Data When H0 Is False**: Larger than the variance of each population due to different group means.


---
<!-- Total tokens: 8654 -->
# Section: seg_181 Heading：13.2 the f distribution and the f-ratio

- **F Distribution**: Distribution used for F-tests with separate numerator and denominator degrees of freedom; derived from the Student’s t-distribution with values equal to squared t-values; denoted F ~ Fdf(num),df(denom).
- **F Statistic (F-Ratio)**: Ratio of mean square between groups to mean square within groups, F = MSbetween/MSwithin; approximately 1 under the null hypothesis and generally larger than 1 when the null is false.
- **One-Way ANOVA**: Procedure that extends the t-test to compare more than two groups; preferred over multiple pairwise t-tests to avoid increasing Type I error; the hypothesis test is always right-tailed.
- **Null Hypothesis (One-Way ANOVA)**: All group population means are equal.
- **Alternative Hypothesis (One-Way ANOVA)**: At least two sample groups come from populations with different normal distributions.
- **Variance Between Samples (Between-Groups Variation)**: An estimate of σ² given by the variance of sample means multiplied by n when group sizes are equal (weighted otherwise); also called variation due to treatment or explained variation.
- **Variance Within Samples (Within-Groups Variation)**: An estimate of σ² given by the average of the sample variances (pooled variance; weighted when group sizes differ); also called variation due to error or unexplained variation.
- **Sum Of Squares Between (SSbetween)**: Sum of squares representing variation among different samples; SSbetween = Σ[(s_j)²/n_j] − (Σ s_j)²/n.
- **Sum Of Squares Within (SSwithin)**: Sum of squares representing variation within samples due to chance; SSwithin = SStotal − SSbetween.
- **Total Sum Of Squares (SStotal)**: Sum of squares of all values combined minus the square of the total sum divided by n.
- **Mean Square (MS)**: Mean square (variance estimate); MSbetween = SSbetween/dfbetween and MSwithin = SSwithin/dfwithin.
- **Degrees Of Freedom Between (dfbetween)**: dfbetween = k − 1.
- **Degrees Of Freedom Within (dfwithin)**: dfwithin = n − k.
- **Simplified F-Ratio For Equal Group Sizes**: F = n · s̄x² / s²pooled, where s²pooled is the mean of the sample variances and s̄x² is the variance of the sample means.
- **Number Of Groups (k)**: The number of different groups.
- **Group Size (nj)**: The size of the jth group.
- **Group Sum (sj)**: The sum of the values in the jth group.
- **Total Sample Size (n)**: Total number of all values combined, n = Σ nj.


---
<!-- Total tokens: 6807 -->
# Section: seg_183 Heading：13.3 facts about the f distribution

- **F Distribution Shape**: Not symmetrical and skewed to the right.
- **F Distribution Degrees Of Freedom**: A different curve exists for each set of numerator and denominator degrees of freedom.
- **Nonnegativity Of F Statistic**: The F statistic takes values greater than or equal to zero.
- **Large-Degrees-Of-Freedom Approximation**: As the numerator and denominator degrees of freedom increase, the F distribution approximates the normal distribution.
- **Uses Of The F Distribution**: Includes comparing two variances and performing two-way Analysis of Variance.
- **F Distribution Notation**: Denoted as Fdf(num),df(denom), specifying numerator and denominator degrees of freedom.
- **Degrees Of Freedom In One-Way ANOVA F-Test**: Numerator degrees of freedom equal k − 1 and denominator degrees of freedom equal n − k.
- **F Statistic (F Ratio)**: The ratio of the between-group mean square to the within-group mean square in one-way ANOVA.
- **P-Value For F Test**: Computed as P(F > observed F) using the right tail of the F distribution.


---
<!-- Total tokens: 4387 -->
# Section: seg_185 Heading：13.4 test of two variances

- **F Test Of Two Variances**: A procedure using the F distribution to compare two population variances.
- **Assumptions For Two-Variance F Test**: The two populations are normally distributed and independent.
- **F Statistic For Two Variances**: F = (s1^2/σ1^2) / (s2^2/σ2^2); under H0: σ1^2 = σ2^2, F = s1^2 / s2^2.
- **F Distribution And Degrees Of Freedom**: F ~ F(n1 − 1, n2 − 1) with numerator degrees of freedom n1 − 1 and denominator degrees of freedom n2 − 1.
- **Hypotheses And Tail Direction**: H0: σ1^2 = σ2^2; the alternative may be less than, greater than, or not equal, leading to left-, right-, or two-tailed tests.
- **Orientation Of F Ratio**: The ratio may be s1^2/s2^2 or s2^2/s1^2, depending on the alternative hypothesis and which sample variance is larger.
- **Interpretation Of F Magnitude**: F close to one supports equal variances; a much larger F (with the larger sample variance in the numerator) indicates evidence against equality.
- **Sensitivity To Non-Normality**: The test is very sensitive to deviations from normality and can yield unpredictable p-values when distributions are not normal.


---
<!-- Total tokens: 15770 -->
# Section: seg_187 Heading：13.5 lab: one-way anova

- **Analysis Of Variance (ANOVA)**: A method of testing whether the means of three or more populations are equal; applicable when populations are normally distributed, have equal standard deviations, and samples are randomly and independently selected; the test statistic is the F-ratio.
- **One-Way ANOVA**: A method of testing whether the means of three or more populations are equal when there is one independent variable and one dependent variable; applicable under normality, equal standard deviations, and random, independent sampling; the test statistic is the F-ratio.
- **Variance**: The mean of the squared deviations from the mean; the square of the standard deviation; the sample variance equals the sum of squared deviations divided by the sample size minus one.
- **F Distribution**: The distribution used for ANOVA and F tests, characterized by numerator and denominator degrees of freedom; it is always positive and skewed right.
- **F Statistic (F-Ratio)**: The ratio of a measure of variation among group means to a similar measure of variation within groups; used as the test statistic in ANOVA.
- **Assumptions For One-Way ANOVA**: Each population is normal; samples are randomly selected and independent; populations have equal standard deviations (or variances).
- **Hypotheses In One-Way ANOVA**: Null hypothesis states that all group means are equal; alternative hypothesis states that one or more group means differ.
- **Degrees Of Freedom (F Distribution)**: Numerator degrees of freedom equal the number of groups minus one; denominator degrees of freedom equal the number of observations minus the number of groups.
- **Sum Of Squares Between (SSbetween)**: The sum of squares measuring variation among group means (factor/between-groups variation).
- **Sum Of Squares Within (SSwithin)**: The sum of squares measuring variation within groups; equal to total sum of squares minus between-groups sum of squares.
- **Total Sum Of Squares (SStotal)**: The total variation across all observations.
- **Mean Square Between (MSbetween)**: The between-groups sum of squares divided by its degrees of freedom.
- **Mean Square Within (MSwithin)**: The within-groups sum of squares divided by its degrees of freedom.
- **Balanced Data**: Data in which the groups are the same size.
- **Unbalanced Data**: Data in which the group sizes are unequal.
- **Test Of Two Variances**: An F test to determine whether two population variances are equal; uses the F distribution with numerator and denominator degrees of freedom one less than the corresponding sample sizes; assumes normal distributions and independence between populations.
- **Pooled Variance**: The mean of the sample variances.

