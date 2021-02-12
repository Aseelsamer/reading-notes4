# Review, Research, and Discussion


### What are the advantages of storing tokens in “Cookies” vs “Local Storage” ?

-In the Local Storage tokens are stored in the header.

-In Cookies it's automatically sent in every HTTP request to your server.


### Explain 3rd party cookies.

Third-party cookies are created by domains that are not the website (or domain) that you are visiting. These are usually used for online-advertising purposes and placed on a website through adding scripts or tags. A third-party cookie is accessible on any website that loads the third-party server's code


### How do pixel tags work?

 tracking pixel is a graphic with dimensions of 1x1 pixels that is loaded when a user visits a webpage or opens an email.The tracking pixel URL is the memory location on the server. 

# Document the following Vocabulary Terms

### cookies : are data, stored in small text files, on your computer.


### authorization :The HTTP Authorization request header contains the credentials to authenticate a user agent with a server.


### access control :Role and Attribute based Access Control for Node.js.


### conditional rendering : is a term to describe the ability to render different user interface (UI) markup if a condition is true or false.


-------------------------------------------------------------------

# Preview 

Redux is a predictable state container for JavaScript apps.
Redux will efficiently manage your overall application state. Like a bank vault, it’s got a store to do that.

***Redux is a pattern and library for managing and updating application state, using events called "actions"***

Redux helps you manage "global" state - state that is needed across many parts of your application.


Redux is more useful when:

1-You have large amounts of application state that are needed in many places in the app
2-The app state is updated frequently over time
3-The logic to update that state may be complex
4-The app has a medium or large-sized codebase, and might be worked on by many people



- the reducer is a pure function that takes the previous state and an action, and returns the next state.You can think of a reducer as an event listener which handles events based on the received action (event) type.


