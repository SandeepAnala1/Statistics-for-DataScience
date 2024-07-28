## Percentiles

### What is a Percentile?

A percentile is a statistical measure indicating the value below which a given percentage of observations in a data set fall. For instance, the 70th percentile is the value below which 70% of the observations may be found. 

#### Formula for Percentile

The formula to find the percentile rank of a given value is:

\[ P = \frac{N_{r}}{N} \times 100 \]

Where:
- \( P \) = Percentile rank
- \( N_{r} \) = Number of values less than the given value
- \( N \) = Total number of observations

Alternatively, to find the value at a specific percentile rank:

\[ V = \left( \frac{P}{100} \right) \times (N + 1) \]

Where:
- \( V \) = Value at the Pth percentile
- \( P \) = Desired percentile rank
- \( N \) = Total number of observations

#### Example of Percentile

Suppose you have the following data set of test scores: 55, 70, 75, 80, 85, 90, 95. To find the 40th percentile:

1. Order the data from least to greatest: 55, 70, 75, 80, 85, 90, 95.
2. Calculate \( P = \left( \frac{40}{100} \right) \times (7 + 1) = 0.4 \times 8 = 3.2 \).

The 40th percentile lies between the 3rd and 4th values (75 and 80). Interpolating between these values:

\[ 75 + (80 - 75) \times 0.2 = 75 + 5 \times 0.2 = 75 + 1 = 76 \]

So, the 40th percentile is approximately 76.

#### Example of IIT JEE Percentile

The IIT JEE (Joint Entrance Examination) uses percentiles to rank candidates. If a candidate scores higher than 90% of the test takers, their percentile is 90. This means 90% of the candidates scored below them.

For instance, if there are 1,000,000 candidates and a candidate's rank is 100,000, their percentile rank would be:

\[ \text{Percentile} = \left( \frac{1,000,000 - 100,000}{1,000,000} \right) \times 100 = \left( \frac{900,000}{1,000,000} \right) \times 100 = 90 \]

So, the candidate is at the 90th percentile.
