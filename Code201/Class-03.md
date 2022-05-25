# HTML Lists, JS Control Flow, CSS Box Model

[Home](../index.md)

## HTML & CSS

### Chapter 3: Lists

There are three default types of lists

1. Ordered: `<ol>` uses number to indicate there is signifigance to the order in which items are presented
2. Unordered: `<ul>` uses bullets to indicate ther is no signifigance to the order in which items are presented
3. Definition: `<dl>` consists of a series of terms being defined and contains the `<dt>` tag to indicate the item being defined and the `<dd>` tag to indicate the definition

You can nest lists within other lists and by default this will increase the indent and change the marker type.

### Chapter 13: Boxes

As previously discussed, CSS views all HTML elements as if they were in boxes. We will examine ways to control the dimensions of the boxes, creating border around boxes, seting margins and padding for the boxees, and showing and hiding boxes.

The width and height attributes allow a developer to override the default dimensions of a box. For dynamically sized boxes, you may use the attribute max/max-height/width to determine a maximum value during resizing.

The overflow value tells an element what to do if its contents are bigger than the box, either make the extra content `hidden`or produce a `scroll` bar to see the rest of the content.

Border, Padding, and Margin and the default areas that surround an element. Margin is between the border and surrounding elements, and padding is in between the border and the element itself. Borders style, width, and color can by styled individually in separate lines, or shorthand in a single line.

The display attribute can be used to transform a block element into an inline element or vice versa. It also introduces the new possibility of the *inline-block* and *none* values.

The visibility property allows developers to hide elements. However, it retains it space on the webpage. It has two values, hidden, and visible.

## JavaScript & JQuery

### Chapter 2: Basic JavaScript Instructions (pp.70-73)

Arrays are indexed lists that are constructed to contain like data in an ordered fashion. In JavaScript there is no need to no how many items an array will have since JavaScript dynamically resizes the array behind the scenes based on the need of the script! The items in the array do not need to be the same data type.

Arrays are either declared or constructed. When an array in declared square brackets are used and it is known as an array literal. When an array in constructed, the `new` keyword is used in concjuction with the `Array();` object. Accesing an array index uses slightly different syntax depedning on how the array was created. Array literals are typically the preferred method.

### Chapter 4: Decisions and Loops (Part 2)

#### Switch Statements

Switch statements start with a switch value and then enumerate all different possibilities for the value along with code blocks that should run if the switch value matches the given values or range of values.

#### Type Coercion and Weak Typing

If JavaScript encounters a data type that it does not expect, instead of throwing and error, it will attempt to make sense of the statement behind the scenes in a process known as type coercion. Futhermore, JavaScript uses weak typing becuase the data in a variable can change after it has been declared.

#### Truthy and Falsy Values

##### Falsy Values

- `false`
- `0`
- `NaN`
- Empty Value
- Undefined

##### Truthy

- `true`
- Nonzero numbers
- Nonempty strings

#### Loops

The three types of loops are `for`, `while`, and `do...while`. Some useful loop keywords include `break` and `continue`.
