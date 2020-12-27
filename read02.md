## Why would you want to run JavaScript code outside of a browser?


I would like to run my code on the terminal so i can see my console logs clearly and understand what I am doing , for me it is better .


## What is the difference between a module and a package?
A ***module*** is a single file (or files) that are imported under one import and used. 


A ***package*** is a collection of modules in directories that give a package hierarchy.


## What does the node package manager do?
**NPM** is a command line tool that installs, updates or uninstalls Node. js packages in your application. It is also an online repository for open-source Node.


## Provide code snippets showing 3 different ways to export a function from a node module ?
1- module.exports 

Example : module.exports ='Hello World';


2-Export Function as a Class

Example :

module.exports = function (firstName, lastName) {


    this.firstName = firstName;


    this.lastName = lastName;


    this.fullName = function () { 


        return this.firstName + ' ' + this.lastName;


    }


}




### Vocab terms :

ecosystem:  is a collection of software packages, libraries, and other resources that facilitate development as they integrate with each other.


Node.js:is a JavaScript runtime built on Chrome's V8 JavaScript engine.



V8 Engine:V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++


A module is a single file (or files) that are imported under one import and used. 


A package is a collection of modules in directories that give a package hierarchy.


node package manager (npm):is a command line tool that installs, updates or uninstalls Node. js packages in your application.


server: makes your app available to serve HTTP requests. It provides the interaction between users and your application.


environment:If you are running your JS program using Node. js from the terminal, then Node defines the environment - what all libraries and default objects are available to you. 


interpreter in the browser reads over the JavaScript code, interprets each line, and runs it.


compiler translates the program into bytecode that the machine understands and can execute.