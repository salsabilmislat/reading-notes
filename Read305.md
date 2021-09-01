# What we will learn

 - Thinking in React



The source of this summary [The first link](https://reactjs.org/docs/thinking-in-react.html)

______________________________________

## Thinking in React

**How would you break a mock into a component heirarchy?**

we will draw boxes around every component (and subcomponent) in the mock and give them all names. After that Components that appear within another component in the mock should appear as a child in the hierarchy.

**What is the single responsibility principle and how does it apply to components?**

 It is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality.

 a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

**What does it mean to build a ‘static’ version of your application?**

To build a static version of your app that renders your data model. It is building components that reuse other components and pass data using props

**Once you have a static application, what do you need to add?**

Identify The Minimal Representation Of UI State

**What are the three questions you can ask to determine if something is state?**

1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

**How can you identify where state needs to live?**

1. Identify every component that renders something based on that state.

2. Find a common owner component (a single component above all the components that need the state in the hierarchy).

3. Either the common owner or another component higher up in the hierarchy should own the state.

4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.