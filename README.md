# BI-Analytics

Course - Introduction
Welcome to the course on scikit-learn.

In this course, you will understand all the practical aspects of fitting a Machine Learning Model.
You will learn:

The different steps involved in this process such as data acquisition, data transformation, data cleaning and model fitting.
How to perform each step using Python scikit-learn package?

****************************************************
Introduction to Machine Learning
According to Arthur Samuel,

Machine learning is a field of computer science that gives computers the ability to learn without being explicitly programmed.

A Machine learning project is typically classified into two categories, depending on its learning system.
Supervised Learning
Unsupervised Learning.

-----------------------------------------------------

Imputation\\
Imputation replaces missing values with either median, mean, or the most common value of the column or row in which the missing values exist.\

Below example replaces missing values, represented by np.nan, with the mean of respective column (axis 0).\
Example\
imputer = preprocessing.Imputer(missing_values='NaN', strategy='mean')\

imputer = imputer.fit(breast_cancer.data) \
breast_cancer_imputed = imputer.transform(breast_cancer.data)
