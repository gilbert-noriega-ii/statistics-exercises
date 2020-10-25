# Statistics Repository

## Goals

- Build on top of the statistics knowledge from the khan academy prework
- Understand how to use the uniform, binomial, poisson, and normal distributions to model real-world scenarios
- Understand in general how hypothesis testing is performed
- Know when to use a t-test, correlation test, and χ2 test
- Write python code that simulates experiments in order to calculate an experimental probability
- Use various statistical distributions in python through scipy.stats
- Perform hypothesis testing in python code

## Vocabulary

- **mean:** the average value, i.e. the sum of all the values divided by the number of values. *The mean can be subject to influence by large outlier points.*
- **expected value:** similar to the average, except that each value is weighted by its probability
- **median:** The center, or middle value. When there are an even number of data points, the average of the two middle points.
- **mode:** the most frequently occuring value
    - **bi-modal:** when two values tie for the mode
- **Min:** smallest value
- **Max:** largest value
- **Range:** The difference between the max and the min
- **Quantile:** The cut points that divide a probability distribution into equally sized continuous intervals. To divide our distribution into n equally sized intervals, there are n-1 quantiles.
- **Quartile:** The cut points on a distrubtion to subdivide it into 4 equally sized intervals are called the quartiles. To create 4 equally sized quarters, we need 3 "cut points" called quartiles. The quartiles are commonly abbreviated as Q1, Q2, and Q3.
- **Percentile:** A quantile cut into 100 equally sized intervals. The percentile can be interpreted as the point where a percentage of values fall below it.
- **IQR:** The Interquartile Range, Q3-Q1 (75th percentile - 25th percentile)
- **Variance:** The average squared distance between each point and the mean.
- **Standard Deviation:** The square root of the variance
- **Skew**
    - **Left-skewed:** A set of data values in which the mean is generally less than the median. The left tail of the distribution is longer than the right tail of the distribution.
    - **Right-skewed:** A set of data values in which the mean is generally greater than the median. The right tail of the distribution is longer than the left tail of the distribution.