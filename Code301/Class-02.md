# State and Props

[Home](../index.md)

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Render occurs before the componentDidMount

2. What is the very first thing to happen in the lifecycle of React?
The very first item in the react lifecycle is the constructor is called in the mount section

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
Constructor, render, React Updates, componentDidMount, ComponentWillUnmount

4. What does componentDidMount do?
"componentDidMount" is a method that is called after a component has successfully mounted. You can customize the behaviour of a component here to do things such as load a network requrest or initialize a DOM.

The bottom line is there are many predetermined steps and customizable methods to allow your interaction with React Componenets to be an efficient and effective way to build websites.

## State vs Props

1. What types of things can you pass in the props?
Paremeters that you want you component to have, such as an initial value for a counter, a name for a person, a title/subitle for the component  etc.

2. What is the big difference between props and state?
State is something inside a component, that is, props is something you pass into the component and state is something you handle inside the component. This reflects what is going on in the component.

3. When do we re-render our application?
When the state is changed!

4. What are some examples of things that we could store in state?
We could store a counter, an image that changes, items in a form, or anything that needs to be re-rendered and updated according to actions taken by the user.
