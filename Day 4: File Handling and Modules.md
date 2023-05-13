# File Handling and Modules

## Day 4


## Brief Overview

File handling and modules are important concepts in Python that allow developers to work with files and organize code into reusable components.

File handling refers to the ability to read and write data to and from files. Python provides a rich set of functions and libraries for working with files, including functions for opening, closing, reading, and writing files. File handling is an essential skill for developers who need to work with data stored in files, such as CSV, JSON, and XML files.

Modules, on the other hand, are self-contained units of code that can be imported and used in other programs. They allow developers to organize their code into reusable components, making it easier to write, maintain, and extend code over time. Python provides a large standard library of modules that can be used for common tasks, such as working with dates and times, sending emails, and connecting to databases. Additionally, developers can create their own modules to share with others or use in their own programs.

Together, file handling and modules are powerful tools that allow developers to work with data stored in files and organize their code into reusable components. By mastering these concepts, developers can write more efficient and maintainable code, and build more robust and reliable applications.

## Outline

* [File Handling Operations: Reading and Writing Files](https://github.com/LaughingRover/Python-Intro/blob/main/Day%204%3A%20File%20Handling%20and%20Modules.md#file-handling-operations-reading-and-writing-files)
* [Understanding Modules and Importing Them](https://github.com/LaughingRover/Python-Intro/blob/main/Day%204%3A%20File%20Handling%20and%20Modules.md#understanding-modules-and-importing-them)
* [Creating and Importing Your Own Modules](https://github.com/LaughingRover/Python-Intro/blob/main/Day%204%3A%20File%20Handling%20and%20Modules.md#creating-and-importing-your-own-modules)


## File Handling Operations: Reading and Writing Files

File handling operations in Python are an essential part of working with data
stored in files. Two common file handling operations are reading from and writing to files.

To read from a file in Python, you can use the built-in `open()` function to open a file and then use the `read()` or readline() method to read the contents of the file. The `read()` method reads the entire contents of the file as a single string, while the `readline()` method reads a single line from the file.


To write to a file in Python, you can use the same `open()` function to open a file, but you must pass the `w` parameter to indicate that you want to write to the file. Then, you can use the `write()` method to write data to the file.

It's important to remember to close the file after you're done working with it. You can do this using the `close()` method.

In addition to reading and writing files, Python provides several other file handling operations, such as appending to a file, renaming a file, and deleting a file. By mastering these operations, you can work with data stored in files more efficiently and effectively in your Python programs.


## Understanding Modules and Importing Them

Modules in Python are pre-written Python files that can be used to add functionality to a program. They are essentially libraries of code that you can import into your program to perform specific tasks.

To use a module in Python, you first need to import it into your program. This is typically done using the import statement, followed by the name of the module. For example, to import the math module, you would use the following statement:

```py
import math
```

Once you've imported a module, you can access its functions and variables by using dot notation. For example, to use the `sin()` function from the math module, you would use the following code:

```py
import math
x = math.sin(3.14)
```

You can also import specific functions or variables from a module using the from...import statement. For example, to import only the `sin()` function from the math module, you would use the following code:

```py
from math import sin
x = sin(3.14)
```

In addition to the built-in modules that come with Python, you can also create your own custom modules and import them into your programs. By understanding how to use and import modules in Python, you can build more complex and powerful applications that leverage the vast library of available modules.

## Creating and Importing Your Own Modules

Creating and importing your own modules is an important concept in Python that allows you to organize your code into reusable components.

In Python, a module is a file containing Python definitions and statements. You can create your own module by writing Python code in a file with a *.py* extension. Once you've created a module, you can import it into another Python script using the import statement.

Importing your own modules can help you organize your code into reusable components and improve the readability and maintainability of your code. By breaking your code into smaller modules, you can focus on specific functionality in each module and make changes more easily.

In addition, Python provides several tools to help you manage your modules, including the module search path, which determines where Python looks for modules, and the `dir()` function, which lists the attributes of a module.

Overall, creating and importing your own modules is an essential skill for Python developers who want to write efficient and maintainable code. By mastering this concept, you can build more robust and reliable applications that are easier to maintain and extend over time.

Here's an example of how to create and import a module in Python:

1. Create a file called my_module.py and add the following code:

```py
def greet(name):
    print(f"Hello, {name}!")
```

2. In another Python script, import the module using the import statement:

```py
import my_module

my_module.greet("John")
```

This will output "Hello, John!" to the console.

You can also import specific functions from a module using the from ... import statement:

```py
from my_module import greet

greet("Jane")
```

This will output "Hello, Jane!" to the console.

Finally, you can give a module an alias using the as keyword:

```py
import my_module as mm

mm.greet("Bob")
```

This will output "Hello, Bob!" to the console.

## Exercise

1. Write a Python script that creates a new text file and writes the string **"Hello, world!"** to the file. Then read the contents of the file and print them to the console.
2. Write a Python script that takes a filename as input and prints the number of lines in the file.
3. Write a Python script that reads a CSV file containing information about books (title, author, publisher, and year of publication) and prints out the information in a formatted table.
4. Write a Python script that reads a text file containing a list of names and sorts them alphabetically. Then write the sorted names to a new file.
5. Write a Python script that reads a JSON file containing information about employees (name, age, department, and salary) and calculates the average salary for each department. Then write the results to a new JSON file.
