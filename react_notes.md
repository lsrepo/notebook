# Notes for learning React

### Aha
Using getInitialState or a constructor to initialize a state property

In the end, props represent "read-only" data that are immutable.

### Terms
props
 > refer to attributes from parent components

state 
> is managed internally by the component itself and is meant to change over time, commonly due to user input (e.g., clicking on a button on the page).

Reconciliation / 和解，對賬 
> the process of determining what has changed in the previous and new 

Object Destructuring
> { x } = this.props
> Because props and state are just JavaScript objects, we can use an ES6 feature to unpack them into distinct variables rather than referencing them as this.state.query and this.props.contacts every time. 


### Core concepts
UI = fn(state)
> UI is a function of your state.
> One state changes, the component will be re-rendered.

Controlled Component
> the source of truth for that form state lives inside the component rather than inside of the DOM



### Helpers

trim
> remove space in a string

JSON.stringfy()
> view values of a string