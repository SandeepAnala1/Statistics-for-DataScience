## Notes on Central Tendency

Central tendency refers to the measure used to determine the center of the distribution of the data. The three primary measures of central tendency are Mean, Median, and Mode.

### Mean (Average)

The mean is the sum of all the values in a dataset divided by the number of values.

#### Formula for Population Mean (\(\mu\)):
\[
\mu = \frac{\sum_{i=1}^N X_i}{N}
\]
- \(\mu\) = Population mean
- \(N\) = Number of values in the population
- \(X_i\) = Each individual value in the population

#### Formula for Sample Mean (\(\bar{x}\)):
\[
\bar{x} = \frac{\sum_{i=1}^n X_i}{n}
\]
- \(\bar{x}\) = Sample mean
- \(n\) = Number of values in the sample
- \(X_i\) = Each individual value in the sample

#### Example:
Given a sample of exam scores: 70, 75, 80, 85, 90

Sample mean (\(\bar{x}\)):
\[
\bar{x} = \frac{70 + 75 + 80 + 85 + 90}{5} = \frac{400}{5} = 80
\]

### Median

The median is the middle value of a dataset when the values are arranged in ascending or descending order. It is less affected by outliers and skewed data compared to the mean.

#### Why Median?
When outliers are added into data, they have a significant impact on the mean but a minimal impact on the median. The median provides a better central value for skewed distributions.

#### Steps to Calculate Median:
1. **Sort the numbers**: Arrange the data in ascending order.
2. **Pick the central element**:
   - For an odd number of observations: The median is the middle element.
   - For an even number of observations: The median is the average of the two middle elements.

#### Formula:
- **Odd number of observations**:
  \[
  \text{Median} = X_{\left(\frac{n+1}{2}\right)}
  \]
  Where \(X\) is the sorted data and \(n\) is the number of observations.
  
- **Even number of observations**:
  \[
  \text{Median} = \frac{X_{\left(\frac{n}{2}\right)} + X_{\left(\frac{n}{2} + 1\right)}}{2}
  \]

#### Example:
Given the dataset: 70, 75, 80, 85, 90
- Sorted data: 70, 75, 80, 85, 90
- Number of observations (\(n\)) = 5 (odd)
  \[
  \text{Median} = X_{\left(\frac{5+1}{2}\right)} = X_3 = 80
  \]

Given the dataset: 70, 75, 80, 85, 90, 95
- Sorted data: 70, 75, 80, 85, 90, 95
- Number of observations (\(n\)) = 6 (even)
  \[
  \text{Median} = \frac{X_{\left(\frac{6}{2}\right)} + X_{\left(\frac{6}{2} + 1\right)}}{2} = \frac{X_3 + X_4}{2} = \frac{80 + 85}{2} = 82.5
  \]

### Mode

The mode is the value that appears most frequently in a dataset. A dataset may have one mode, more than one mode, or no mode at all.

#### Where Mode is Used:
- **Categorical data**: The mode is often used for categorical data where we want to know the most common category.
- **Bimodal or multimodal distributions**: It is useful for identifying the peaks in such distributions.
- **Retail and marketing**: Understanding the most popular product size, color, etc.

#### Example:
Given the dataset: 70, 75, 80, 75, 90
- The mode is 75, as it appears most frequently in the dataset.
