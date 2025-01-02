Data Exploration and Analysis with Jupyter Notebooks
This project is focused on performing an Exploratory Data Analysis (EDA) on a customer dataset using Python. We will walk through various tasks such as data exploration, univariate and bivariate analysis, handling missing values, and calculating correlations using libraries like Pandas, Numpy, Seaborn, and Matplotlib.

**Task 1: Initial Data Exploration**
In this task, we familiarize ourselves with the dataset and perform initial explorations.

Libraries Used: Pandas, Numpy, Seaborn, Matplotlib
Objective:
Load the dataset into a Pandas DataFrame.
Get an overview of the first few rows using .head().
Calculate summary statistics for the numeric columns using Pandas .describe() method.

**Task 2: Univariate Analysis**
We conduct univariate analysis to explore the distribution and summary statistics of individual variables.

Libraries Used: Seaborn, Numpy, Pandas
Objective:
Visualize the distribution of customer ratings using Seaborn.
Overlay key statistics like mean, 25th, and 75th percentiles on the distribution using Numpy.
Plot histograms for all numeric columns using Pandas .hist().
Examine the frequency distribution of categorical variables ('Branch', 'Payment') using Seaborn's .countplot().

**Task 3: Bivariate Analysis**
This task explores the relationship between pairs of variables.

Libraries Used: Seaborn, Matplotlib
Objective:
Create scatterplots and regression plots to examine the relationship between customer rating and gross income.
Plot a boxplot to compare aggregate sales across the different supermarket branches.
Use a boxplot to compare sales patterns between male and female customers.
Visualize trends over time by plotting a time series graph for gross income over a three-month period.

**Task 4: Dealing with Duplicate Rows and Missing Values**
In this task, we handle common data issues such as duplicates and missing values.

Libraries Used: Pandas, Pandas Profiling
Objective:
Identify duplicate rows in the dataset and remove them using drop_duplicates().
Address missing values by replacing them with the mean of the respective columns using Pandas.
Use Pandas Profiling to automate some of the data exploration and see detailed reports on missing values and duplicates.

**Task 5: Correlation Analysis**
In this task, we examine the relationships between numeric variables.

Libraries Used: Numpy, Pandas, Seaborn
Objective:
Use Numpy to calculate correlations between numeric variables.
Generate a correlation matrix using Pandas and plot it as a heatmap using Seaborn to visualize pairwise correlations.
