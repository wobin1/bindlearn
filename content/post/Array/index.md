---
title: "Arrays"
date: 2021-09-21T09:00:33+01:00
categories:
- Programming Basics
- 
tags:
- programming basics
keywords: 
- arrays
- what is an array
- python arrays
- how to create an array
- how to delete elements in arrays
- how to add elements in arrays
- programming for beginners
- programming Basics

thumbnailImage: https://images.unsplash.com/photo-1523961131990-5ea7c61b2107?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=774&q=80
coverImage: https://images.unsplash.com/photo-1523961131990-5ea7c61b2107?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=774&q=80
metaAlignment: center
---
To understand arrays it is necessary to have an understanding of variables, you can refer to this [article](https://www.bindlearn.com/post/variable-in-python/) if you don't have an understanding of variables. It is easier to store a name in a variable but imagine you need to store up to 5000 names in a program, will you store each name in a variable? this is where the concept of arrays comes into play.

### What Is An Array
An array is a type of data structure consisting of a collection of elements of the same [data type](https://www.bindlearn.com/post/data-types-in-python/) that can be referenced by a unique array index. The elements in an array are stored in memory locations which can be accessed using an index starting from 0 depending on the length of the array. In other words, we can say an array is a variable used for storing multiple data or information of the same data type. Below is an image of how an array is indexed.

![Arrays](array.png)

The array in the image above shows how arrays are indexed the array is made up of ten elements the first element is stored in a location of index 0 while the last is stored at index 9. This means the first element can be accessed with the index number 0 while the last element can be accessed with the index number (length of array - 1) in the context of the array in the above picture (10 - 9).

### How To Create an Array
Just as creating [variables](https://www.bindlearn.com/post/variable-in-python/) differs depending on a programming language so does create arrays. Compiled languages such as java require you to declare the array before assigning values to it while Interpreted languages such as python do not require you to declare before assignment. 

#### Creating Arrays in Java
```java
// declaring an array of strings
String[] countries;

// inserting values to the arrays of strings
String[] countries = {"Ghana", "France", "Italy", "China"};

// declaring an array of integers
Int[] numbers;

// inserting values to the array of integers
int[] numbers = {10, 20, 30, 40};

```

#### Creating Arrays in Python
To use arrays in python you will have to import a library called numpy but lists in python can be treated as arrays. Creating arrays in python can be as easy as shown below
```python
# creating an array of strings
array = ["man", "woman", "Boy", "Girl"]

# creating an array of integers
numbers = [1, 3, 6, 8, 9]
```
### How To Access Elements in Arrays
Accessing elements in arrays is done by referencing the index assigned to each element.

#### Accessing Arrays In Java
Accessing an element from the java array we created from the create array section above
```java
// accessing the first element of the array
System.out.println(countries[0]);

// output
Ghana
```

#### Accessing Arrays in python 
Accessing an element from the python array we created from the create array section above
```python 
# accessing the first element of the array
print(array[0])

# output
man
```
### Multidimensional Array
A multidimensional array is an array of arrays, i.e an array whose elements is a collection of arrays. a multidimensional is as seen bellow
```python
array = [[1,2,3,4,5], ['john', 'bisi', 'peter', 'joy']]
```
a multidimensional can take arrays of different data types as elements as shown in the code snippet above. A multidimensional array can be accessed as shown below
```python 
# from the array above picking the second element of the first array 
array[0][1]

# output 
2
```
### How To Add To an Array
In python, elements are added to an array using a method called append(). Adding to an array in python looks like shown below.
```python
# creating an empty array 
names = []

# adding to the array
name.append('James')

# print the array
print(name)

# output
['james']
```
from the code snippet above the append() method takes anything we add as an argument is what is added to the array.

### Deleting From an Array
There are two ways to delete an element from the array one way is using the `pop()` method or `remove()` method. Below is a code snippet that shows how to delete elements from an array in python.
```python 
# creating an array
names = ["man", "woman", "Boy", "Girl"]

# removing the first element using remove()
names.remove("man")

# printing the new array
print(names)

# output
["woman", "Boy", "Girl"]

# removing the first element using pop()
names.pop(0)

# printing the new array
print(names)

# output
["woman", "Boy", "Girl"]

```
from the code snippet above removing the element using the `remove()` method takes the element you want to remove as an argument while using the `pop()` method takes the index of the element you want to remove as an argument.

### Conclusion 
Arrays are a very important concept in programming, it's a prerequisite to a lot of concepts in programming thereby making it a mandatory concept to understand if you ever want to build software. 

Feel free to leave comments or questions in the comment section I'll be glad to respond to you. Thank you!!

