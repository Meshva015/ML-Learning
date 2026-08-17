# 1. Introduction

Before building a Machine Learning model, it is necessary to understand the dataset. EDA helps us examine the structure, characteristics, distribution, patterns, and relationships present in the data.

EDA uses both statistical methods and data visualization techniques to explore a dataset.

The main purpose is to understand the data before applying further analysis, preprocessing, or Machine Learning algorithms.

# 2. What is EDA?

Exploratory Data Analysis (EDA) is the process of examining, summarizing, and visualizing a dataset to understand its main characteristics.

During EDA, we explore questions such as:

- How many rows and columns are present?
- What are the names of the columns?
- What type of data does each column contain?
- Are there missing values?
- Are there duplicate records?
- How is the numerical data distributed?
- Are there any outliers?
- How are categorical variables distributed?
- Are there relationships between variables?
- Are some variables strongly correlated?

EDA helps us discover useful patterns, unusual observations, and possible data quality problems.

### Simple Example

Suppose we have an employee dataset containing:

- Age
- Gender
- Salary
- Experience
- City

Using EDA, we can find:

- Average employee age
- Salary distribution
- Number of employees from each city
- Relationship between experience and salary
- Missing values
- Duplicate records
- Possible salary outliers

In simple words:

> EDA means understanding the data before using the data.

# 4. Objectives of EDA

The main objectives of Exploratory Data Analysis are:

- Understand the dataset structure.
- Understand the variables and their data types.
- Summarize the important characteristics of the data.
- Analyze numerical and categorical variables.
- Detect missing values and duplicate records.
- Identify outliers and unusual observations.
- Understand the distribution of variables.
- Analyze relationships between variables.
- Identify correlations.
- Discover patterns and trends.
- Generate meaningful insights.
- Support further data preprocessing and Machine Learning.

# 5. Types of EDA

EDA can mainly be performed using three types of analysis:

1. Univariate Analysis
2. Bivariate Analysis
3. Multivariate Analysis

## 5.1 Univariate Analysis

Univariate analysis means analyzing one variable at a time.

The main purpose is to understand the distribution and characteristics of a single variable.

### Examples

For an Age column, we can analyze:

- Minimum age
- Maximum age
- Mean age
- Median age
- Distribution of age
- Possible outliers

### Common techniques

- Mean
- Median
- Mode
- Standard deviation
- Frequency distribution
- Histogram
- Box plot
- Bar chart

### Example

If we have:

Age = [20, 22, 25, 25, 30, 35]

We can calculate the average age and visualize how the ages are distributed.

## 5.2 Bivariate Analysis

Bivariate analysis means analyzing two variables together.

The purpose is to understand the relationship or association between two variables.

### Examples

- Age vs Salary
- Experience vs Salary
- Gender vs Salary
- Study Hours vs Exam Result

### Common techniques

- Scatter plot
- Box plot
- Bar chart
- Correlation analysis

### Example

If we compare:

Experience vs Salary

we can investigate whether salary tends to increase as experience increases.

## 5.3 Multivariate Analysis

Multivariate analysis means analyzing more than two variables together.

It helps us understand relationships and interactions involving multiple variables.

### Examples

We may analyze:

Age + Experience + Salary

or:

Age + Salary + Gender + City

### Common techniques

- Heatmap
- Pair plot
- Scatter plot matrix
- Multivariable analysis

# 6. Understanding the Dataset

Before performing detailed analysis, we first inspect the basic structure of the dataset.

Important checks include:

- Number of rows and columns
- Column names
- First few records
- Last few records
- Data types
- Non-null values
- Missing values
- Basic statistical information

### Important Python Functions

```python
df.shape
df.head()
df.tail()
df.info()
df.dtypes
df.describe()