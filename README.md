# Zomato-EDA-and-Feature-Engineering

# Feature Engineering – How to Detect and Remove Outliers (with Python Code)
How to detect outliers?
👉 For Normal distributions: Use empirical relations of Normal distribution.

– The data points which fall below mean-3*(sigma) or above mean+3*(sigma) are outliers.

where mean and sigma are the average value and standard deviation of a particular column.

![image](https://user-images.githubusercontent.com/108605935/207641597-1dbbf8ef-d517-4dd2-94c5-5861e21ff85a.png)

👉 For Skewed distributions: Use Inter-Quartile Range (IQR) proximity rule.

– The data points which fall below Q1 – 1.5 IQR or above Q3 + 1.5 IQR are outliers.

where Q1 and Q3 are the 25th and 75th percentile of the dataset respectively, and IQR represents the inter-quartile range and given by Q3 – Q1.

### Techniques for outlier detection and removal:
* PDF -> feature-engineering-how-to-detect-and-remove-outliers-with-python-code
* Web link -> https://www.analyticsvidhya.com/blog/2021/05/feature-engineering-how-to-detect-and-remove-outliers-with-python-code/


# What is a Box Plot?
 Display variation in a set of data.

![image](https://user-images.githubusercontent.com/108605935/207808262-e84a6482-aaf3-4895-8a36-68e22ab2073c.png)

* Minimum – The minimum value in the data set
* First quartile – The value below which the lower 25% of the data exist
* Median – the value below which the lower 50% of the data exist
* Third quartile – the value below which the lower 75% of the data exist
* Maximum – the maximum value in the data set
 
