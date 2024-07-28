# Measure of Dispersion: Variance and Standard Deviation

Dispersion refers to the spread of data points in a dataset. It provides insights into the variability and distribution of the data. Two key measures of dispersion are variance and standard deviation.

## 1. Variance

Variance measures how far each data point in a set is from the mean and thus from every other data point. It provides a sense of how much the data varies.

### Formula

**Population Variance (\(\sigma^2\)):**
\[ \sigma^2 = \frac{\sum_{i=1}^{N} (x_i - \mu)^2}{N} \]

**Sample Variance (\(s^2\)):**
\[ s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n - 1} \]

Where:
- \( N \) = Number of data points in the population
- \( n \) = Number of data points in the sample
- \( x_i \) = Each individual data point
- \( \mu \) = Mean of the population
- \( \bar{x} \) = Mean of the sample

### Explanation with Examples

#### Population Variance

Consider a population dataset: \( [2, 4, 4, 4, 5, 5, 7, 9] \)

1. Calculate the mean (\(\mu\)):
\[ \mu = \frac{2 + 4 + 4 + 4 + 5 + 5 + 7 + 9}{8} = 5 \]

2. Subtract the mean from each data point and square the result:
\[ (2-5)^2, (4-5)^2, (4-5)^2, (4-5)^2, (5-5)^2, (5-5)^2, (7-5)^2, (9-5)^2 \]
\[ 9, 1, 1, 1, 0, 0, 4, 16 \]

3. Sum these squared differences:
\[ 9 + 1 + 1 + 1 + 0 + 0 + 4 + 16 = 32 \]

4. Divide by the number of data points (N):
\[ \sigma^2 = \frac{32}{8} = 4 \]

#### Sample Variance

Consider a sample dataset: \( [2, 4, 4, 4, 5, 5, 7, 9] \)

1. Calculate the mean (\(\bar{x}\)):
\[ \bar{x} = \frac{2 + 4 + 4 + 4 + 5 + 5 + 7 + 9}{8} = 5 \]

2. Subtract the mean from each data point and square the result:
\[ (2-5)^2, (4-5)^2, (4-5)^2, (4-5)^2, (5-5)^2, (5-5)^2, (7-5)^2, (9-5)^2 \]
\[ 9, 1, 1, 1, 0, 0, 4, 16 \]

3. Sum these squared differences:
\[ 9 + 1 + 1 + 1 + 0 + 0 + 4 + 16 = 32 \]

4. Divide by the number of data points minus one (n-1):
\[ s^2 = \frac{32}{7} \approx 4.57 \]

### Graphs
Variance is often represented in graphical form to illustrate how data points deviate from the mean. Here's a conceptual graph:

![image](https://github.com/user-attachments/assets/5014a44e-224b-45ef-ba92-c4b27d6ed545)

- The horizontal axis represents the data points.
- The vertical axis represents the deviation from the mean.
- The squares of the deviations are shown as squares on the graph.

## 2. Standard Deviation

Standard deviation is the square root of the variance. It provides a measure of dispersion in the same units as the original data, making it more interpretable.

### Formula

**Population Standard Deviation (\(\sigma\)):**
\[ \sigma = \sqrt{\sigma^2} \]

**Sample Standard Deviation (\(s\)):**
\[ s = \sqrt{s^2} \]

### Why Standard Deviation?

Standard deviation is widely used because:
- It provides a measure of dispersion in the same units as the data.
- It is useful in determining how spread out the data points are around the mean.
- It is used to understand the probability distributions, particularly in the context of the normal distribution.

### Bell Curve (Normal Distribution)

The bell curve, or normal distribution, is a probability distribution that is symmetric about the mean. Most of the data points fall close to the mean, with fewer data points as you move further away.

![image](https://github.com/user-attachments/assets/9866fbc0-52cf-476d-9442-f976581f5e6f)


Key features:
- The mean, median, and mode are all equal.
- About 68% of the data falls within one standard deviation of the mean.
- About 95% of the data falls within two standard deviations of the mean.
- About 99.7% of the data falls within three standard deviations of the mean.

Standard deviation is crucial in understanding the spread of data in a normal distribution and is often used in statistical analyses to infer probabilities and make predictions.
