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

* Understanding Functions and Creating your Own
* Built-in Functions and Standard Library Functions
* Working with Lists, Tuples, and Dictionaries
* Basic Operations on Data Structures
* String Manipulation

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
