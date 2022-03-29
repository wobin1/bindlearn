### What is a function
A function is a block of code that performs a single functionality, written in a way that it can be reusable in a codebase. 

A function will help you reduce the bulkiness of a codebase, thereby making debugging easier and faster.

### Steps to writing a function
- To write a function there are four basic steps you will take;
- Declaring the function with a name
- Passing parameters for the function
- Writing your functionality
- Returning an output

### Defining a function
to define a function you start by calling the keyword `def`, followed by the name of the function, followed by a parenthesis then end the line with a colon as shown below.
```python 
def name_of_function():
    pass
```
`pass` In the snippet above means tells the program that the function does nothing.

### Passing Parameters
Parameters in functions can be seen as variables declared to hold the data or inputs that will be used to build the functionality in a function. An example of a function with parameters is shown below,

```python 
def addition(num1, num2):
    pass
```
`num1` and `num2` define what the function will take as input when calling it.

### Writing a functionality
The functionality in a function is the main purpose of the function, it's the action expected to be carried out by the function whenever it's called. below is an example of a function with a functionality.
```python
def addition(num1, num2):
    sum = num1 + num2

```
From the code snippet above the summation of num1 and num2 is the functionality of the addition function.

### Returning an output
A function will not return an output until it is told what to return i.e the addition function above will not return an output until it is told what to return. below is an example of a function with a return statement
```python
def addition(num1, num2):
    sum = num1 + num2
    return sum
```
The code snippet above will return the summation of the two inputs provided to the function. If you are testing your code on a terminal make sure you print the functionality before calling the function as shown below.
```python
def addition(num1, num2):
    sum = num1 + num2
    print(sum)
    return sum
```

The print is an inbuilt function in python that takes an argument(will explain what argument means in a bit) or input and prints it on a terminal.

### Calling a function
calling a function is like triggering the function to perform that task it was built for. To call a function you write the name of the function followed by a parenthesis. Add the input inside the parenthesis if the function has parameters passed when it was defined, below is an example of how a function is called.
```python
name_of_function()
```
To call your addition function which has num1 and num2 parameters

```python
addition(3, 5)
```
The code snippet above will print and return 8.


Difference between Parameters and Argument
Arguments and parameters are often used interchangeably, arguments are the input you pass when calling a function.

Parameters are variables that will hold inputs a function will act upon to create functionality while arguments are the inputs passed while calling a function.

parameters are passed when declaring a function while arguments are passed when calling a function.

NOTE: The number of arguments passed in a function must be equal to the number of parameters declared.

You can play around with functions that perform other functionalities
