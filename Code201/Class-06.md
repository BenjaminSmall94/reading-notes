# Object Literals and the Document Object Model

[Home](../index.md)

## Javascript and JQery

### Chapter 3 (Part 2): Object Literals

Objects are sets of variables and functions grouped together to represent something meaningful, typically modeled after real (non-virtual) world concepts or physical objects. When placed into an object, variables become properties and functions become methods. The names of properties and functions also refered to as keys. Together they encapsulate the state and behavior of the object.

#### Creating an Object (Literal Notation)

One way to create objects is to set a variable equal to curly braces with the object contents inside the curly brackets. Keys are separated from their values with colons and each item is dilineated witha comma.

#### Accessing Data/Methods in Objects

You can either use the dot/member notation (eg`this.property` or `this.method()`) to access variables or functions with objects or you can use square bracket notation to access only the variables (eg `this['property']).

### Chapter 5: Document Object Model

The Document Object Model (DOM) is not a part of HTML or JavaScript. It is implemented by all major browsers and describes how browsers make a model of an HTML page as well as access and change the HTML page after it is constructed. When constructing the page, the DOM uses a DOM tree made of objects to represent a different part of the webpage that is loaded into the browsers. The DOM also defined methods and properties to access all of these objects in order to alter what the user sees in the browser.

#### Structure of the DOM

Before you alter any items you need to find its node from within the tree. The tree is structured just like a family tree with Parents, Children, Siblings, and acestors of various degrees. Text nodes are stored in the DOM as children of their containing HTML elements. Text nodes cannot have children, only siblings.

#### Accessing Nodes (Elements) within the DOM

Whenever you query for an item, the interpreter must search the entire DOM for the corresponding element. Therefore it is wise to store reference to this locating in a variable to save the interpreter and the CPU time.

##### Individual Elements

1. `getElementbyId();` use a nodes unique ID value
2. `querySelector();` find the first matching element based on CSS selectors
3. Select an indiviual element by taversing from one element to another by traversing the DOM tree (eg `parentNode`, `previousSibling/nextSibling`, and `firstChild/LastChild`)

##### Multiple Nodes

1. `getElementsByClassName();`
2. `getElementsByTagName();` select all elements of a certain tag type
3. `querySelectorAll();` select all elements that match the CSS selector

These methods will always return a nodeList even if they only find one item. In live NodeLists, the NodeList is updated any time the script updates the DOM. The opposite is true for static NodeLists. In order to access a single item from a NodeList you can either use the `item()` method or array notation.

#### Working with Nodes

1. `nodeValue`
2. `innerHTML`
3. `textContent`
4. `createElement()`
5. `createTextNode()`
6. `appendChild()`
7. `removeChild()`

##### Common Attributes and Methods of Nodes

1. `className`
2. `Id`
3. `hasAttribute()`
4. `getAttribute()`
5. `setAttribute()`
6. `removeAttribute()`

#### Altering HTML

When altering HTML you can either use the `innterHTML` property, or you can create objects manipulating the DOM model. Using the HTML direct can be faster an easier, but is less secure when in comes to user input.

## Things I want to know more about

I just want practice using the innerHTML and DOM. Also I want to know more about securing my webisite on the server and client side to malicious attacks.
