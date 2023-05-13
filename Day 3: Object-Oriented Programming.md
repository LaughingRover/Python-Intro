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

Here's an example code that demonstrates the concept of classes, objects, and methods in Python:

```
class Car:
    def __init__(self, make, model, color):
        self.make = make
        self.model = model
        self.color = color
        self.speed = 0

    def accelerate(self, amount):
        self.speed += amount

    def brake(self, amount):
        self.speed -= amount

my_car = Car("Toyota", "Corolla", "blue")
my_car.accelerate(10)
print(my_car.speed)
my_car.brake(5)
print(my_car.speed)
```

In this code, we define a class called `Car` that has attributes for `make`, `model`, `color`, and `speed`. The `__init__` method is the constructor that is called when a new `Car` object is created. It initializes the object's attributes with the provided values.

The `accelerate` and `brake` methods are used to manipulate the `speed` attribute of the `Car` object. They increase or decrease the speed by the provided amount.

We create a new `Car` object called `my_car` with the `make` "Toyota", `model` "Corolla", and `color` "blue". We then call the `accelerate` method with an amount of 10, which increases the `speed` attribute of the `my_car` object to 10. We print the `speed` attribute to confirm this. We then call the `brake` method with an amount of 5, which decreases the `speed` attribute to 5. We print the `speed` attribute again to confirm this.

This code demonstrates how we can use classes, objects, and methods to create and manipulate objects in Python.

## Constructors and Destructors

Constructors and destructors are special methods in object-oriented programming that are used to create and destroy objects.

A constructor is a special method that is called when an object is created. It is used to initialize the object's attributes and perform any other setup that needs to be done. Constructors are defined with the same name as the class and are typically used to set default values for the object's attributes. In Python, the `__init__()` method is used to define a constructor.

A destructor, on the other hand, is a special method that is called when an object is destroyed or goes out of scope. It is used to free up any resources that the object was using, such as memory or file handles. Destructors are defined with the name `__del__()` in Python.


While constructors are automatically called when an object is created, destructors are automatically called when an object is no longer needed and is being removed from memory. In Python, the garbage collector automatically calls the destructor when an object is no longer being used.

Constructors and destructors are important concepts in object-oriented programming because they allow developers to control the lifecycle of objects and ensure that resources are properly managed. By using constructors to initialize objects and destructors to free up resources, developers can create more robust and reliable software systems.

Here's an example of a Python class that uses a constructor to initialize object attributes:

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def introduce(self):
        print(f"Hi, my name is {self.name} and I'm {self.age} years old.")

person1 = Person("Alice", 30)
person1.introduce() # Output: Hi, my name is Alice and I'm 30 years old.

person2 = Person("Bob", 25)
person2.introduce() # Output: Hi, my name is Bob and I'm 25 years old.
```

In this example, we define a `Person` class with a constructor that takes two arguments (`name` and `age`) and initializes the `name` and `age` attributes of the object. We also define an `introduce` method that prints out a message introducing the person.

We then create two `Person` objects, `person1` and `person2`, using the constructor with different arguments. We call the `introduce` method on each object to print out their respective names and ages.

Here's an example of a Python class that uses a destructor to free up resources:

```python
class FileHandler:
    def __init__(self, filename):
        self.file = open(filename, "r")

    def read_contents(self):
        return self.file.read()

    def __del__(self):
        self.file.close()

file_handler = FileHandler("myfile.txt")
contents = file_handler.read_contents()
print(contents)
# Output: Contents of the file

# When the file_handler object goes out of scope or is no longer needed,
# the __del__ method is automatically called, which closes the file.
```

In this example, we define a `FileHandler` class with a constructor that takes a `filename` argument and opens the file in read mode. We also define a `read_contents` method that returns the contents of the file.

We then create a `FileHandler` object, `file_handler`, passing in the name of a file to read. We call the `read_contents` method to retrieve the contents of the file and print it out.

When the `file_handler` object is no longer needed, the Python garbage collector automatically calls the `__del__` method, which closes the file to free up any resources used by the object.


## Inheritance and Polymorphism

Inheritance and polymorphism are two important concepts in object-oriented programming.

Inheritance is a mechanism that allows a class to inherit the properties and methods of another class. The class that inherits from another class is called a subclass or derived class, while the class that is being inherited from is called the superclass or base class. The subclass can then add its own properties and methods or override the methods of the superclass. Inheritance allows for code reuse, as developers can create new classes that build on the functionality of existing classes.


Polymorphism, on the other hand, is the ability of objects to take on different forms. This means that objects of different classes can be used interchangeably if they share a common superclass. Polymorphism is achieved through inheritance, where the subclass can override the methods of the superclass to provide its own implementation. This allows developers to write code that works with objects of different classes, as long as they share a common interface or superclass.

Together, inheritance and polymorphism allow developers to create complex object-oriented systems that are easier to understand, maintain, and extend over time. They provide a powerful way to organize and structure code, as well as promote code reuse and flexibility.

Here's an example of inheritance and polymorphism in Python:

```
class Animal:
    def __init__(self, name):
        self.name = name
    
    def speak(self):
        pass

class Dog(Animal):
    def speak(self):
        return "Woof!"

class Cat(Animal):
    def speak(self):
        return "Meow!"

def animal_speak(animal):
    print(animal.speak())

my_dog = Dog("Fido")
my_cat = Cat("Fluffy")

animal_speak(my_dog)  # Output: "Woof!"
animal_speak(my_cat)  # Output: "Meow!"
```

In this example, we have a superclass `Animal` that has an attribute `name` and a method `speak()`. The `speak()` method is defined as a placeholder method that does nothing. We also have two subclasses `Dog` and `Cat` that inherit from the `Animal` superclass. These subclasses override the `speak()` method of the `Animal` superclass to provide their own implementation.

We then have a function `animal_speak()` that takes an `Animal` object as a parameter and calls its `speak()` method. This function can take either a `Dog` object or a `Cat` object as a parameter because both subclasses inherit from the `Animal` superclass and have a `speak()` method.

Finally, we create a `Dog` object `my_dog` and a `Cat` object `my_cat`, and pass them to the `animal_speak()` function to see how they "speak". Because of polymorphism, the `animal_speak()` function works with both `Dog` and `Cat` objects, even though they have different implementations of the `speak()` method.

## Exercise

1. Create a class called `Person` with attributes `name`, `age`, and `gender`. Add a method to the class called `speak` that prints out the message "Hello, my name is [name] and I am [age] years old."
2. Create a class called `Rectangle` with attributes `width` and `height`. Add a method to the class called `area` that returns the area of the rectangle.
3. Create a class called `Animal` with attributes `species` and `sound`. Add a method to the class called `make_sound` that prints out the sound the animal makes. Create a subclass called `Dog` that has an
additional attribute called `name`. Override the `make_sound` method in the `Dog` class to print out the message "Woof, my name is [name]."

4. Create a class called `BankAccount` with attributes `balance` and
`interest_rate`. Add methods to the class called `deposit` and `withdraw` that adjust the account balance accordingly. Add a method called `add_interest` that increases the account balance based on the interest rate.
5. Create a class called `Shape` with a method called `draw` that prints out the message "Drawing a shape." Create a subclass called `Circle` that overrides the `draw` method to print out the message "Drawing a circle." Create a subclass called `Square` that overrides the `draw` method to print out the message "Drawing a square."

