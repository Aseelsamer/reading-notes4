# Review, Research, and Discussion

### Do child components have direct access to props/state from the parent?

- we can always pass around functions from the parent to child component. The child component can then make use of these functions.

### When a component “wraps” another component, how does the child component’s output get rendered?

-The wrapped component receives all the props of the container, along with a new prop, data , which it uses to render its output.


### Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?

-No it can't be.


### What trick can a parent use to share all props with it’s children?

-this.props.children 

------------------------------------------------
# Document the following Vocabulary Terms

### props.children :

-is used to display whatever you include between the opening and closing tags when invoking a component.


### composition :

-is a natural pattern of the component model. It's how we build components from other components, of varying complexity and specialization through props.


-----------------------------------------------

# Preview :

React Router v4 is a pure React rewrite of the popular React package.

-Each router creates a history object, which it uses to keep track of the current location 1 and re-render the website whenever that changes.

-Usually it is preferable to use a <BrowserRouter>, but if your website will be hosted on a server that only serves static files, then the <HashRouter> is a good solution.

