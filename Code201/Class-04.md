# HTML Links, JS Functions, and CSS Layout

[Home](../index.md)

## HTML & CSS

### Chapter 4: Links

Links are the defining feature of a web page as they essentially enable a seamless experience fo "surfing the web". Links can link to a new website, to a different page in the same website, to a different part of the same webpage, or enable quick addressing of an email to a specific address. Links in HTML are created with and `<a>` tag and have a href attribute to determine the URL to associate with. When you link to another website the URL must be an absolute URL. Links to other pages on the same website use a relative URL.

#### Relative URL Basics

When designing a website it's important to consider structure, relationships, and proper use of homepgaes. The top level folder of a webpage is known as the root. Relationships like siblings, children, or parents will dictate the proper use of relative URls. Each folder can have a homepage annotated with the name index.html. When using relative links and going down into children or grandchildren folders you simply need to type out the folder name followed by a slash "/" until you reach the desired folder and then type the file name. For accessing parents or grandparents folder use two dots and a slash "../"to move up a single level in a directory.

#### Special Uses for Links

To create email links be sure to include "mailto:" in the value of your href attribute before typing in the email address. In order to link to other places on the same page simply set the href attribute to pound sign "#" plus whatever the ID of the desired element you wish to navigate to is. You can also apply this principle to link to specific locations of another page by including a pound sign "#" plus whatever the ID of the desired element in you new page is to the end of the previously specified address.

### Chapter 15: Layout

Fundamentally CSS treats each HTML element as though it exists in its own special box. The two primary types of boxes are:

1. Block-level: Fill entire width of parent element and start a new line.
2. Inline: Flow with with text and only fill the space their content takes up and now more.

#### Positioning of Elements

1. Normal Flow: Block Elements fill the width and always start a new line. Inline always flows with text based on the size of its content.
2. Relative: An element is positioned relative to where it normally would occupy.
3. Absolute: An element is positioned relative to its parent element.
4. Fixed: An element is positioned relative to the browser window viewport.
5. Floating: An element is removed from the normal flow and is may be positioned to the far left of right of the containing element and other inline elements will flow around it.
6. Static: This reverts block elements back to their default value.

#### Other Positioning features

- The z-index attribute determines which element will take display priority when two elements are overlapping.
- The clear attribute can be used on floating elements to start a new line when paragraphs are different heights.

#### Screen Sizes

Screen sizes can vary greatly in width as well as height! It is important to develop websites with this in mind. When building a website it is important to keep attention grabbers and information on what the page is about near the top of the page.

#### Fixed vs Liquid Layouts

Fixed layouts allow a lot more specific control of the exact look of a page, however they may leave large "white space" to the sides of larger monitors, or be hard to read on high resolution "4k" screens. Also they can take up a lot more vertical space than liquid layouts. Liquid layouts are harder to design correctly and can lead to some unforeseen and unintended layouts. However, if done well, it can increase readability on all devices.

## JavaScript and JQuery

### Chapter 3 (Part 1): Functions, Methods, and Objects

Functions contain a series of statements organized together to accomplish a specific task. Usually functions will take parameters as input, and produce a return value as output. A method is function that is part of an object. Objects are models of the real world comprised of methods and variables. JavaScript and the web browser come with several pre-defined Objects.

Declaring a functions requires the function keyword, a name followed by open and close parentheses containing necessary parameters (if any), and lastly a set of curly braces surrounding the lines of code to be accessed.

### 6 Reasons for Pair Programming

Pair programming is the practice of two developers working together at a single workstations in order to efficiently design a program to solve a single task.

The roles are typically divided into a driver and a navigator. The driver is the one with hands on the keyboard managing the text editor, switching files, and actually writing the code. The navigator is guiding the driver with his words and has his mind on big picture things like determining the best algorithm for a specific task and searching for bugs and typos. They also can use a second workstation to work their Google Fu to answer any unknowns.

As well as being an excellent learning tool for students it can also increase efficiency, encourage collaboration, provide an opportunity to learn from your peers, build social skills, prepare for technical interviews, and future job opportunities!
