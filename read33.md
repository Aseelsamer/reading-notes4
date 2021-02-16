# Review, Research, and Discussion


### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

-it's simple to get access to the store inside a React component – no need to pass the store as a prop or import it, just use the connect function from React Redux, and supply a mapStateToProps function that pulls out the data you need


### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

- Each lifecycle action creator will be attached to the returned thunk action creator so that your reducer logic can reference the action types and respond to the actions when dispatched.

# Document the following Vocabulary Terms

***middleware*** : Middleware functions are functions that have access to the request object ( req ), the response object ( res ), and the next function in the application's request-response cycle.


***thunk*** :middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met.

-------------------------------------------------------------------------------------------

# Preview 

-The Redux Toolkit package is intended to be the standard way to write Redux logic.

This package will include :

***configureStore()***:  It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and **enables use of the Redux DevTools Extension.**

***createReducer()***: that lets you supply a lookup table of action types to case reducer functions, rather than writing switch statements.


***createAction()***: generates an action creator function for the given action type string.


-Installation : npx create-react-app my-app --template redux OR npm install @reduxjs/toolkit





