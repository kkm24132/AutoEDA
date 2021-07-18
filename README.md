# AutoEDA (Automated Exploratory Data Analysis)

## 1. Objective

To provide what is AutoEDA, what is the need, why it is used in Data Science projects and what are the libraries / packages that we can leverage from programming language such as Python to help facilitate data exploration and data analysis efforts in any project.

![AutoEDA](https://github.com/kkm24132/AutoEDA/blob/main/images/AutoEDA.png)

## 2. What is AutoEDA

Any Data Science project/program follows the CRISP-DM methodology. Data Understanding and Data Preparation phases involve EDA (Exploratory Data Analysis) and this is where we perform data exploration.

Why do we need EDA:
-	Extracting key variables and leaving behind not-so-important variables
-	Identifying various aspects such as outliers, missing values, or any human error in the dataset
-	Understanding the relationship between variables that are present or not present
-	Maximizing our insights of a dataset and minimizing potential error that may occur later in the process by ensuring understanding of data pattern better

How AutoEDA comes into play:
- We leverage some of the existing packages to **save time** in our analysis efforts
- There is need to analyze lots of messy and large datasets at initial phases in DS program for "Data Understanding". This is where AutoEDA helps **quick insight generation**
- **Feature wise comparision** of understanding data patterns and uncovering hidden insights which is a key step before we perform any "Data Preparation" / "Feature Engineering" step prior to Model development



## 3. AutoEDA Options with Features

Some of the key AutoEDA in Python are as follows:

Package / Library Name | Features                            | URL Reference(s)         |
-----------------------|-------------------------------------|--------------------------|
Pandas Profiling       | Type inference, Quantile and Descriptive Stats, Most frequent values, Histogram, Correlations, Missing Values, Text analysis, Image analysis |<ul> <li> https://pypi.org/project/pandas-profiling/ </li> <li> https://pandas-profiling.github.io/pandas-profiling/docs/master/rtd/ </li> |
SweetViz               | Target Analysis, Visualize and Compare, Mixed-Type Associations, Type Inference, Summary Information |<ul> <li> https://pypi.org/project/sweetviz/ </li> |
AutoViz                | Scatter Plots, Pair-wise Scatter Plots, Histograms (KDE Plots), Violin Plot, Heatmap, Bar Plots  | <ul> <li> https://github.com/AutoViML/AutoViz </li>|
LUX                    | Correlation, Distribution, Occurrence, Geographical analysis, Current visualization and comparision with Enhance/Filter/Generalize approach | <ul> <li> https://pypi.org/project/lux-api/ </li>|
DataPrep               | Distributions, Correlations, Missing Values analysis, Profile Report with various stats, Time series data analysis, Faster than others like Pandas Profiling due to Dask based computing module |<ul> <li> https://pypi.org/project/dataprep/ </li> |
D Tale                 | Combination of Flask back-end and React front-end to view and analyze Pandas data structures, Integrates with IPython notebooks, supports interactive plots, 3d plots, heat maps, the correlation between features, builds custom columns etc. | <ul> <li> https://pypi.org/project/dtale/ </li>|

**P.S: This is non-exhaustive list**

## 4. Notebooks / Kernels

Sample Notebooks are kept [here](https://github.com/kkm24132/AutoEDA/tree/main/notebooks)


## 5. Interpretation Summary

- [X] If we want to get quick insights on statistical inferences, missing values, duplicates, categorical/numerical/text features, correlations, interactions, top and bottom 10 rows, comparision between train and test datasets, then we can leverage some of these AutoEDA libraries and their capabilities.
- [X] This helps in saving time significantly as we quickly generate some statistical inferences, insights as part of these reports / outcomes.
- [X] If the dataset is large, we may use "DataPrep" which seems to be 10X faster than Pandas Profiling as it uses Dask based computing methods.
- [X] We have used one sample dataset (Loan Eligible / Loan Prediction dataset) for the analysis to demonstrate features of various techniques. These can be used based on scenarios, data context, business need, feasibility etc. These are non-exhaustive list.
- [X] DTale shows most exhaustive amongst these as it provides user detailed analysis, "Code Expert" is one of the unique feature that it provides. Additionally, it follows 3 key features "Action"-"Visualize"-"Highlight".
  

