# State and Props

[Home](../index.md)

## React Docs - lists and keys

1. What does .map() return?
`map()` returns a new array the same length as the original based on the callback function passed in as a parameter.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
We assign the JSX expressions to an array of elements and the call the new array in the return statement inside curly braces.

3. Each list item needs a unique ____.
Key.

4. What is the purpose of a key?
Keys provide a stable identiy to an element so that React can identify when items are added, removed, or changed without losing reference to the element.

Keys are necessary when rendering an array/list of items within JSX.

## The Spread Operator

1. What is the spread operator?
An operator used to manipulate arrays into function arguments. It's notation is the ellipses `...`. It is used to change an iterable array into a list of arguments for a function.

2. List 4 things that the spread operator can do.

   >- Copying an array
   >- Concatenating or combining arrays
   >- Using Math functions
   >- Using an array as arguments
   >- Adding an item to a list
   >- Adding to state in React
   >- Combining objects
   >- Converting NodeList to an array

3. Give an example of using the spread operator to combine two arrays.

    ```javascript
    const arr1 = [1, 5, 8];
    const arr2 = [2, 6, 10];
    const combinedArr = [...arr1,... arr2]
    ```

4. Give an example of using the spread operator to add a new item to an array.

    ```javascript
    const arr1 = [1, 5, 8];
    const newArr = [...arr1, 3, 22];
    ```

5. Give an example of using the spread operator to combine two objects into one.

    ```javascript
    const obj1 = {objArr: [1, 5, 8]};
    const obj2 = {objArr: [2, 6, 10]};
    const combinedArr = [...arr1,... arr2]
    ```

## How to Pass Functons Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
You define the state in the componenet that manages the state.

2. In your own words, what does the increment function do?
The component updates the state of the person component to `hasChanged = true` then calls the parents increment function with reference to it's own name. The increment component then finds the item that is called and increments the state corresponding to the amount of times it has been called.

3. How can you pass a method from a parent component into a child component?
You can pass it down in the props object.

4. How does the child component invoke a method that was passed to it from a parent component?
Using the props object such as {this.props.increment()}
