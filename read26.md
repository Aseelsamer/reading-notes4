# Review, Research, and Discussion
### What does a component’s lifecycle refer to?

-React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.


### Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect?

-useCallback will help in avoiding regeneration of functions when the functional component re-renders. However there isn't much of a performance difference caused by recreation of functions


### Why are functional components preferred over class components?

-Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks. You end up with less code. They help you to use best practices.

### What is wrong with the following code?
In the render you should add the Fragments.


-------------------------------------------------------------------------------------------
# Document the following Vocabulary Terms

-state hook:useState is a Hook that allows you to have state variables in functional components.


-effect hook:(callback, dependencies) is the hook that manages the side-effects in functional components. callback argument is a function to put the side-effect logic


-reducer hook: It accepts a reducer function with the application initial state, returns the current application state, then dispatches a function.

-------------------------------------------------------------------------------------------
# Preview :

-Custom Hooks are JavaScript functions whose names are prefixed with the word use. A custom Hook is a normal function but we hold them to a different standard. By adding the word use to the beginning, it lets us know that this function follows the rules of Hooks.

-We cannot use 'async' keyword with 'useEffect' callback method. It will result in race conditions.

-useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

-