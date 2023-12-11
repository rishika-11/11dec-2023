# Housing data set

# Overview
The code conducts exploratory data analysis on a housing dataset, including data overview, statistics, and handling of categorical variables. It uses pandas for data manipulation, matplotlib for visualization. The code aims to understand and preprocess the dataset for potential modeling, providing insights through summary statistics and visualizations.

# Prerequisites
- Numpy
- Pandas
- Matplotlib

# Explore Data
- df.head()
- df.tail()
- df.shape[0]
- df.shape[1]
- len(df.columns)
- df.columns
- df.info()
- df.dtypes
- df.nunique()
- df.isnull().sum()
- df.isnull().sum().sum()
- df.describe().T

# Code
Using the pandas, numpy, matplotlib, seaborn, and scikit-learn packages, the Python code employs exploratory data analysis (EDA) and data preprocessing on a housing dataset. After the dataset is imported into a pandas DataFrame, information about its number of rows and columns, column names, data types, and summary statistics are obtained, and the first and final few rows are displayed to assess the structure and content of the dataset. In order to investigate and, for the column "mainroad," binary values ('yes' and 'no') are transformed to numeric values (1 and 0). Other categorical categories, such as "guestroom," "basement," and "furnishingstatus," are also examined.In addition, to improve comprehension of the numerical features, the algorithm looks into the existence of null values in the dataset and produces descriptive statistics.Unique value counts are used to investigate the categorical columns in more detail. Lastly, a histogram is made to show the distribution of numerical features visually.
