## Explain what a “Singleton” is (in Computer Science terms) ?
 the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. 

## Explain how the Singleton pattern can be used with Node modules, specifically with classes

Singletons are used to create an instance of a class if it does not exist or else return the reference of the existing one. This means that singletons are created exactly once during the runtime of the application in the global scope. 

## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

creating and deleting tasks (CRUD METHODS).

------------------------------------------------
# Term :

Router Middleware : Middleware (and method handlers) are functions that follow specific function parameters and have defined behavior when used with router . The most common format is with three parameters - "req", "res" and "next".

Dynamic Module Loading : This allows you to dynamically load modules only when they are needed, rather than having to load everything up front.
 Benefits of module loading is -->  code is easier to write and easier to optimise, and faster to load .

Singleton Pattern :this design pattern restricts instantiation of a class to just one object .

CRUD -> REST Method Matches : checks if the element "is" the selector.
CRUD (Create, Read, Update, Delete) is an acronym for ways one can operate on stored data.

Mock Testing: Mock functions allow you to test the links between code by erasing the actual implementation of a function, capturing calls to the function.