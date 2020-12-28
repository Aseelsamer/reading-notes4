### Name 3 advantages to Test Driven Development?
1. Better program design and higher code quality
2. Detailed project documentation
3. TDD reduces the time required for project development


### In what case would you need to use beforeEach() or afterEach() in a test suite?
If you have some work you need to do repeatedly for many tests, you can use beforeEach and afterEach.

beforeEach and afterEach can handle asynchronous code.


### What is one downside of Test Driven Development?

It’s difficult to write good tests that cover the essentials and avoid the superfluous.


### What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

The most important difference between class- and prototype-based inheritance is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.


### Name a use case for a static method?
used for the functionality that belongs to the class “as a whole”


### Write an example of a Higher Order function and describe the use case it solves?
const double = n => n * 2

[1, 2, 3, 4].map(double) // [ 2, 4, 6, 8 ]

 the map function on arrays is a higher order function. The map function takes a function as an argument.


 
 ## Document the following Vocabulary Terms

functional programming:is a programming paradigm where programs are constructed by applying and composing functions. It is a declarative programming 


pure function:A pure function is a function which:
Given the same input, will always return the same output.
Produces no side effects.


higher-order function: it takes one or more functions as arguments (i.e. procedural parameters),
returns a function as its result.


immutable state: is state that cannot be changed.


object:An entity that has state and behavior is known as an object e.g., chair, bike, marker, pen, table, car, etc. It can be physical or logical 


object-oriented programming (OOP):is a programming paradigm based on the concept of "objects", which can contain data and code: data in the form of fields (often known as attributes or properties), and code, in the form of procedures (often known as methods).


A Class is like an object constructor, or a "blueprint" for creating objects.


prototype:is a creational design pattern that allows cloning objects, even complex ones, without coupling to their specific classes. 


super:The most common use of the super keyword is to eliminate the confusion between superclasses and subclasses that have methods with the same name.


inheritance:can be defined as the process where one class acquires the properties (methods and fields) of another.


constructor:is a special method that is used to initialize objects. The constructor is called when an object of a class is created.


instance:variables in Java are non-static variables which are defined in a class outside any method, constructor or a block. 


context:represents your environment. It represents the state surrounding where you are in your system.

this:The this keyword refers to the current object in a method or constructor. 


Test Driven Development (TDD): is a software development process which includes test-first development.

Jest: provides an implementation of the Elasticsearch REST API.


Continuous Integration (CI):is one of the cornerstones of the DevOps revolution. 


unit test:means testing the smaller units of your application, like classes and methods. ... Unit tests are typically automated, meaning once they are implemented, you can run them again and again. 
