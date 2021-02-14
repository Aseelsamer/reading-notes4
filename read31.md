# Review, Research, and Discussion


### Why choose Redux instead of the Context API for global state?

-Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity.


### What is the purpose of a reducer?

- reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.


### What does an action contain?

- actions are plain JavaScript object that must have a type attribute to indicate the type of action performed


### Why do we need to copy the state in a reducer?

-making a copy is a way to describe the unchanged part.


# Document the following Vocabulary Terms

***immutable state ***: 
Immutability is a concept that React programmers need to understand. An immutable value or object cannot be changed, so every update creates new value, leaving the old one untouched.‏


***time travel in redux*** :A scalable undo redo time travel implementation that leaves your original state powered by diffs and merges.
 
An ***action*** creator is merely a function that returns an action object.

A ***reducer*** is a function that determines changes to an application's state.

***dispatch*** : is a function of the Redux store used to dispatch an action.

---------------------------------------------------------------------

# Preview

CombineReducers is simply a utility function to simplify the most common use case when writing Redux reducers. You are not required to use it in your own application, and it does not handle every possible scenario. It is entirely possible to write reducer logic without using it, and it is quite common to need to write custom reducer logic for cases that combineReducer does not handle.

The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

Returns(Function): A reducer that invokes every reducer inside the reducers object, and constructs a state object with the same shape.


