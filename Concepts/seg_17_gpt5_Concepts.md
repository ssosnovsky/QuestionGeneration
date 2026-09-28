
---
<!-- Total tokens: 0 -->
# Chapter: seg_17 Heading：chapter 2: descriptive statistics




---
<!-- Total tokens: 6532 -->
# Section: seg_19 Heading：2.1 stem-and-leaf graphs (stemplots), line graphs, and bar graphs

- **Stem-And-Leaf Graph (Stemplot)**: A graph for small data sets that divides each observation into a stem and a leaf (final significant digit), lists stems vertically from smallest to largest, and places leaves in increasing order next to their stems to give an exact picture of the data.
- **Stem**: The portion of each observation in a stemplot that precedes the final significant digit and is listed in a vertical column from smallest to largest.
- **Leaf**: The final significant digit of each observation in a stemplot, written in increasing order next to its corresponding stem.
- **Side-By-Side Stem-And-Leaf Plot**: A comparative stemplot in which two data sets share the same stems, with leaves displayed on both the left and right of the stems.
- **Outlier**: An observation that does not fit the rest of the data, sometimes called an extreme value, appearing not to fit the pattern of the graph.
- **Line Graph**: A graph for specific data values with the x-axis showing data values, the y-axis showing frequency points, and the points connected by line segments.
- **Bar Graph**: A graph consisting of separated bars that can be vertical or horizontal and may be rectangles or rectangular boxes in three-dimensional plots.


---
<!-- Total tokens: 9785 -->
# Section: seg_21 Heading：2.2 histograms, frequency polygons, and time series graphs

- **Histogram**: A graph of contiguous boxes with the horizontal axis labeled by what the data represent and the vertical axis labeled frequency or relative frequency; used to readily display large data sets and show the data’s shape, center, and spread, with the same shape under either y-axis label.
- **Histogram Usage Guideline**: A rule of thumb is to use a histogram when the data set consists of 100 values or more.
- **Frequency**: The number of times an answer occurs.
- **Relative Frequency**: The frequency for an observed value divided by the total number of data values in the sample (RF = f/n).
- **Class Interval (Class)**: The bars or intervals that represent grouped data in a histogram.
- **Class Width**: The width of each bar or class interval computed as (ending value − starting point) divided by the number of bars.
- **Starting Point (Histogram)**: A first class boundary chosen to be less than the smallest data value and carried to one more decimal place than the value with the most decimal places.
- **Class Boundaries Convention**: Carry boundaries to one additional decimal place so no data value falls on a boundary; count a value in a class if it falls on the left boundary but not if it falls on the right boundary.
- **Number Of Classes**: Typically five to 15 bars for clarity; a guideline is to take the square root of the number of data values and round to determine the number of intervals.
- **Continuous Data**: Data obtained by measurement.
- **Discrete Data**: Data obtained by counting.
- **Discrete Data Class Boundaries**: For integer data, subtract 0.5 from the smallest value and add 0.5 to the largest value; choose a width that centers data values within intervals.
- **Frequency Polygon**: A graph analogous to a line graph that makes continuous data easy to interpret, constructed by selecting class intervals, plotting the data points, and connecting them with line segments.
- **Overlay Frequency Polygon**: Comparing distributions by overlaying frequency polygons drawn for different data sets.
- **Time Series Graph**: A graph that recognizes chronological ordering by plotting time on the horizontal axis and measured values on the vertical axis, connecting points in the order they occur to display changes over time.
- **Uses Of A Time Series Graph**: Important for data recorded over time because graphical display makes trends easy to spot.


---
<!-- Total tokens: 8445 -->
# Section: seg_23 Heading：2.3 measures of the location of the data

- **Measures Of Location**: Common measures that describe data position, specifically quartiles and percentiles.
- **Percentiles**: Values that divide ordered data into hundredths; the pth percentile has at most p% of data at or below it.
- **Quartiles**: Special percentiles that divide ordered data into quarters.
- **First Quartile (Q1)**: The 25th percentile; the median of the lower half of ordered data.
- **Median (Second Quartile, 50th Percentile)**: The center of ordered data that splits values into two halves; may not be an observed value.
- **Third Quartile (Q3)**: The 75th percentile; the median of the upper half of ordered data.
- **Interquartile Range (IQR)**: The spread of the middle 50% of data; calculated as Q3 − Q1.
- **Potential Outlier**: A data point notably different from others; suspected if less than Q1 − 1.5(IQR) or greater than Q3 + 1.5(IQR); requires further investigation.
- **Five-Number Summary**: The set of Minimum, Q1, Median, Q3, and Maximum.
- **Kth Percentile Index Formula**: For ordered data of size n, the position i = (k/100)(n + 1); if i is an integer, use the ith value; otherwise average the surrounding values.
- **Percentile Rank Formula**: For a value with x observations below and y equal in a set of size n, percentile = ((x + 0.5y)/n) × 100, rounded to the nearest integer.
- **Interpreting Percentiles**: Percentiles indicate relative standing; low percentiles correspond to lower values and high percentiles to higher values; whether a percentile is “good” or “bad” depends on context.
- **Percentile Interpretation Elements**: Include context, the data value, the percent below the percentile, and the percent above the percentile.


---
<!-- Total tokens: 7768 -->
# Section: seg_25 Heading：2.4 box plots

- **Box Plot (Box-And-Whisker Plot)**: A graphical display constructed from five values that shows the concentration of the data and how far extreme values are from most of the data; the box spans Q1 to Q3 with a median line, and whiskers extend to the minimum and maximum.
- **Five Values For Box Plots**: The minimum value, first quartile, median (second quartile), third quartile, and maximum value used to construct a box plot.
- **Minimum Value**: The smallest data value used as an axis endpoint and whisker limit in a box plot.
- **Maximum Value**: The largest data value used as an axis endpoint and whisker limit in a box plot.
- **First Quartile (Q1)**: The value that marks one end of the box; approximately 25% of the data lie between the minimum and Q1.
- **Median (Q2)**: The second quartile shown inside the box (often as a dashed line) that may lie between or coincide with the first and third quartiles.
- **Third Quartile (Q3)**: The value that marks the other end of the box; approximately 25% of the data lie between Q3 and the maximum.
- **Whiskers**: Line segments extending from the ends of the box to the smallest and largest data values; when outliers are marked with dots, whiskers do not extend to the minimum and maximum.
- **Interquartile Range (IQR)**: The difference Q3 − Q1, representing the spread of the middle 50% of the data.
- **Range**: The difference between the maximum and minimum values.
- **Middle 50%**: The portion of the data between the first and third quartiles that falls inside the box.
- **Scaled Number Line**: A properly scaled horizontal or vertical number line used as the axis to construct a box plot.
- **Tied Values In Box Plots**: A condition where some of the minimum, first quartile, median, third quartile, and maximum are equal, affecting the display (e.g., no separate median line when the median equals the third quartile).
- **Quartile Proportions**: Each quartile contains approximately 25% of the data.


---
<!-- Total tokens: 6554 -->
# Section: seg_27 Heading：2.5 measures of the center of the data

- **Arithmetic Mean (Average)**: Sum of all data values divided by the number of values; commonly used as a measure of center.
- **Sample Mean (X̄)**: Arithmetic mean of a sample, denoted x̄; a good estimate of the population mean when the sample is truly random.
- **Population Mean (Μ)**: Arithmetic mean of an entire population, denoted μ.
- **Mean Calculation Using Frequencies**: Compute the mean by multiplying each distinct value by its frequency, summing these products, and dividing by the total number of data values.
- **Median**: The value that splits ordered data into two equal parts; for odd n it is the middle value, and for even n it is the average of the two middle values; robust to outliers.
- **Median Location Formula**: The position of the median in ordered data is (n + 1) / 2; the location is not the median’s value.
- **Mode**: The most frequent value; multiple modes are allowed if they tie for highest frequency; applicable to qualitative and quantitative data.
- **Bimodal**: A data set that has exactly two modes.
- **Law Of Large Numbers**: As sample size increases, the sample mean x̄ tends to get closer to the population mean μ.
- **Frequency Table**: A representation of grouped data that lists intervals and their corresponding frequencies.
- **Midpoint Of An Interval**: The average of an interval’s lower and upper boundaries, used to represent the interval’s data.
- **Mean Of A Grouped Frequency Table**: Estimated mean computed as Σ(fm) / Σf, where f is interval frequency and m is the interval midpoint.


---
<!-- Total tokens: 5082 -->
# Section: seg_29 Heading：2.6 skewness and the mean, median, and mode

- **Symmetrical Distribution**: A distribution in which a vertical line can be drawn so the left and right shapes are mirror images of each other.
- **Skewed To The Left**: A distribution that is pulled out to the left.
- **Skewed To The Right**: A distribution that is pulled out to the right.
- **Unimodal Distribution**: A distribution with one mode.
- **Bimodal Distribution**: A distribution with two modes.
- **Mean And Median In Perfectly Symmetrical Distribution**: In a perfectly symmetrical distribution, the mean and the median are the same.
- **Modes In Symmetrical Bimodal Distribution**: In a symmetrical distribution with two modes, the two modes are different from the mean and median.
- **Mean Versus Median Sensitivity To Skewness**: The mean and the median both reflect skewing, but the mean reflects it more.
- **Relative Order In Left-Skewed Distribution**: Generally, the mean is less than the median, which is often less than the mode.
- **Relative Order In Right-Skewed Distribution**: Generally, the mode is often less than the median, which is less than the mean.
- **Median And Mean Positions Relative To Mode In Skewed Distributions**: The median is closest to the high point (the mode), while the mean tends to be farther out on the tail.
- **Mean And Median Location In Symmetrical Distribution**: In a symmetrical distribution, the mean and the median are centrally located close to the high point of the distribution.


---
<!-- Total tokens: 9871 -->
# Section: seg_31 Heading：2.7 measures of the spread of the data

- **Standard Deviation**: A number that measures how far data values are from their mean; a numerical measure of overall variation that is always zero or positive.
- **Deviation**: For a value x, the difference from the mean (population: x − μ; sample: x − x̄) used to compute spread.
- **Variance**: The average of the squared deviations (σ² for a population, s² for a sample); the standard deviation is the square root of the variance.
- **Sample Standard Deviation**: The standard deviation calculated from sample data, denoted s, computed with denominator n − 1.
- **Population Standard Deviation**: The standard deviation calculated from an entire population, denoted σ, computed with denominator N.
- **Number Of Standard Deviations (#ofSTDEVs)**: How many standard deviations a value is from the mean; relates to data via value = mean + (#ofSTDEVs)(standard deviation).
- **Z-Score**: The number of standard deviations a value is from its mean; for a sample z = (x − x̄)/s and for a population z = (x − μ)/σ; used to compare values across different data sets.
- **Sampling Variability Of A Statistic**: The extent to which a statistic changes from one sample to another.
- **Standard Error**: A measure of the sampling variability of a statistic.
- **Standard Error Of The Mean**: The standard deviation of the sampling distribution of the mean.
- **Grouped Data Standard Deviation**: An estimated standard deviation for grouped frequency data obtained using interval midpoints because individual data values are unknown.
- **Mean Of A Frequency Table**: The estimated mean for grouped data computed as (Σf m)/(Σf), where f are interval frequencies and m are interval midpoints.
- **Variability**: Describing data in terms of its spread.
- **Chebyshev's Rule**: For any data set, at least 75% of values lie within two standard deviations of the mean, at least 89% within three, and at least 95% within 4.5.
- **Empirical Rule**: For bell-shaped, symmetric distributions, approximately 68% of values lie within one standard deviation of the mean, 95% within two, and more than 99% within three; applies only to such distributions.


---
<!-- Total tokens: 22960 -->
# Section: seg_33 Heading：2.8 descriptive statistics

- **Box Plot**: A graph that gives a quick picture of the middle 50% of the data.
- **First Quartile**: The value that is the median of the lower half of the ordered data set.
- **Frequency**: The number of times a value of the data occurs.
- **Frequency Polygon**: A graph that looks like a line graph but uses intervals to display ranges of large amounts of data.
- **Frequency Table**: A data representation in which grouped data is displayed along with the corresponding frequencies.
- **Histogram**: A graphical representation of a data distribution using contiguous rectangles; x represents data (classes) and y represents frequency or relative frequency.
- **Interquartile Range (IQR)**: The range of the middle 50% of data values, found by subtracting the first quartile (Q1) from the third quartile (Q3).
- **Interval (Class Interval)**: A range of data used when displaying large data sets.
- **Mean**: A measure of central tendency (arithmetic average); sample mean x̄ equals the sum of sample values divided by the sample size, and population mean μ equals the sum of population values divided by the population size.
- **Median**: A value that separates ordered data into halves; half the values are at or below and half are at or above it.
- **Midpoint**: The mean of an interval in a frequency table.
- **Mode**: The value that appears most frequently in a data set.
- **Outlier**: An observation that does not fit the rest of the data.
- **Paired Data Set**: Two data sets with a one-to-one relationship where both sets are the same size and each point in one set matches exactly one point in the other.
- **Percentile**: A number that divides ordered data into hundredths; the median is the 50th percentile, Q1 is the 25th, and Q3 is the 75th.
- **Quartiles**: Numbers that separate data into quarters; the second quartile is the median.
- **Relative Frequency**: The ratio of the frequency of a value to the total number of outcomes.
- **Skewed**: Describes data that is not symmetrical; more spread in lower values indicates left skew, more spread in greater values indicates right skew.
- **Standard Deviation**: The square root of the variance that measures how far data values are from their mean; notation s for sample and σ for population.
- **Variance**: The mean of squared deviations from the mean; for a sample, the sum of squared deviations divided by (n − 1).
- **Stem-And-Leaf Plot**: A plot that displays all individual data values within classes to show the distribution.
- **Line Graph**: A graph used to represent data where a quantity varies over time, useful for identifying trends.
- **Bar Graph**: A chart using horizontal or vertical bars to compare categories; one axis shows categories and the other a discrete value.
- **Time Series Graph**: A graph used to display one variable measured over a period of time.
- **IQR Outlier Rule**: A method to flag potential outliers using Q3 + 1.5(IQR) and Q1 − 1.5(IQR).
- **Sample Standard Deviation**: s = sqrt[∑(x − x̄)² / (n − 1)] (or frequency form), measuring spread for a sample.
- **Population Standard Deviation**: σ = sqrt[∑(x − μ)² / N] (or frequency form), measuring spread for a population.

