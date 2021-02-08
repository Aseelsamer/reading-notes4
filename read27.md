# Review, Research, and Discussion

### Describe use cases for useMemo() and useReducer() ?


- we use useMemo , which will save the value to the cache, and will NOT run again during re-renders unless the value of data is changed.

- useReducer is which allows to access state and dispatch actions to your store from your functional components.

### Why do custom hooks need the use prefix?

-So it can use hooks inside of it and contain a common stateful logic to be reused in other components.


### What do custom hooks usually do?

-A custom Hook is a JavaScript function whose name starts with ”use” and that may call other Hooks and it  allows you to extract some components logic into a reusable function.


### Using any list of custom hooks, research and name one that you think will be useful in your applications 


### Describe how a hook that fetches API data might work

-Using useState and useEffect 

This is the process that we need to use for the API call.

1-State variable is ready to store the response data
2-API call happens when the component is mounted
3-Response data is saved to the state variable

# Document the following Vocabulary Terms

reducer:  is a function that determines changes to an application's state. It uses the action it receives to determine this change. 


-------------------------------------------------------------------------------------------

# Preview

Context provides a way to pass data through the component tree without having to pass props down manually at every level.

Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult.

If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.

