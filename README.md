# EDA_of_Iris.csv
Exploring and Visualizing a Simple Dataset Iris.csv. 


##🌸Iris Dataset – Exploratory Data Analysis (EDA)
###📌 Project Overview

This project performs initial data exploration and visualization on the famous Iris dataset using Python.
The goal is to understand the structure, distribution, and relationships between features using statistical analysis and visualizations.

###🛠 Tools & Libraries Used

- Python

- Pandas – for data loading and manipulation

- Matplotlib – for basic visualizations

- Seaborn – for enhanced data visualization

###📂 Dataset Loading

- The dataset was loaded using the Pandas library.

- Initial inspection was done using:

- .shape → to check the number of rows and columns

- .info() → to examine column data types

- .describe() → to get statistical summary (mean, std, min, max, quartiles)

###🧹 Data Cleaning & Preparation

-Column names were standardized for consistency.

-The species column was converted from object type to categorical data type to improve memory usage and clarity.

###📊 Data Visualization

Several visualizations were created to analyze the dataset:

####🔹 Bar Plot & Scatter Plot

**Used to study relationships between:**

Sepal length & width

Petal length & width

Helped in comparing measurements across different species.

####🔹 Histogram

Used to analyze the distribution of numerical features such as:

- Sepal length

- Sepal width

- Petal length

- Petal width

####🔹 Box Plot

Used to identify outliers in the dataset.

The Interquartile Range (IQR) method was applied to detect outliers mathematically.

###📈 Grouped Analysis

Calculated the average sepal length for each flower species using group-by operations.

This helped in comparing flower characteristics across species.

##✅ Key Findings

- Petal length and width show clear variation among different species.

- Box plots revealed potential outliers in some features.

- Setosa species tends to have smaller petal dimensions compared to others.

- Iris-setosa was the one that was way more distinguish from Iris-versicolor and Iris-virginica.So it can be distinguish base on either sepal or pertal features.
- Iris-versicolor and Iris-virginica are overllaping and they are difficult to distinguish.
- Feature distributions are mostly normal with slight skewness in some variables.

##📌 Conclusion

**This project demonstrates basic data analysis skills including:**

- Data loading and inspection

- Data cleaning and type conversion

- Statistical analysis

- Visualization using multiple plot types

- Outlier detection using IQR

- Grouped aggregation by category

It provides a strong foundation for further machine learning or classification tasks using the Iris dataset.
