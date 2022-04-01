---
title: "How To Read CSV Using Pandas"
date: 2022-03-30T6:18:58+01:00
categories:
- Machine Learning
- 
tags:
- Machine Learning, Data Science, Artificial Intelligence
keywords: 
- Machine Learning
- Data Science
- Pandas
- CSV

thumbnailImage: https://images.unsplash.com/photo-1529078155058-5d716f45d604?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80
coverImage: https://images.unsplash.com/photo-1529078155058-5d716f45d604?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80
metaAlignment: center
---


### CSV
CSV is an acronym for Commer Separated values, it is sometimes refered to as Character Separated Values. A CSV file is a plain text file containing a list of information separated by commas or other characters, which can be used to share or transfer information between applications.

### Pandas
Pandas is a python package or library that is used for data analysis, it is the most flexible and fast tool to use when working with data in python.

### How to read a CSV file using pandas
Pandas have a method that makes it easier to read a CSV file, reading a CSV file using pandas is as easy as shown below.
```python
import pandas as pd

df = pd.read_csv('name of csv file')

print(df)
```
From the code snippet above we have to first import pandas as pd so we can use the keyword pd where ever we need to use pandas. `df` means data frame,  what pandas do is load the CSV data into a data frame which will organize the data into rows and columns. `read_csv` is the method pandas provide for the loading of CSV files. 

The code snippet above loaded the data in the file as a data frame and printed it out on the terminal. If you run the code using your CSV file it will print out only the first five and last five of the data frame if the total rows generated are more than the maximum row set in your computer.

There are two ways you can print the whole rows first is to use `to_string()` method provided by pandas or increase the maximum rows your computer can display.

### Using to_string() method
Using the `to_string` method your code will look as below.
```python
import pandas as pd 

df = pd.read_csv("name of csv file")

print(df.to_string())
```
The above code snippet will print the whole rows in the data frame.

### Increasing maximum rows
To increase the maximum number of rows to be returned you can do that using pandas.
```python
import pandas as pd

print(pd.options.display.max_rows)
```
Mine return 60. You can increase the maximum row and print the data frame as shown below.
```python
import pandas as pd

pd.options.display.max_rows = 9999

df = pd.read_csv("name of csv file")

print(df)
```
The above code snippet will print out the whole rows in the data frame.

We looked at what CSV and Pandas is and how you can use Pandas to read CSV files, you can read more about pandas [here](https://pandas.pydata.org/).