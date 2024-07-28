# Variable Measurement Scales
- 4 types of measured varibles

1) **Nominal:** {Categorical data} -> Eg: Colours, Gender
2) **Ordenal:** Order of the data matters, but value doesn't. -> Eg: Marks vs Rank
3) **Interval:** Order & Value both matters, natural zero is not possible. -> Eg: (70-80,80-90,90-100 F)
4) **Ratio:** Ratio data is a type of variable measurement scale that possesses all the properties of interval data, with the addition of a true zero point. -> Eg: **Height:** A person who is 180 cm tall is twice as tall as a person who is 90 cm tall.

# Frequency Distribution
### Definition
A frequency distribution is a summary of data that shows the number (frequency) of observations within different intervals or categories. It helps in understanding the distribution and pattern of the data.

### Types of Frequency Distribution
1. **Categorical Frequency Distribution**: Used for categorical data where the data is divided into categories (e.g., colors, types of fruits).
2. **Grouped Frequency Distribution**: Used for numerical data divided into intervals or classes (e.g., ages, scores).

### Components
1. **Class Intervals**: These are the range of values in which the data is grouped.
2. **Frequency**: The number of observations in each class interval.
3. **Cumulative Frequency**: The sum of frequencies up to a certain class interval.
4. **Relative Frequency**: The ratio of the frequency of a class interval to the total number of observations.
5. **Class Boundaries**: The actual limits of class intervals.

### Steps to Create a Frequency Distribution
1. **Determine the Range**: Subtract the smallest value from the largest value.
2. **Decide the Number of Classes**: Use Sturges' formula (\( k = 1 + 3.322 \log N \)), where \( N \) is the number of observations.
3. **Determine Class Width**: Divide the range by the number of classes.
4. **Set Class Intervals**: Create intervals using the class width.
5. **Tally the Frequencies**: Count the number of observations in each interval.

### Example

Consider the following dataset representing the scores of 20 students in a test:
```
45, 67, 52, 59, 61, 73, 55, 68, 47, 72, 51, 66, 64, 58, 60, 71, 69, 62, 57, 74
```

1. **Determine the Range**:
   - Largest value: 74
   - Smallest value: 45
   - Range = 74 - 45 = 29

2. **Decide the Number of Classes**:
   - Using Sturges' formula: \( k = 1 + 3.322 \log 20 \approx 6 \)

3. **Determine Class Width**:
   - Class Width = Range / Number of Classes = 29 / 6 ≈ 5

4. **Set Class Intervals**:
   - 45-49, 50-54, 55-59, 60-64, 65-69, 70-74

5. **Tally the Frequencies**:

| Class Interval | Frequency |
|----------------|-----------|
| 45 - 49        | 2         |
| 50 - 54        | 2         |
| 55 - 59        | 4         |
| 60 - 64        | 5         |
| 65 - 69        | 4         |
| 70 - 74        | 3         |

#### Cumulative Frequency
| Class Interval | Frequency | Cumulative Frequency |
|----------------|-----------|----------------------|
| 45 - 49        | 2         | 2                    |
| 50 - 54        | 2         | 4                    |
| 55 - 59        | 4         | 8                    |
| 60 - 64        | 5         | 13                   |
| 65 - 69        | 4         | 17                   |
| 70 - 74        | 3         | 20                   |

#### Relative Frequency
| Class Interval | Frequency | Relative Frequency |
|----------------|-----------|--------------------|
| 45 - 49        | 2         | 0.10               |
| 50 - 54        | 2         | 0.10               |
| 55 - 59        | 4         | 0.20               |
| 60 - 64        | 5         | 0.25               |
| 65 - 69        | 4         | 0.20               |
| 70 - 74        | 3         | 0.15               |

### Visualization
A histogram or bar chart can be used to visualize the frequency distribution, with class intervals on the x-axis and frequencies on the y-axis.

# Charts
### Bar chart
Used for discrete data
A bar chart is a graphical representation of data using rectangular bars, where the length or height of each bar is proportional to the value it represents. The bars can be plotted vertically or horizontally and are used to compare different categories or groups. Bar charts are useful for visualizing categorical data and highlighting differences in frequency or magnitude.
![image](https://github.com/user-attachments/assets/6afe06cd-680f-4c4b-ae3c-a097d249e717)


### Histogram
Used for continous data
A histogram is a graphical representation of numerical data using adjacent rectangular bars to show the frequency distribution of a dataset. The bars represent intervals (bins) of data, with the height of each bar indicating the number of observations within that interval. Histograms are useful for visualizing the shape, spread, and central tendency of continuous data.

![image](https://github.com/user-attachments/assets/14a7abf4-62c4-4f4a-a768-0d419948d721)

#### PDF: Smoothing of Histograms

![image](https://github.com/user-attachments/assets/25796940-4f9f-475e-9dbf-f7029079eef0)










