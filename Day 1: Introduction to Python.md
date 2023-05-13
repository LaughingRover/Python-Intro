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

* Installing Python and an IDE
* Running the First Program
* Understanding Variables, Data Types, and Operators
* Basic Input and Output
* Control Structures: Conditional Statements and Loops

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

1. Open your preferred IDE (Integrated Development Environment) and create a
    new Python file. You can name it anything you like, but it's a good idea to give
    it a descriptive name.
2. In the Python file, type the following code: print("Hello, World")
3. Save the file with a .py extension. For example, you can save it as
    "hello_world.py".
4. Run the program by either clicking on the "Run" button in your IDE, or by
    opening your command prompt (Windows) or terminal (Mac or Linux),
    navigating to the directory where the Python file is saved, and running the
    following command: python hello_world.py


## Understanding Variables, Data Types, and Operators

**Variables** :

* Variables are containers for storing values in Python.
* To create a variable, you need to give it a name and assign a value to it using
the equal sign (=) operator. For example: x = 5
* You can then use the variable name in your code to refer to the value it holds.
For example: print(x) will output 5.


## Data Types:


* Python supports various data types, such as integers, floating-point numbers,
strings, and booleans.
* To check the data type of a value, you can use the type() function. For
example: type(5) will output <class 'int'>.
* You can also convert a value from one data type to another using type
conversion functions, such as int(), float(), str(), and bool().


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

Output:


* To display text on the screen, you can use the print() function in Python. For
example: print("Hello, world!") will output Hello, world! to the console.


* You can also use the format() method to insert values into a string. For
example: ```print("My name is {} and I am {} years old.".format("John", 30))``` will
output My name is John and I am 30 years old..


## Input

* To get input from the user, you can use the input() function in Python. For
example: ```name = input("What is your name? ")``` will prompt the user to enter
their name and store it in the name variable.


* By default, input() returns a string. If you want to get a different data type, you
need to convert the input value using type conversion functions, such as ```int()```,
```float()```, or ```bool()```.


## File Input and Output:

* You can also read and write data to files in Python using file input/output (I/O)
operations.
* To open a file for reading, use the open() function with the file name and
mode. For example: file = open("myfile.txt", "r") will open the file myfile.txt for
reading.
* To read the contents of the file, you can use the read() method on the file
object. For example: contents = file.read() will read the entire contents of the
file into the contents variable.
* To write data to a file, you can use the write() method on the file object. For
example: file.write("Hello, world!") will write the text Hello, world! to the file.

* After you're done with the file, it's important to close it using the close()
method. For example: file.close() will close the file.

By mastering input/output operations in Python, you'll be able to create more
complex and interactive programs that can interact with users and read and write
data to files. More on reading and writing with python


## Control Structures: Conditional Statements and Loops

Control structures are used in Python to control the flow of program execution. In this
section, we'll cover two of the most important control structures: conditional statements
and loops.

**Conditional Statements** :

Conditional statements allow you to execute different code blocks based on different
conditions.

The most common conditional statement in Python is the if statement. For example:


## If Statement
```
age = 25
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```
In this example, the code will check if the age variable is greater than or equal to

18. If it is, it will print You are an adult. Otherwise, it will print You are a minor..


## Loops

Loops allow you to execute the same code block multiple times.

There are two types of loops in Python: for loops and while loops.

**For loops** are used to iterate over a sequence of elements. For example:

```
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```
In this example, the code will iterate over the fruits list and print each fruit on a separate line.


## While loops

while loops are used to execute a code block repeatedly while a certain condition
is true. For example:
```
i = 0
while i < 5:
    print(i)
    i += 1
```

In this example, the code will print the numbers from 0 to 4, because the condition
```i < 5``` is true for these values of ```i```.


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


