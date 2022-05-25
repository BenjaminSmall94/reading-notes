# Putting it all Together

[Home](../index.md)

## React Docs - Thinking in React

1. What is the *single responsibility principle* and how does it apply to components?
   A Component should really only do one thing. If it grows beyond that, it should be divided into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application?
   Build a version of your website with zero interactivity. Which also means, with no 'state'.

3. Once you have a static application, what do you need to add?
   You need to add state and interactivity.

4. What are the three questions you can ask to determine if something is state?
   - Is it passed in from a parent via props? If so, it probably isn’t state.
   - Does it remain unchanged over time? If so, it probably isn’t state.
   - Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?
   - Identify every component that renders something based on that state.
   - Find a common owner component (a single component above all the components that need the state in the hierarchy).
   - Either the common owner or another component higher up in the hierarchy should own the state.
   - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions

1. What is a “higher-order function”?
   A function that operates on or references other functions, either by taking them as arguments or returning them are *higher-order functions*. They benefit developers by allowing them to abstract actions that are repetitive and common.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this.function doing?
   I had to stare at that one for a while. The greater than function returns an anonymous function that compares one number (via the greater than operator) to another number defined by the user as a parameter during the function creatiion.

3. Explain how either map or reduce operates, with regards to higher-order functions.
   The map function works by taking in a callback function as a parameter with instruction to manipulate and copy every items in one array to another in a very particular way

## Things I want to know more about

I want to know more about the reduce function mentioned in question 3 of the higher order functions section. I do not know what that does.
