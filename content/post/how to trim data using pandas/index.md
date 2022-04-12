---
title: "How to trim data with Python using Pandas"
date: 2022-04-12T6:18:58+01:00
categories:
- Machine Learning
- 
tags:
- Machine Learning
keywords: 
- triming data in python
- Pandas
- machine learning for beginners
- programming basics

thumbnailImage: https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1476&q=80
coverImage: https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1476&q=80
metaAlignment: center
---

### Data Trimming
Data trimming is the process of picking relevant data from a data set, data trimming happens when a researcher neglects other parts of data considered not useful to the research he/she is conducting thereby picking only necessary data points. 

### Pandas
Pandas is a python package or library that is used for data analysis, it is the most flexible and fast tool to use when working with data in python. We will be using pandas to read the data set we want to trim.

### Prerequisite
to follow this tutorial it is assumed you have;
- A basic knowledge of python
- A data set you want to work with or you can download [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00320/).

### Steps to trimming data using python
- install pandas
- import pandas
- read data set using pandas
- trim the data

#### Installing pandas
You can install pandas using the command below on the terminal
```cmd
pip install pandas
```

#### Importing Pandas
To import pandas add the below code snippet at top of your codebase
```python 
import pandas as pd
```
We are importing pandas as pd i.e you can use pd to represent pandas anywhere in your code.

#### Reading the data set
You can read your data set as shown below.
```python
data = pd.read_csv("student-mat.csv", sep=";")
````
From the code above we are reading a CSV file type, the pandas object is using the read_csv file to read `student-mats.csv` which the CSV file contains our data set. We are using `sep=;` to have our data frame well arranged because the data in the CSV file we are using is separated using `;` instead of a comma. You can read more on how to read CSV [here](https://www.bindlearn.com/post/how-to-read-csv-using-pandas/)

#### Trimming the data
Trim the data using the snippet as shown below
```python
data = data[["G1", "G2", "G3", "studytime", "failures", "absences"]]
```
The code above will only pick data from the columns above, thereby neglecting the other data.

### Conclusion
We were able to look at how to read and trim data using pandas, You can play around with the data by choosing different data points to trim.