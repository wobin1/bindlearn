---
title: "Classes in python"
date: 2022-03-30T6:18:58+01:00
categories:
- Programming Basics
- 
tags:
- programming basics, functions
keywords: 
- functions in python
- functions
- programming for beginners
- programming Basics

thumbnailImage: https://images.unsplash.com/photo-1592609931041-40265b692757?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8ZnVuY3Rpb258ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60
coverImage: https://images.unsplash.com/photo-1592609931041-40265b692757?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8ZnVuY3Rpb258ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60
metaAlignment: center
---

### Classes in python

A class is a blueprint used in building or creating objects, it is a guide used to building and creating objects. A class is made up of attributes and methods. e.g

If you want to build a computer there are properties every computer must have e.g ram(memory), storage disk, operating system, processor, etc. these properties will differ between computers.

Computers can be used to perform different functions after booting, these functions may include video editing, gaming, programming, and lots more. Some of the functions the computer performs happen immediately after booting e.g displaying time, displaying background pictures e.t.c. These properties and functions make up the computer which may vary for different computers i.e the properties and functions used for a Macbook will vary from those of a Hp computer and so on.

From the example above the computer can be seen as a class, the properties can be seen as attributes, and the functions can be seen as methods

### Steps to writing a class
- Declare the name of the class
- write your properties
- write your methods

Just as in computers if your program has properties and functions that you will use more than once it's a good practice to wrap them in a class. 

Let's say you need to collect the name and ages of 10 students to print. We will go through the above mention steps to solve the problem.

To solve this problem using classes we will follow the steps mentioned above.

### Declaring the class name
To declare you start with the keyword `class` followed by the name of the class, a parenthesis then `:` as shown below,
```python
class Student():
```
Just as in the code snippet Student is the name of our class
`Note:` The name of a class should always start with a capital letter.

### Writing the properties
Declaring the properties of a class in Python is done using the constructor as shown below.
```python
class Student():
    def __init__(self, name, age):
        self.name = name
        self.age = age
```
The `def __init__() ` in the code snippet is used to define constructors in python. The `self` is a keyword that binds the properties and argument together, it is used to access the attributes(properties) and methods(functions) of a class. `name` and `age` are the properties in theis case. `self.name` and `self.age` are variables holding the name and age.

### Writing the methods
Methods are functions in a class, i.e a function can only be called a method if its inside a class. We will add our print method as shown below.
```python
class Student():
    class Student():
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def print(self):
        return self.name + " you are " + self.age
```
From the code snippet above the method, print is returning the name property a string, and the age property.

### How to call the class
To call our class you will need to create an instance of the class for each object of the class as shown below.
```python
student1 = Student("john", "20")
```
To print each student all you need to do is create an instance for each student then print using the print function as shown below
```python
student1 = Student("john", "20")
print(student1.print())
```
The snippet above will print out ``` john you are 20``` 

#### Collecting names and ages and printing for the 10 student

```python
student1 = Student("nate", "34")
student2 = Student("john", "20")
student3 = Student("Joy", "16")
student4 = Student("Peter", "21")
student5 = Student("Parker", "25")
student6 = Student("James", "20")
student7 = Student("Hanah", "26")
student8 = Student("Patience", "14")
student9 = Student("Diane", "19")
student10 = Student("Raman", "20")


print(student1.print())
print(student2.print())
print(student3.print())
print(student4.print())
print(student5.print())
print(student6.print())
print(student7.print())
print(student8.print())
print(student9.print())
print(student10.print())
```

which will return output as shown below.
```bash
nate you are 34
john you are 20
Joy you are 16
Peter you are 21
Parker you are 25
James you are 20
Hanah you are 26
Patience you are 14
Diane you are 19
Raman you are 20
```
We looked at what a class is and how to write our class in python, you can play around with your class so you can have a much better understanding of the concept.