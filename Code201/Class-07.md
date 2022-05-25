# Object-Oriented Programming, HTML Tables

[Home](../index.md)

## Domain Model

It is highly useful to focus on small parts of a problem at a time an solve problems incrementally. This practice lends itself very well to Object Oriented Programming, where you can build a single object that repeats similar process over and over again and has multiple methods inside, all of which do a particular narrow task very well and efficiently.

### Summary

>Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.
>
>Here's some tips to follow when building your own domain models.
>
> - When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
> - Model its attributes with a constructor function that defines and initializes properties.
> - Model its behaviors with small methods that focus on doing one job well.
> - Create instances using the new keyword followed by a call to a constructor function.
> - Store the newly created object in a variable so you can access its properties and methods from outside.
> - Use the this variable within methods so you can access the object's properties and methods from inside.

## HTML Tables

For items that should be displayed in a 2 dimensional layout/grid (eg finance info, sports data), use the HTML Table element.

HTML tables are built out row by row. On the outside a `<table>` tag encapsulates the entire table. Each row is boound by a `<tr>` tag. Each element is represent by a table data `<td>` tag. The table header `<th>` tag takes the place of `<td>` on the top and left most row/column and represents that name of the corresponding row/column. If you need an single `<td>` or `<th>` to span more than one column use the `colspan` attribute. The same can be done for rows with the `rowspan` attribute. The headers row, typically the first row should be bound by a `<thead>` tag and the body by a `<tbody>`, and the footer, if present, should be bound by a `<tfoot>` tag. These are rarely formatted differently by default in a browser, but are useful reference selectors for CSS.

## Functions, Methods, and Objects (Part 3)

### Objects

> The new keyword along with the object constructor creat a blank object. You can then add properties and mthods to the object.

You can update properties of an object, regardless of how it was created, with dot notation or square brackets. The delete key word deletes attributes. Using the constructor notation allows easy recreation of objects of the same type.

### This Keyword

Depending on where the "this" keyword is placed, it can refer to various things. When placed in an area with global scope, "this" refers to the window and has access to all gloabal variables as well as built in values like `innerWidth` and `innerHeight` through use of the dot notation. When placed in the method it refers to value of the containing object. If a function is placed in global scope, uses this notation, and is mapped as a method to an object, then called as a method from within that object, this refers to the Object instance that is calling it.

### Built-in JavaScript Objects

Some of hte most common built-in objects are

1. Browser Object Model
2. Document Object Model
3. Gloabal javaScript Objects (eg Math, Date, Regex)

## Things I want to know more about

I just need to get repetitive practice working with all the built in objects that JavaScript has available so I can know what kinds of resources I have available to accomplish specified tasks. HTML Tables seems very straightforward and easy to understand. Getting to better understand how object oriented programming fits within the domain model is also highly beneficial.
