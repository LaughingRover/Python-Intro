# Object-Oriented

# Programming

## Day 3


## Brief Overview

Object-Oriented Programming (OOP) is a programming paradigm that focuses on
the use of objects to model real-world concepts and entities. In OOP, programs are designed and implemented as collections of objects that interact with each other to perform a specific task.

The basic idea behind OOP is to represent objects as instances of classes, which are templates that define the properties and behavior of objects. Objects have attributes (data) and methods (functions) that allow them to interact with other objects in the program.


OOP has several key features, including encapsulation, inheritance, and polymorphism. Encapsulation involves hiding the implementation details of an object and providing a well-defined interface for interacting with it. Inheritance allows classes to be derived from other classes, inheriting their attributes and methods. Polymorphism allows objects to be used interchangeably, even if they belong to different classes, as long as they share a common interface.

By using OOP, developers can write code that is more modular, maintainable, and extensible. OOP is widely used in modern programming languages such as
Python, Java, and C++.


## Outline

* [Introduction to Object-Oriented Programming](https://github.com/LaughingRover/Python-Intro/blob/main/Day%203%3A%20Object-Oriented%20Programming.md#introduction-to-object-oriented-programming)
* [Classes, Objects, and Methods](https://github.com/LaughingRover/Python-Intro/blob/main/Day%203%3A%20Object-Oriented%20Programming.md#classes-objects-and-methods)
* [Constructors and Destructors](https://github.com/LaughingRover/Python-Intro/blob/main/Day%203%3A%20Object-Oriented%20Programming.md#constructors-and-destructors)
* [Inheritance and Polymorphis](https://github.com/LaughingRover/Python-Intro/blob/main/Day%203%3A%20Object-Oriented%20Programming.md#inheritance-and-polymorphism)

## Introduction to Object-Oriented Programming

Introduction to Object-Oriented Programming (OOP) refers to the process of
learning the basic concepts, principles, and techniques of programming in an
object-oriented paradigm.

OOP is a programming paradigm that emphasizes the use of objects, classes, and inheritance to organize and structure code. In OOP, programs are designed and implemented as collections of objects that interact with each other to perform a specific task.

The key concepts of OOP include objects, classes, methods, inheritance, encapsulation, and polymorphism. Objects are instances of classes, which are templates that define the properties and behavior of objects. Methods are functions that are associated with objects and allow them to perform specific tasks. Inheritance allows classes to be derived from other classes, inheriting their attributes and methods. Encapsulation involves hiding the implementation details of an object and providing a well-defined interface for interacting with it. Polymorphism allows objects to be used interchangeably, even if they belong to different classes, as long as they share a common interface.

By learning OOP, developers can write code that is more modular, maintainable, and extensible. OOP is widely used in modern programming languages such as Python, Java, and C++. Understanding OOP is an essential skill for any developer who wants to build scalable and robust software systems.


## Classes, Objects, and Methods

Classes, objects, and methods are the fundamental building blocks of object-oriented programming.

A class is a blueprint or template for creating objects. It defines the attributes and methods that objects of that class will have. For example, a class might define the attributes of a car, such as its make, model, and color, as well as methods for starting the engine, changing gears, and braking.

An object is an instance of a class. It is created using the blueprint provided by the class and can be thought of as a specific realization of that blueprint. For example, an object might be an instance of the car class, with specific values for its make, model, and color attributes.


Methods are functions that are associated with objects and allow them to perform specific tasks. They are defined in the class and are used to manipulate the attributes of objects or perform operations on them. For example, a method in the car class might be used to accelerate the car or turn on its headlights.

Together, classes, objects, and methods provide a powerful way to organize and structure code in an object-oriented paradigm. They allow developers to build complex systems that are easier to understand, maintain, and extend over time.


## Constructors and Destructors

Constructors and destructors are special methods in object-oriented programming that are used to create and destroy objects.

A constructor is a special method that is called when an object is created. It is used to initialize the object's attributes and perform any other setup that needs to be done. Constructors are defined with the same name as the class and are typically used to set default values for the object's attributes. In Python, the `__init__()` method is used to define a constructor.

A destructor, on the other hand, is a special method that is called when an object is destroyed or goes out of scope. It is used to free up any resources that the object was using, such as memory or file handles. Destructors are defined with the name `__del__()` in Python.


While constructors are automatically called when an object is created, destructors are automatically called when an object is no longer needed and is being removed from memory. In Python, the garbage collector automatically calls the destructor when an object is no longer being used.

Constructors and destructors are important concepts in object-oriented programming because they allow developers to control the lifecycle of objects and ensure that resources are properly managed. By using constructors to initialize objects and destructors to free up resources, developers can create more robust and reliable software systems.


## Inheritance and Polymorphism

Inheritance and polymorphism are two important concepts in object-oriented programming.

Inheritance is a mechanism that allows a class to inherit the properties and methods of another class. The class that inherits from another class is called a subclass or derived class, while the class that is being inherited from is called the superclass or base class. The subclass can then add its own properties and methods or override the methods of the superclass. Inheritance allows for code reuse, as developers can create new classes that build on the functionality of existing classes.


Polymorphism, on the other hand, is the ability of objects to take on different forms. This means that objects of different classes can be used interchangeably if they share a common superclass. Polymorphism is achieved through inheritance, where the subclass can override the methods of the superclass to provide its own implementation. This allows developers to write code that works with objects of different classes, as long as they share a common interface or superclass.

Together, inheritance and polymorphism allow developers to create complex object-oriented systems that are easier to understand, maintain, and extend over time. They provide a powerful way to organize and structure code, as well as promote code reuse and flexibility.


## Exercise

1. Create a class called `Person` with attributes `name`, `age`, and `gender`. Add a method to the class called `speak` that prints out the message "Hello, my name is [name] and I am [age] years old."
2. Create a class called `Rectangle` with attributes `width` and `height`. Add a method to the class called `area` that returns the area of the rectangle.
3. Create a class called `Animal` with attributes `species` and `sound`. Add a method to the class called `make_sound` that prints out the sound the animal makes. Create a subclass called `Dog` that has an
additional attribute called `name`. Override the `make_sound` method in the `Dog` class to print out the message "Woof, my name is [name]."

4. Create a class called `BankAccount` with attributes `balance` and
`interest_rate`. Add methods to the class called `deposit` and `withdraw` that adjust the account balance accordingly. Add a method called `add_interest` that increases the account balance based on the interest rate.
5. Create a class called `Shape` with a method called `draw` that prints out the message "Drawing a shape." Create a subclass called `Circle` that overrides the `draw` method to print out the message "Drawing a circle." Create a subclass called `Square` that overrides the `draw` method to print out the message "Drawing a square."

