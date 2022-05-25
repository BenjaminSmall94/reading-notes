# React and Forms

[Home](../index.md)

## React Docs - Forms

1. What is a ‘Controlled Component’?
A form input or similar component that inherently has state but who's state is controlled by the React component state property.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
You should update the state as soon as the user inputs change into the element. This way we ensure the React state property is the single source of truth regarding your page and allows you to pass the actual current state to other UI elements and effectively manipulate it within event handlers.

3. How do we target what the user is entering if we have an event handler on an input field?
We put an onChange event with a callback function that then references the new value from the event object in the linked callback function.

## Conditional (Ternary) Operator

1. Why would we use a ternary operator?
To shorten our code into a more efficient concise line of code.

2. Rewrite the following statement using a ternary statement:
  
   ```JavaScript
    x === y ? true : false
   ```

Ternary operators are a very useful tool for writing concise code and can be nested in eachother for a more versatile output.

## React-Bootstrap Forms

Bootstrap provides a nicely formatted form item with many nice features included in its API [Bootstrap](https://react-bootstrap.github.io/forms/overview/)

## Conditional Rendering

There are many cool ways to force code to be displayed or not with either functions or inline operators. More information can be found [Here](https://reactjs.org/docs/conditional-rendering.html)

## Things I want to know more about

I just want practice doing it. Bootstraps is a pretty cool tool that I'll just need to build familiarity with.
