# Review, Research, and Discussion
In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

## How granular should your reducers be?

-Reducer functions should only depend on their state and action arguments, and ... subscribed to the Redux store and reading data at a more granular level.


## Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched



# Document the following Vocabulary Terms

***store*** :A store is a state container which holds the application's state. Redux can have only a single store in your application. Whenever a store is created in Redux, you need to specify the reducer


***combined reducers*** : combine multiple reducers into one that can be passed into createStore by using a helper function named combineReducers . The way we combine reducers is simple, we create one file per reducer in the reducers directory. 

---------------------------------------------------------------------


# Preview

Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the function’s body once the asynchronous operations have been completed.

The most common use case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data. Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API.

By itself, a Redux store doesn't know anything about async logic. It only knows how to synchronously dispatch actions, update the state by calling the root reducer function, and notify the UI that something has changed. Any asynchronicity has to happen outside the store.

Earlier, we said that Redux reducers must never contain "side effects". A "side effect" is any change to state or behavior that can be seen outside of returning a value from a function

