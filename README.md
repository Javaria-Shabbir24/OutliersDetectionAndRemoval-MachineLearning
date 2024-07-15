# Outlier Detection and Removal

This repository covers outlier detection using box plots and distribution plots,  and removal techniques using the Interquartile Range (IQR) and Z-score methods.


## Introduction
Outliers are data points that differ significantly from other observations. Detecting and handling outliers is crucial for improving the accuracy of statistical analyses and machine learning models. This repository includes two popular methods for detecting outliers: 

- Box plots
- Distribution plots

 and two techniques for removing outliers:
- Interquartile Range (IQR)
- Z-score methods.

## Box Plot
A box plot (or box-and-whisker plot) is a standardized way of displaying the distribution of data based on a five-number summary: 
- minimum
- first quartile (Q1)
- median
- third quartile (Q3)
- maximum.
Outliers can be detected as points that fall outside the "whiskers" of the plot.

## Distribution Plot
A distribution plot shows the distribution of data points across different values. Outliers can be identified as data points that fall far away from the majority of the data.

## Interquartile Range (IQR) Method
The IQR method involves calculating the range between the first quartile (Q1) and the third quartile (Q3). Outliers are typically defined as data points that fall below Q1 - 1.5 * IQR or above Q3 + 1.5 * IQR.

## Z-score Method
The Z-score method involves calculating the Z-score for each data point, which measures how many standard deviations a point is from the mean. Data points with a Z-score greater than a threshold (typically 3 or -3) are considered outliers.

## Conclusion
Proper detection and removal of outliers ensure that the data used for analysis or modeling is clean and reliable.
