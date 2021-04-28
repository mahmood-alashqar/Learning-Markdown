# What are component lifecycle events?
## React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

# 1- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

### Render()

# 2- What is the very first thing to happen in the lifecycle of React?

### Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

# 3- What does componentDidMount do?

### load anything using a network request or initialize the DOM

//////////////////////////////////////
 # 1- What types of things can you pass in the props?
 ### Arguments
# 2- What is the big difference between props and state?
### props : handle the data inside the component and must be updated outside the component.
### state : it works just inside the component.
# 3- When do we re-render our application?
### when the state changed
# 4- What are some examples of things that we could store in state?
### counters,forms , .etc  about what users input