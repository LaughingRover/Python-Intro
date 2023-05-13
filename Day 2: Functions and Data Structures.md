# Functions and Data

# Structures

## Day 2


### Brief Overview

Functions and data structures are two essential concepts in programming.
Functions are blocks of reusable code that perform specific tasks, while data
structures are containers that hold data in a specific format. By mastering these
concepts, programmers can create modular, efficient, and well-organized code
that is easier to maintain and scale. In this course on functions and data
structures, you will learn how to define and use functions, as well as how to work
with various data structures such as lists, tuples, sets, and dictionaries. By the end
of this course, you will have a solid understanding of these fundamental concepts,
which will allow you to write more efficient and effective code.


### Outline

* [Understanding Functions and Creating your Own](https://github.com/LaughingRover/Python-Intro/blob/main/Day%202%3A%20Functions%20and%20Data%20Structures.md#understanding-functions-and-creating-your-own)
* [Built-in Functions and Standard Library Functions](https://github.com/LaughingRover/Python-Intro/blob/main/Day%202%3A%20Functions%20and%20Data%20Structures.md#built-in-functions-and-standard-library-functions)
* [Working with Lists, Tuples, and Dictionaries](https://github.com/LaughingRover/Python-Intro/blob/main/Day%202%3A%20Functions%20and%20Data%20Structures.md#working-with-lists-tuples-and-dictionaries)
* [Basic Operations on Data Structures](https://github.com/LaughingRover/Python-Intro/blob/main/Day%202%3A%20Functions%20and%20Data%20Structures.md#basic-operations-on-data-structures)
* [String Manipulation](https://github.com/LaughingRover/Python-Intro/blob/main/Day%202%3A%20Functions%20and%20Data%20Structures.md#string-manipulation)

### Understanding Functions and Creating your Own

Functions are reusable blocks of code that perform a specific task or a set of
tasks. They allow programmers to break down complex programs into smaller,
more manageable pieces of code.

In Python, functions are defined using the `def` keyword followed by the function
name and its parameters. Once defined, functions can be called and used multiple
times within a program, providing a modular and efficient approach to
programming.


To create your own functions, you will need to understand how to define the
function using the correct syntax, including specifying the function name, the
parameters it takes, and the code block that performs the desired task.
Additionally, you will need to understand how to call the function within your code
and how to pass arguments to the function.

By mastering the creation and use of functions, you can write more efficient and
organized code that is easier to maintain and scale. This knowledge is crucial for
building complex programs and applications.

Here is an example of defining and calling a simple function in Python:

```python
# Defining a function that takes in two parameters and returns their sum
def add_numbers(num1, num2):
    sum = num1 + num2
    return sum

# Calling the function with arguments and printing the result
result = add_numbers(5, 10)
print(result)   # Output: 15
```

In this example, we define a function called `add_numbers` that takes in two parameters `num1` and `num2` and returns their sum. We then call the function with arguments `5` and `10` and store the result in a variable called `result`. Finally, we print the result using the `print` function.

Functions can also have optional parameters and default values. Here's an example:

```python
# Defining a function with optional parameters and default values
def greet(name, greeting="Hello"):
    message = f"{greeting}, {name}!"
    print(message)

# Calling the function with and without optional parameters
greet("John")           # Output: Hello, John!
greet("Sarah", "Hi")    # Output: Hi, Sarah!
```

In this example, we define a function called `greet` that takes in a mandatory parameter `name` and an optional parameter `greeting` with a default value of "Hello". The function then prints out a message that includes the greeting and the name. We call the function twice, once with just the mandatory parameter and once with both parameters. The output includes the greeting and the name for each call.


### Built-in Functions and Standard Library Functions

Python comes with a wide range of built-in functions that can be used to perform
common tasks such as math operations, data conversion, input/output operations,
and more. These built-in functions can be used directly in your code without the
need for any additional modules or libraries.

Examples of built-in functions include `print()`, `len()`, `type()`, `range()`, `abs()`,
and `input()`. These functions are predefined by Python and can be used in your
code by simply calling them by their name.


In addition to built-in functions, Python also has a vast collection of modules in its
standard library, which contains many useful functions that can be used for a wide range
of tasks such as string manipulation, file operations, networking, and more. These
modules can be imported into your code using the `import` keyword, allowing you to use
the functions they contain.

Examples of standard library functions include `os.path.join()` for file path manipulation,
`random.choice()` for random value selection, `urllib.request.urlopen()` for web data
retrieval, and `json.dumps()` for JSON serialization.

By mastering both built-in and standard library functions, you can write more efficient and
effective code, reducing the time and effort required to complete programming tasks.

Here are some examples of using built-in and standard library functions in Python:

Example 1: Using the len() function to get the length of a string

```python
# Define a string variable
my_string = "Hello, World!"

# Use the len() function to get the length of the string
string_length = len(my_string)

# Print the length of the string
print(string_length)    # Output: 13
```

In this example, we use the built-in function len() to get the length of a string. The function takes a string as input and returns the number of characters in the string.

Example 2: Using the random module to generate a random number

```python
# Import the random module
import random

# Use the random.randint() function to generate a random number between 1 and 10
random_number = random.randint(1, 10)

# Print the random number
print(random_number)
```

In this example, we import the random module from the standard library using the import keyword. We then use the random.randint() function to generate a random integer between 1 and 10. The function takes two arguments: the lowest and highest values that the random number can be.

Example 3: Using the os module to get the current working directory

```python
# Import the os module
import os

# Use the os.getcwd() function to get the current working directory
cwd = os.getcwd()

# Print the current working directory
print(cwd)
```

In this example, we import the os module from the standard library and use the os.getcwd() function to get the current working directory. The function returns a string representing the path of the current working directory.

### Working with Lists, Tuples, and Dictionaries

Lists, tuples, and dictionaries are three common data structures in Python. They
are used to store and manipulate data in different ways, and each has its own
advantages and disadvantages depending on the task at hand.

A list is an ordered collection of items, which can be of any data type. Lists are
mutable, which means that you can add, remove, or modify items within a list after
it has been created. Lists are defined using square brackets, with each item
separated by a comma.


A tuple is similar to a list, but it is immutable, which means that once a tuple is defined,
you cannot add, remove, or modify its items. Tuples are defined using parentheses, with
each item separated by a comma.

A dictionary is an unordered collection of key-value pairs, where each key is unique.
Dictionaries are mutable, and items can be added, removed, or modified after the
dictionary has been created. Dictionaries are defined using curly braces, with each
key-value pair separated by a colon and each item separated by a comma.

By mastering the use of lists, tuples, and dictionaries, you can store and manipulate data
in a variety of ways, allowing you to write more efficient and effective code for a wide
range of programming tasks.

Here are some examples of working with lists, tuples, and dictionaries in Python:

Lists:
```python
# Creating a list and accessing its items
my_list = [1, "hello", 3.14, True]
print(my_list[1])   # Output: hello

# Adding items to a list
my_list.append("world")
print(my_list)   # Output: [1, "hello", 3.14, True, "world"]

# Removing items from a list
my_list.remove(3.14)
print(my_list)   # Output: [1, "hello", True, "world"]
```

Tuples:
```python
# Creating a tuple and accessing its items
my_tuple = (1, "hello", 3.14, True)
print(my_tuple[2])   # Output: 3.14

# Converting a list to a tuple
my_list = [1, "hello", 3.14, True]
my_tuple = tuple(my_list)
print(my_tuple)   # Output: (1, "hello", 3.14, True)
```

Dictionaries:
```python
# Creating a dictionary and accessing its items
my_dict = {"name": "John", "age": 30, "city": "New York"}
print(my_dict["age"])   # Output: 30

# Adding items to a dictionary
my_dict["gender"] = "Male"
print(my_dict)   # Output: {"name": "John", "age": 30, "city": "New York", "gender": "Male"}

# Removing items from a dictionary
del my_dict["city"]
print(my_dict)   # Output: {"name": "John", "age": 30, "gender": "Male"}
```

### Basic Operations on Data Structures

Python provides a wide range of basic operations that can be performed on data
structures such as lists, tuples, and dictionaries. These operations allow you to
manipulate and process data in various ways, making it easier to work with data
and solve complex problems.

Some of the basic operations that can be performed on data structures include:

- Accessing elements: You can access individual elements within a data structure
using their index or key. For example, to access the first element in a list, you can
use the index `0`.


- Slicing: You can extract a range of elements from a data structure using slicing.
For example, to extract the first three elements of a list, you can use `my_list[:3]`.
- Adding elements: You can add elements to a data structure using methods such
as `append()` for lists, `update()` for dictionaries, and concatenation for tuples.
- Removing elements: You can remove elements from a data structure using
methods such as `remove()` for lists, `pop()` for dictionaries, and slicing for tuples.


- Sorting and searching: You can sort and search data structures using methods
such as `sort()` and `sorted()` for lists, `sorted()` for dictionaries, and `sorted()` for
tuples.

By mastering these basic operations, you can effectively manipulate and process
data structures in Python, making it easier to work with complex data sets and
solve a wide range of programming problems.

Here are some code examples for the basic operations on data structures in Python:

### Accessing elements

```python
my_list = [1, 2, 3, 4, 5]
my_dict = {"a": 1, "b": 2, "c": 3}

# Accessing the third element of the list
print(my_list[2])   # Output: 3

# Accessing the value of the key "b" in the dictionary
print(my_dict["b"])   # Output: 2
```

### Slicing

```python
my_list = [1, 2, 3, 4, 5]
my_tuple = (1, 2, 3, 4, 5)

# Extracting the first three elements of the list
print(my_list[:3])   # Output: [1, 2, 3]

# Extracting the last two elements of the tuple
print(my_tuple[-2:])   # Output: (4, 5)
```

### Adding elements

```python
my_list = [1, 2, 3]
my_dict = {"a": 1, "b": 2}

# Adding an element to the end of the list
my_list.append(4)
print(my_list)   # Output: [1, 2, 3, 4]

# Adding a new key-value pair to the dictionary
my_dict.update({"c": 3})
print(my_dict)   # Output: {"a": 1, "b": 2, "c": 3}
```

### Removing elements

```python
my_list = [1, 2, 3, 4, 5]
my_dict = {"a": 1, "b": 2, "c": 3}

# Removing the third element from the list
my_list.pop(2)
print(my_list)   # Output: [1, 2, 4, 5]

# Removing the key-value pair with the key "b" from the dictionary
del my_dict["b"]
print(my_dict)   # Output: {"a": 1, "c": 3}
```

### Sorting and searching

```python
my_list = [5, 2, 1, 4, 3]
my_dict = {"a": 1, "b": 2, "c": 3}

# Sorting the list in ascending order
my_list.sort()
print(my_list)   # Output: [1, 2, 3, 4, 5]

# Sorting the dictionary by value in ascending order
sorted_dict = dict(sorted(my_dict.items(), key=lambda x: x[1]))
print(sorted_dict)   # Output: {"a": 1, "b": 2, "c": 3}
```

### String Manipulation

String manipulation refers to the process of manipulating and transforming text data in Python. Python provides several built-in methods that can be used to manipulate strings, allowing you to perform a variety of operations such as searching, replacing, and formatting text. Some of the common string manipulation operations in Python include:

- Concatenation: You can join two or more strings together using the `+`
 operator or the `join()` method.


- Slicing: You can extract a substring from a string using slicing. For
 example, to extract the first three characters of a string, you can use
 `my_string[:3]`.

- Searching and replacing: You can search for a substring within a string
 and replace it with a new value using methods such as `find()`, `replace()`,
 and `split()`.

- Formatting: You can format strings in various ways using methods such as
 `format()` and f-strings.


- Case conversion: You can convert a string to uppercase or lowercase using the `upper()` and `lower()` methods. By mastering these string manipulation operations, you can effectively process and manipulate text data in Python, making it easier to work with and analyze textual data sets.

Here are some examples of string manipulation operations in Python:

Concatenation:
```
first_name = "John"
last_name = "Doe"
full_name = first_name + " " + last_name
print(full_name) # Output: "John Doe"
```

Slicing:
```
my_string = "Hello, World!"
substring = my_string[7:12]
print(substring) # Output: "World"
```

Searching and replacing:
```
my_string = "Hello, World!"
new_string = my_string.replace("World", "Python")
print(new_string) # Output: "Hello, Python!"
```

Formatting:
```
name = "John"
age = 30
formatted_string = "My name is {} and I am {} years old".format(name, age)
print(formatted_string) # Output: "My name is John and I am 30 years old"
```

Case conversion:
```
my_string = "Hello, World!"
upper_case = my_string.upper()
lower_case = my_string.lower()
print(upper_case) # Output: "HELLO, WORLD!"
print(lower_case) # Output: "hello, world!"
```

### Exercise

1. Write a function that takes a list of integers as input and returns the sum of all
the even numbers in the list.
2. Write a function that takes a dictionary as input and returns a list of all the keys
in the dictionary sorted in alphabetical order.
3. Write a function that takes a list of strings as input and returns a new list
containing only the strings that start with a vowel.
4. Write a function that takes a list of numbers as input and returns the average of
the numbers in the list.
5. Write a function that takes a list of tuples, where each tuple contains a name
and an age, and returns the name of the oldest person in the list.
