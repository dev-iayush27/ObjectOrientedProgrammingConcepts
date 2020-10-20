# Object Oriented Programming Concepts

Object-Oriented Programming or OOPs refers to languages that uses objects in programming. Object-oriented programming aims to implement real-world entities like inheritance, hiding, polymorphism etc in programming. The main aim of OOP is to bind together the data and the functions that operate on them so that no other part of the code can access this data except that function.

## OOPs Concepts:

Class
Object
Polymorphism
Inheritance
Encapsulation
Abstraction


## Class:

- Class is a user-defined data type.
- Class holds its own data members and member functions, which can be accessed and used by creating an instance of that class. 
- A class is like a blueprint for an object.

## Object:

- An Object is an identifiable entity with some characteristics and behaviour. 
- An Object is an instance of a Class. 
- When a class is defined, no memory is allocated but when it is instantiated (i.e. an object is created) memory is allocated.

## Encapsulation: 

- Encapsulation is defined as wrapping up of data and member function in a single unit. 
- Encapsulation is defined as binding together the data and the functions that manipulate them.
- It hides the internal states and functionality of objects.  
- We can achieve this by using the access control features in Swift.

## Abstraction: 

- Abstraction means displaying only essential information and hiding the details. 
- Data abstraction refers to providing only essential information about the data to the outside world, hiding the background details or implementation.
- Handle complexity by hiding unnecessary details from the user.

## Polymorphism:

The word polymorphism means having many forms.

#### Compile Time Polymorphism (Method Overloading):

A function can perform different actions with the same function name but should have different parameters.

#### Run Time Polymorphism (Method Overridding):

It is a concept that allows a subclass or child class to provide a specific implementation of a method that is already provided by one of its superclasses or parent classes.

## Inheritence:

The capability of a class to derive properties and characteristics from another class is called Inheritance.

#### Sub Class: 
The class that inherits properties from another class is called Sub class or Derived Class.

#### Super Class:
The class whose properties are inherited by sub class is called Base Class or Super class.

#### Reusability: 
Inheritance supports the concept of “reusability”, i.e. when we want to create a new class and there is already a class that includes some of the code that we want, we can derive our new class from the existing class. By doing this, we are reusing the fields and methods of the existing class.

### Types of inheritence:

- Single Inheritence
- Multi-level Inheritence
- Multiple Inheritence
- Hierarchial Inheritence
- Hybrid Inheritence
