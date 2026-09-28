
---
<!-- Total tokens: 0 -->
# Chapter: seg_157 Heading：chapter 12: linear regression and correlation




---
<!-- Total tokens: 3053 -->
# Section: seg_159 Heading：12.1 linear equations

- **Linear Equation**: An equation with one independent variable of the form y = a + bx, where a and b are constants.
- **Independent Variable**: The variable x in y = a + bx for which a value is chosen to solve the equation.
- **Dependent Variable**: The variable y in y = a + bx that is solved for after choosing a value of x.
- **Graph Of A Linear Equation**: The graph of y = a + bx is a straight line, and any non-vertical line can be represented by this equation.
- **Slope**: For y = a + bx, b; a number that describes the steepness of the line.
- **Y-Intercept**: For y = a + bx, a; the y-coordinate of the point (0, a) where the line crosses the y-axis.
- **Slope Sign Interpretation**: If b > 0 the line slopes upward to the right; if b = 0 the line is horizontal; if b < 0 the line slopes downward to the right.


---
<!-- Total tokens: 4248 -->
# Section: seg_161 Heading：12.2 scatter plots

- **Scatter Plot**: A way to display the relationship between two variables x and y.
- **Direction Of A Relationship**: Indicates whether high values of one variable occur with high (or low) values of the other; a clear direction is high-high/low-low or high-low.
- **Strength Of A Relationship**: Determined by how close the points are to a line or other function; for a linear relationship, stronger when points are close to a straight line.
- **Horizontal Line Indicates No Relationship**: A scatter plot where all points fall on a horizontal line shows no relationship, despite a perfect fit.
- **Overall Pattern And Deviations**: When examining a scatter plot, focus on the overall pattern and any deviations from that pattern.
- **Linear Relationship**: A relationship in which scatter plot points follow an approximate straight-line pattern; strong when points are close to the line, except for horizontal lines.
- **Linear Regression**: The process used to calculate the line for a scatter plot when the points show a linear relationship.
- **Regression Line**: A line calculated from a scatter plot, used to predict y for a given value of x when one variable helps to explain or predict the other.
- **Condition For Using A Regression Line**: Only calculate a regression line if one variable helps to explain or predict the other variable.


---
<!-- Total tokens: 7753 -->
# Section: seg_163 Heading：12.3 the regression equation

- **Line Of Best Fit (Least-Squares Regression Line)**: The straight line that best fits the data by minimizing the sum of squared residuals; used for prediction when a linear pattern is reasonable.
- **Regression Equation**: The equation of the best-fit line, ŷ = a + bx, where a is the y-intercept and b is the slope.
- **Predicted Value (Ŷ)**: The estimated value of y obtained from the regression line for a given x; generally not equal to the observed y.
- **Residual (Error)**: ε = y − ŷ; the vertical distance between an observed y and its predicted value, positive if the point is above the line and negative if below.
- **Sum Of Squared Errors (SSE)**: The sum of squared residuals, Σε²; the quantity minimized to determine the least-squares regression line.
- **Least Squares Criterion**: The best-fit line is the one that minimizes the SSE among all possible lines.
- **Slope (b)**: The average change in y for a one-unit increase in x; computed as b = Σ(x − x̄)(y − ȳ)/Σ(x − x̄)² and equivalently b = r(sy/sx).
- **Y-Intercept (a)**: The value where the regression line crosses the y-axis; computed as a = ȳ − b x̄.
- **Linear Regression**: The process of fitting the least-squares best-fit line under the assumption that data are scattered about a straight line.
- **Correlation Coefficient (r)**: A numerical measure of the strength and direction of the linear association between x and y, ranging from −1 to +1; its sign matches the slope.
- **Coefficient Of Determination (r²)**: The square of r; the proportion (often as a percent) of variation in y explained by variation in x using the regression line; 1 − r² is the unexplained proportion.
- **Best-Fit Line Passes Through (X̄, Ȳ)**: The least-squares regression line always passes through the point (x̄, ȳ).
- **Correlation Does Not Imply Causation**: Strong correlation does not indicate a causal relationship between x and y.
- **Independent And Dependent Variables**: x is the independent (explanatory) variable used to predict; y is the dependent (predicted) variable.
- **Prediction Within Sample Domain**: Use the regression line for x-values within the domain of the sample data; predictions outside that domain are not necessarily appropriate.


---
<!-- Total tokens: 7460 -->
# Section: seg_165 Heading：12.4 testing the significance of the correlation coefficient

- **Correlation Coefficient (r)**: Sample statistic measuring the strength and direction of the linear relationship between x and y; calculated from sample data and used to estimate ρ.
- **Population Correlation Coefficient (ρ)**: Unknown population parameter describing the linear association; target of the hypothesis test for being zero or not.
- **Significance Test For Correlation Coefficient**: Procedure using r and n to decide whether ρ is significantly different from zero.
- **Null Hypothesis (H0: ρ = 0)**: States that the population correlation is not significantly different from zero; no significant linear relationship exists.
- **Alternative Hypothesis (Ha: ρ ≠ 0)**: States that the population correlation is significantly different from zero; a significant linear relationship exists.
- **Significance Level (α)**: Threshold probability (e.g., 0.05) used to make the reject/do-not-reject decision via p-values or critical values.
- **P-Value Method**: Decision rule that rejects H0 when the p-value from a t-distribution with n − 2 degrees of freedom is less than α.
- **Critical Values Method**: Decision rule that deems r significant when r lies outside the interval between the negative and positive critical values for df = n − 2 at α = 0.05.
- **Test Statistic (t) For Correlation**: t = r√(n − 2) / √(1 − r²); has the same sign as r and follows a t-distribution with n − 2 degrees of freedom.
- **Degrees Of Freedom**: n − 2, used for the t-distribution and selection of critical values in the test.
- **Significant Correlation Coefficient**: Result where r is significantly different from zero; conclude a significant linear relationship and that the regression line can be used to model and predict within the observed x-domain.
- **Not Significant Correlation Coefficient**: Result where r is not significantly different from zero; conclude no significant linear relationship and avoid using the regression line for modeling or prediction.
- **Conditions For Using The Regression Line For Prediction**: Use when r is significant and the scatter plot shows a linear trend; do not extrapolate beyond the observed x-domain; avoid use if r is not significant or the plot is non-linear.
- **Linearity In The Population**: The expected value of y for each x lies on a straight line in the population.
- **Normality Of Y About The Line**: For each x, y values are normally distributed about the line, with means on the line.
- **Equal Standard Deviations**: The standard deviations of y about the line are equal for all x (homoscedasticity).
- **Independence Of Residuals**: Residual errors are mutually independent.
- **Random Sampling Or Randomized Experiment**: Data arise from a well-designed random sample or randomized experiment.


---
<!-- Total tokens: 5092 -->
# Section: seg_167 Heading：12.5 prediction

- **Prediction Using Least-Squares Regression**: Using the least-squares regression line to estimate the mean value of y for a specified x by substituting the x-value into the equation when x lies within the observed x range.
- **Least-Squares Regression Line**: The best-fit line for the data used to predict y from x.
- **Domain Of Observed X Values**: The range of x-values observed in the data (independent variable).
- **Interpolation**: Predicting inside of the observed x values in the data.
- **Extrapolation**: Predicting outside of the observed x values in the data.


---
<!-- Total tokens: 7792 -->
# Section: seg_169 Heading：12.6 outliers

- **Outliers**: Observed data points that are far from the least squares line, characterized by large residuals, and requiring careful evaluation before inclusion or exclusion.
- **Residual (Error)**: The vertical distance from a data point to the line of best fit, computed as observed y minus predicted y (y − ŷ).
- **Influential Points**: Data points far from others in the horizontal (x) direction that can substantially affect the slope of the regression line; initially identified by removing them and checking for significant slope changes.
- **Standard Deviation Of Residuals (s)**: The standard deviation of the residuals used to set thresholds for outlier detection; calculated from SSE with n − 2 degrees of freedom.
- **Sum Of Squared Errors (SSE)**: The sum of the squared residuals, used to compute the standard deviation of residuals.
- **Two-Standard-Deviation Rule For Outliers**: A guideline that flags any point with a residual magnitude greater than 2s as a potential outlier.
- **Graphical Identification Of Outliers**: A method that draws lines parallel to the best-fit line at ±2s; points outside these lines are flagged as potential outliers.
- **Numerical Identification Of Outliers**: A method that calculates each residual and compares it to ±2s to flag potential outliers.
- **Handling Outliers**: The process of examining causes, correcting erroneous values or deleting them if necessary, retaining informative outliers, and documenting any deletions or reporting results with and without the removed data.


---
<!-- Total tokens: 5343 -->
# Section: seg_171 Heading：12.7 regression (distance from school)

- **Line Of Best Fit**: The line calculated and constructed between two variables.
- **Significant Relationship**: Determining whether the relationship between two variables is significant.
- **Bivariate Data**: Paired data on distance an individual lives from school and the cost of supplies for the current term.
- **Linear Equation**: The equation ŷ = ____ written from the data and rounded to four decimal places.
- **Correlation**: A calculated value evaluated for significance to assess the relationship between the variables.
- **Regression Line**: The line sketched on the graph obtained from the calculator or computer based on the data.
- **Outlier**: A data point identified as an outlier in the set and considered for possible removal.
- **Sample**: Eight members of the class used for the analysis.
- **Dependent Variable**: The variable designated as dependent when analyzing distance versus cost.
- **Independent Variable**: The variable designated as independent when analyzing distance versus cost.


---
<!-- Total tokens: 5235 -->
# Section: seg_173 Heading：12.8 regression (textbook cost)

- **Bivariate Data**: Paired data collected for two variables.
- **Independent Variable**: The variable used to make predictions about the other in the analysis.
- **Dependent Variable**: The variable to be predicted in the analysis.
- **Line Of Best Fit**: The linear equation between two variables constructed from the data.
- **Linear Equation**: The equation y = ____ written from the data and rounded to four decimal places.
- **Coefficient A**: A calculated parameter in the linear equation.
- **Coefficient B**: A calculated parameter in the linear equation.
- **Correlation**: A calculated value that indicates the relationship between the two variables.
- **Significance Of Correlation**: The determination of whether the correlation is significant.
- **Prediction**: Using the analysis to estimate a variable’s value for a specified case.
- **Regression Line**: The graphed line representing the linear equation for the data.
- **Line Fit**: An evaluation of whether the line seems to fit the data.
- **Outlier**: A data point identified as an outlier in the set.
- **Sample Size (n)**: The number of data pairs collected and used in the analysis.


---
<!-- Total tokens: 18906 -->
# Section: seg_175 Heading：12.9 regression (fuel efficiency)

- **Linear Equation**: An algebraic relationship typically written as y = mx + b (algebraic) or y = a + bx (statistical), relating an independent variable x and a dependent variable y.
- **Independent Variable**: The variable x that is used to predict or explain changes in the dependent variable.
- **Dependent Variable**: The variable y whose values depend on the independent variable x.
- **Slope**: The coefficient b in y = a + bx that represents the rate of change in y for a one-unit increase in x.
- **Y-Intercept**: The constant a in y = a + bx; the value of y when x = 0 and the point where the line crosses the y-axis.
- **Scatter Plot**: A graph used to assess the direction and strength of the relationship between x and y and evaluate linearity.
- **Regression Line (Line Of Best Fit)**: A line drawn on a scatter plot to model the relationship and make predictions between x and y.
- **Least-Squares Regression Line**: The regression line that minimizes the Sum of Squared Errors, providing a uniform best fit.
- **Residuals**: The differences between observed y values and the corresponding estimated y values from the regression line.
- **Sum Of Squared Errors**: The sum of squared residuals; its minimum identifies the least-squares regression line.
- **Coefficient Of Correlation**: Pearson’s r, a measure of the strength and direction of linear association between x and y, bounded between −1 and +1.
- **Coefficient Of Determination**: r², the proportion (often expressed as a percent) of variation in y explained by x via the regression line.
- **Conditions For Regression**: Assumptions for linear regression validity—Linear, Independent residuals, Normal y-values for each x, Equal variance, and Random data production.
- **Standard Deviation Of Residuals**: The statistic s used to estimate the population standard deviation of y based on the residuals.
- **Population Correlation Coefficient**: ρ (rho), the parameter representing the linear association in the population.
- **Significance Testing Of Correlation Coefficient**: A linear regression t-test of H0: ρ = hypothesized value (commonly 0) to assess whether a linear relationship exists in the population.
- **Prediction Using Regression**: Using the least-squares regression line to predict y after establishing a strong correlation.
- **Outlier**: An observation that does not fit the pattern of the rest of the data.
- **Extrapolation**: Making predictions for x-values outside the observed data range using the regression line, which should be avoided.

