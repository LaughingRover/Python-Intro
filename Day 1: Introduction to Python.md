# Python Intro Course

## Day 1


## Brief Overview

Python is a popular, high-level programming language. It is known for its simplicity,
ease of use, and powerful features, making it an ideal language for beginners and
experts alike.

**Applications** :

1. Web Application
2. Data Analysis
3. Task Automation
4. Machine Learning
5. Web Scraping


In this introduction to Python and programming, you will learn the basics of
programming concepts such as variables, data types, control structures, functions,
and data structures. By the end of this course, you will have a solid foundation in
Python and programming, which will allow you to tackle more complex
programming challenges with confidence.


## Outline

* [Installing Python and an IDE](https://github.com/LaughingRover/Python-Intro/blob/main/Day%201:%20Introduction%20to%20Python.md#installing-python-and-an-ide)
* [Running the First Program](https://github.com/LaughingRover/Python-Intro/blob/main/Day%201:%20Introduction%20to%20Python.md#running-the-first-program)
* [Understanding Variables, Data Types, and Operators](https://github.com/LaughingRover/Python-Intro/blob/main/Day%201:%20Introduction%20to%20Python.md#understanding-variables-data-types-and-operators)
* [Basic Input and Output](https://github.com/LaughingRover/Python-Intro/blob/main/Day%201%3A%20Introduction%20to%20Python.md#basic-input-and-output)
* [Control Structures: Conditional Statements and Loops](https://github.com/LaughingRover/Python-Intro/blob/main/Day%201%3A%20Introduction%20to%20Python.md#control-structures-conditional-statements-and-loops)

## Installing Python and an IDE

IDE - Integrated Development Environment.

**Getting Started**

1. Visit the official Python website at https://www.python.org/downloads/ and
    download the latest version of Python for your operating system. Be sure to
    select the correct version for your computer, either 32-bit or 64-bit.
2. Follow the installation wizard and make sure to add Python to your system
    path during the installation process so that you can run Python commands
    from any directory on your computer.
3. Install Visual Studio Code from **store** or https://code.visualstudio.com/


## Running the First Program

1. Open your preferred IDE (such as PyCharm, VS Code, or Sublime Text) and create a new Python file. Let's call it "hello_world.py".
2. In the Python file, type the following code:

```python
print("Hello, World!")
```

3. Save the file with a .py extension. For example, you can save it as "hello_world.py".
4. Run the program by clicking on the "Run" button in your IDE or by opening your command prompt or terminal, navigating to the directory where the Python file is saved, and running the following command:

```bash
python hello_world.py
```

This will execute the program and output the message "Hello, World!" to the console. Congratulations, you have created and run your first Python program!


## Understanding Variables, Data Types, and Operators

**Variables** :

* Variables are containers for storing values in Python.
* To create a variable, you need to give it a name and assign a value to it using
the equal sign (=) operator. 

For example:
```py
x = 5
```

* You can then use the variable name in your code to refer to the value it holds.

For example: 
```py
print(x)
``` 

will output `5`.


## Data Types:

In programming, data types refer to the different kinds of data that can be stored and manipulated by a computer program. Each programming language has its own set of data types, but there are some common types that are found in most programming languages:

1. Integer: An integer is a whole number without a decimal point. In Python, for example, integers are represented by the int data type.

2. Float: A float, or floating-point number, is a number with a decimal point. In Python, floats are represented by the float data type.

3. String: A string is a sequence of characters. In most programming languages, strings are enclosed in quotes, such as "hello world". In Python, strings are represented by the str data type.

4. Boolean: A boolean is a data type that can only have one of two values: True or False. Booleans are often used in conditional statements and loops to control program flow.

5. List: A list is a collection of values, usually of the same data type, that can be indexed and manipulated. In Python, lists are represented by the list data type.

6. Tuple: A tuple is similar to a list, but it is immutable, meaning that its values cannot be changed after it is created. In Python, tuples are represented by the tuple data type.

7. Dictionary: A dictionary is a collection of key-value pairs, where each key is associated with a value. In Python, dictionaries are represented by the dict data type.

Different data types have different properties and methods associated with them. Understanding data types is an important concept in programming, as it helps you to write code that is efficient, effective, and easy to maintain.

* To check the data type of a value, you can use the type() function. For
example: `type(5)` will output `<class 'int'>`.
* You can also convert a value from one data type to another using type
conversion functions, such as `int()`, `float()`, `str()`, and `bool()`.


## Operators:


* Operators are symbols that perform operations on values in Python.
* Some common operators include:
    * Arithmetic operators, such as +, -, *, /, and %.
    * Comparison operators, such as ==, !=, <, >, <=, and >=.
    * Logical operators, such as and, or, and not.
* Operators follow the order of precedence, which determines the order in
which they are evaluated in an expression. You can use parentheses to
override the default precedence order.


## Basic Input and Output

## Output:


* To display text on the screen, you can use the `print()` function in Python. For
example: `print("Hello, world!")` will output Hello, world! to the console.


* You can also use the format() method to insert values into a string. For
example: `print("My name is {} and I am {} years old.".format("John", 30))` will
output `My name is John and I am 30 years old.`.


## Input

* To get input from the user, you can use the input() function in Python. For
example: `name = input("What is your name? ")` will prompt the user to enter
their name and store it in the name variable.


* By default, input() returns a string. If you want to get a different data type, you
need to convert the input value using type conversion functions, such as `int()`,
`float()`, or `bool()`.

```python
# Example code for data types and type conversion
x = 5
y = 3.14
z = "hello"
w = True

print(type(x))  # output: <class 'int'>
print(type(y))  # output: <class 'float'>
print(type(z))  # output: <class 'str'>
print(type(w))  # output: <class 'bool'>

a = float(x)
b = int(y)
c = str(w)
d = bool(z)

print(type(a))  # output: <class 'float'>
print(type(b))  # output: <class 'int'>
print(type(c))  # output: <class 'str'>
print(type(d))  # output: <class 'bool'>
```

Output:
```
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
<class 'float'>
<class 'int'>
<class 'str'>
<class 'bool'>
```

## Control Structures: Conditional Statements and Loops

Control structures are used in Python to control the flow of program execution. In this section, we'll cover two of the most important control structures: conditional statements and loops.

**Conditional Statements** :

Conditional statements allow you to execute different code blocks based on different
conditions.

The most common conditional statement in Python is the if statement. For example:


## If Statement
```py
age = 25
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```
In this example, the code will check if the age variable is greater than or equal to `18`. If it is, it will print `You are an adult.` Otherwise, it will print `You are a minor.`.


## Loops

Loops allow you to execute the same code block multiple times. are two types of loops in Python: for loops and while loops.

## For loops

For loops are used to iterate over a sequence of elements. For example:
```py
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```
In this example, the code will iterate over the fruits list and print each fruit on a separate line.


## While loops

While loops are used to execute a code block repeatedly while a certain condition
is true. For example:
```py
i = 0
while i < 5:
    print(i)
    i += 1
```

In this example, the code will print the numbers from 0 to 4, because the condition
`i < 5` is true for these values of `i`.


By using conditional statements and loops, you can create more complex and
dynamic programs that can adapt to different conditions and iterate over
sequences of elements.

## Exercise

1. Write a Python program that calculates the area and perimeter of a rectangle.
    The program should prompt the user to enter the length and width of the
    rectangle, and then print the area and perimeter.
2. Write a Python program that converts temperature from Fahrenheit to Celsius.
    The program should prompt the user to enter a temperature in Fahrenheit,
    and then print the temperature in Celsius.
3. Write a Python program that checks if a number is even or odd. The program
    should prompt the user to enter a number, and then print whether the number
    is even or odd.

4. Write a Python program that calculates the factorial of a number. The program
    should prompt the user to enter a number, and then print the factorial of that
    number.
5. Write a Python program that finds the largest element in a list. The program
    should prompt the user to enter a list of numbers, and then print the largest
    element in the list.
