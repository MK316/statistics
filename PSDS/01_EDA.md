# 1. Exploratory Data Analysis
(Reference: PSDS, pp.2 ~ )

🔳 **Exploring the data:**  

🔳 **Elements of structured data:**  

* Data come from multiple sources (e.g., sensor measurements, events, text, images, videos, etc.)  
* The _Internet of Things (IoT)_ and unstructured data: "...to apply the statistical concepts..., unstructured raw data must be processed and manipulated into a structured form." (p.2)
* Structured data: numeric (continuous / discrete) and categorical (sets of value / Binary / ordinal) data.  
For computational performance.  
To help determine the type of visual display, data analysis, or statical model.  

* Rectangular data (e.g., spreadsheet or database table): two dimensional matrix with rows indicating records (cases) and columns indicating features (variables).
e.g., **dataframe** is the specific format in R and Python.
* Non-rectangular data: e.g., time series, spatial data, graph data structure, etc.  

🔳 **Estimates of location:**   e.g., Mean, Median, Percentile (quantile), Robust, Outlier  
finding typical value for each feature (variable) - an estimate of where most of the data is located (i.e., its central tendency).  

🔳 **Estimates of variability:**  
Location is one dimension in summarizing a feature (variable).  
Variability (dispersion) measures whether the data values are tightly clusterred or spread out.  

| Terms | Definitions |
|---|---|
| Deviation| The difference between the observed values and the estimate of location |
| Variance | The sum of squared deviation from the mean divided by n-1 where n is the number of data values |
| SD | The square root of the variance |
| Range | The difference between the largest and the smallest value in a data set |
| Percentile | The value such that P percent of the values take on this value or less and (100-P) percent take on this value or more |
| Interquartile range (IQR) | The difference between the 75th percentile and the 25th percentile |





