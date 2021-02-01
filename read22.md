# Review, Research, and Discussion

### Can a parent component access the state of a child component?

- you can declare a ref in the parent component, then pass it as a ref attribute to the child .

### What can be passed along in a prop variable?

-it can be passed in a className={}.


### How can a child component “know” the state of another component?

-You need to use a child component in parent's render function in order to pass the state (and even props) of Parent component to its child component


# Term
### component props :

use to transport data from one component to another.

### component state :

The state object is where you store property values that belongs to the component.


### application state :

State is a JavaScript object. It stores a component's dynamic data and determines the component's behavior. In other words, it is the interface between any data of changes (backend or local) and the representation of this data with UI-elements in the frontend.
And there are 5 types of application state.

-------------------------------------------------

# Preview

-A higher-order component is a function that takes a component and returns a new component.
A good use case for an HOC is authorization. You could write your authentication code in every single component that needs it. It would quickly and unnecessarily bloat your code.


-The only way you should change state is via the setState method. This method takes an object and merges it into the current state.


-The React context API allows you to create global context objects that can be given to any component you make. This allows you to share data without having to pass props down all the way through the DOM tree.


-My simple explanation of what this.props.children does is that it is used to display whatever you include between the opening and closing tags when invoking a component.


-Composition is also a familiar concept in Object Oriented Programming. Instead of inheriting properties from a base class, it describes a class that can reference one or more objects of another class as instances.
-When a child class derives properties from it’s parent class, we call it inheritance.

