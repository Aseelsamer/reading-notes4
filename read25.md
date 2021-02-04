# Review, Research, and Discussion

## Why do we not need more .html pages in a multi-page React app?

-Because React is not designed to develop multi-page websites. So, we need to create multiple routes to handle multiple views.


## If we wanted a component to show up on every page, where would we put it and why?

Inside the <BrowserRouter />
inside the browserRouter with nav tag .



## What does props.children contain?

this.props.children can have one element, multiple elements, or none at all, its value is respectively a single child node, an array of child nodes or undefined.

------------------------------------------------
# Document the following Vocabulary Terms

### Composition :

is a natural pattern of the component model. It's how we build components from other components, of varying complexity and specialization through props.


### Children / Child Components :

components use the special children prop to pass children elements directly into their output.


### Hash Routing:

routing is using the anchor part of the URL to simulate different content.

### Link Routing:

it  is a dynamic routing algorithm in which each router shares knowledge of its neighbors with every other router in the network.

------------------------------------------------

# Preview

 -Hooks let us organize the logic inside a component into reusable isolated units.

 -Hooks apply the React philosophy (explicit data flow and composition) inside a component, rather than just between the components.

 -If the React community embraces the Hooks proposal, it will reduce the number of concepts you need to juggle when writing React applications. Hooks let you always use functions instead of having to constantly switch between functions, classes, higher-order components, and render props.



 -When would I use a Hook? If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component. 

 
 -What does calling useState do? It declares a “state variable”.


 -What does useState return? It returns a pair of values: the current state and a function that updates it.

 
 -The Effect Hook, useEffect, adds the ability to perform side effects from a function component. It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount in React classes, but unified into a single API.