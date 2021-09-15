# What we will learn

- Component Lifecycle Events

- State and Props

The source of this summary [The first link](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

The source of this summary [The second link](https://www.youtube.com/watch?v=IYvD9oBCuJI)
______________________________________

## Component Lifecycle Events

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

The render happens first then the componentDidMount

**What is the very first thing to happen in the lifecycle of React?**

>React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

in another word The constructor for a React component is called then an instance of a component will be created and inserted into the DOM.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.**

1. constructor

2. render

3. React Updates

4. componentDidMount

5. componentWillUnmount

**What does componentDidMount do?**

help you load anything using a network request or initialize the DOM, also a good place to set up any subscriptions . we can use it to connect to the YouTube API and get videos when the components is rendered.

______________________________________

## State and Props

**What types of things can you pass in the props?**

props it is like argument to a function , so when we create component in react it will pass props that we would give it .
when we want to display something for the user and it is static not changeable

**What is the big difference between props and state?**

the props you can pass it into a component and it is update outside the component

the state are handled inside a component also updated inside the component

**When do we re-render our application?**

whenever there is a change in their state or props. it will be re-rendered automatically.

**What are some examples of things that we could store in state?**
if it is not a static data and you want to update it to the user.

## Things I want to know more about

to do a real example of react component using with it props and state.
