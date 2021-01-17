# Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?
ticket create, ticket update, and note create .

# Why are events sometimes better than asynchronous actions with callbacks?


# What does an EventEmitter instance do?
ll objects that emit events are instances of the EventEmitter class. These objects expose an eventEmitter. on() function that allows one or more functions to be attached to named events emitted by the object.


# When is a program’s call stack, event queue, and event loop active?
Stack: This is where all your javascript code gets pushed and executed one by one as the interpreter reads your program, and gets popped out once the execution is done.

Callback Queue: This is where your asynchronous code gets pushed to, and waits for the execution.

Event Loop:which keeps running continuously and checks the Main stack, if it has any frames to execute.


# Term
Observer Pattern :bserver pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
‏
Listener: The addEventListener() method attaches an event handler to an element without overwriting existing event handlers .you can add event listeners to any DOM .

Event Handler : Events are actions that occur, usually as a result of something the user does. 

Event Driven Programming : follows mainly a publish-subscribe pattern, ie a class (as an example) communicates with another class with events, not by calling methods directly.

Event Loop :which is responsible for executing the code, collecting and processing events, and executing queued sub-tasks.

Event Queue :A JavaScript runtime uses a message queue, which is a list of messages to be processed.

Call Stack :is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions.

Subscribe :To execute the observable you have created and begin receiving notifications, you call its subscribe() method.

database: is an organized collection of structured information, or data, typically stored electronically in a computer system.