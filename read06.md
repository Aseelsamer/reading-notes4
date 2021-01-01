# Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.

-Linux Gaming 
An operating system based on the Linux kernel and customized specifically for gaming, could adopt the vanilla Linux kernel with only little changes, or—like the Android operating system—be based on a relative extensively modified Linux kernel. It could adopt GNU C Library or Bionic or something like it. The entire middleware or parts of it, could very well be closed-source and proprietary software; the same is true for the video games. There are free and open-source video games available for the Linux operating system, as well as proprietary ones.


# What is the advantage of an ORM, like Mongoose?
-They write correct and optimized SQL queries, thereby eliminating the hassle for developers
-They make the code easier to update, maintain, and reuse as the developer can think of, and manipulate data as objects
-ORMs will shield your application from SQL injection attacks since the framework will filter the data for you!
-ORMs provide the concept of Database Abstraction which makes switching databases easier and creates a consistent code base for your application.

# How does the repository pattern compare with an ORM?

-Now with the Repository pattern i'd had to create a repository for each thing you have. The repository also needs all kinds of functions to retrieve data for me and to store it. Plus it needs to work with Entity models.

but for the ORM if you have tables for example you put them in a model file And i could store it just as easy.

# When making a repository/facade, what flexibility do you gain?

-You can reduce the entangling or coupling of the application with the persistence code by making sure that all persistence activities happen behind the facade.

# Name 3 cloud based NoSQL Databases
-MoongoDb
- Java
-DynamoDB

----------------------------------------------------

# Term 

lifecycle: 
-Lifecycle of Components
Each component in React has a lifecycle which you can monitor and manipulate during its three main phases.
The three phases are: Mounting, Updating, and Unmounting.


collections:A Set is a collection of unique elements that can be of any type. Set is also an ordered collection of elements, which means that elements will be retrieved in the same order that they were inserted in.

the “Repository” design pattern:In using the Repository design pattern, you can hide the details of how the data is eventually stored or retrieved to and from the data store. This data store can be a database, an xml file, etc. You can apply this design pattern to even hide how data that is exposed by a web service or an ORM is accessed

mongoose middleware:are functions which are passed control during execution of asynchronous functions. Middleware is specified on the schema level and is useful for writing plugins.

Object Relation Mapping (ORM):it’s a technique that allows us to query and change data from the database in an object oriented way.
