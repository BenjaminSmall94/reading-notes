# Class 2: More Web Programming Basics

[Home](../index.md)

## HTML5 & CSS

### Chapter 2: Text

#### Structural Markup

- Headings have six levels (`<h1>`... `<h6>`) that convey the flow and hierarchy of information on a webpage as well as provide default format to said elemeents
- Paragraphs (`<p>`)hold the main text content of any page. 
- Bold and italic tags (`<b>` and `<i>`) are used to make text appear in **bold** or *italics*
- Superscript and Subscript tags (`<sup>` and `<sub>`) are use to make text appear as a <sup>superscript</sup> or <sub>subscript</sub>
- Line break tags `<br />` make a line break <br /><br />within an element.
- Horizontal rule tags `<hr />` make a horizontal line

-----

- all the way across the page, and typically indicate a change in topic.
- When browswers encounter more than one consecutive white space or line break, it only reads it as a single space. This is known as white space collapsing.

#### Semantic Markup

Sematic tags will be by default formatted in a specific way. However, they should not be used to format your webpage.Instead they should be used to add meaning to your webpage. Programs such as screen readers or search engines use this extra information to optimize performance.

- The `<strong>` tag is used to indicate that a certain element has **strong** importance. By default strong elements will be displayed in **bold text**.
- The `<em>` tag is used to indicate that a certain elements should be *emphasized*. By default browsers will display this element with *italic* text.
- The `<blockquote>` tag is used for long quotes the form their own paragraph. 

> By default browsers will indent text in  this elements.

- The `<q>` tag is used for shorter inline quotes that sit within a paragraph. By default browsers will place "quotation marks" around text in this element.
- The `<abbr>` tag can be used wherever an abbreviation or acronym is used. It includes a title attribute that specifies the full meaning of the abbreviation or acronym. In HTML4 there was a separate `<acronym>` tag used.
- The `<cite>` tag is used when you are referencing a book, film, or research paper. Browsers will render text in this element in italics by default.
- The `<dfn>` tag is used to indicate the first instance a new term is encountered in an article where it is accompanied by a definition.
- The `<address>` tag contains details for the author of the page such as the physical address, email address, phone number or any other relevant contact information.
- The `<ins>` and `<del>` tags are used to display content that has been added to or removed from a document. By default, insertions are underline and deletions are striked through.
- The `<s>` tag indicates elements that are no longer relevant but that should not be deleted. Text in this elements will be striked through by default.

### Chapter 10 Introducing CSS

#### Block and Inline Elements

The two primary structure types in HTML and CSS are block and inline. Block elements such as `<h1>` and `<p>` will start a new line. Inline elements such as `<img>` and `<span>` do not start a new line and flow within the existing line.

#### HTML and CSS integration

CSS works by giving rules to specific HTML elements. The rules is comprised of two parts.

1. The selector: Selectors define which elements a rule will be applied to. You can select multiple items on the same line by using a comma dilineated list.
2. Any number of declarations: Declarations define what rules to be applied to the selected HTML elements.

Declarations themselves are made up of two parts. 

1. A property: The property chooses which attribute of the selected element will be altered.
2. A value: The value assigns a new manifestation of the property (eg the text color should display as blue).

#### HTML and CSS communcation

There are three ways to implement CSS into any given HTML document

1. External

    The HTML `<link>` tag is used to link a separate .css stylesheet to said HTML document and resides inside the head of an HTML document. It has 3 primary attributes

    1. *href* defines the path to the css sheet
    2. *type* defines the type of document. In this case it would be text/css
    3. *rel* defines the relationship between the HTML document and the linked page. In this case the value should be *stylesheet*

    <br />An HTML document can have more than one CSS style sheet. In this case it would require a link tag for every separate stylesheet.

2. Internal

    Alternatively the `<style>` tag can be used within an HTML document to define the look of a webpage. The style tag has an attribute *type* which should be set to equal "text/css" when writing internal CSS. However except for small single page website it's generally accepted to be better to implement css in a separate file. This allows all pages in a website to use the same stylesheet rather than having to write out the same style multiple times, stylistically keeps the code describing the content of a webpage separate for code describing the look of a webpage, as well as allows a website administrator to change a stye in one loation and be reflected across every page in the website.

3. Inline

    Lastly it is possible to access the style attribute of almost every element that occupies the body of an HTML page in order to change its styling individually.

#### Types of CSS Selectors

| Selector                  | Meaning | Example |
| ------------------------- | ------- | ------- |
| Universal Selector        | Applies to all elements in a document                          | * {}                    |
| Type Selector             | Applies to speicifc element namess                             | h1, p, img {}           |
| Class Selector            | Selects elements according to class attribute value            | .card {} or div.card {} |
| ID Selector               | Selects elements according to ID attribute value               | #person {}              |
| Child Selector            | Selects elements that are direct children of another element   | ul>li {}                |
| Descendant Selector       | Selects all elements that are contained within another element | ul li {}                |
| Adjacent Sibling Selector | Select an element that is directly after another element       | p+img {}                |
| General Sibling Selector  | Selects all elements that are a sibling of another element     | p~img {}                |

#### CSS Rule Priority

1. The highest priority is given to items that are specified *!important*
2. Next priority is determine by specificity, with the more specific selector being granted priority.
3. The next tier or priority is determined by where it is located from high priority to low; inline, internal, then external
4. The lowest tier of priority is states that rules to appear later in a document trump those that go before it.

#### Inheritance in CSS

Certain attributes (eg font-family) are inherited by all children elements by default, while others are not. For example this means that if you specify a font-family for the body of an HTML page all text within child elements will have the specified font. For elements that are not inherited by default you can specify that value of the property of the desired child element to *inherit*.

## Javascript and JQuery

### Chapter 2: Basic JavaScript Instructions

Computer instructions are different than instructions you would give to a human. It is important to start thinking like a computer in order to be able to effectively program one. Each individual instruction in known as a statement and is the foundation of all computer programming. Multiple statements grouped together within curly braces forms a code block.

#### Variables

Virtually all programs require the temporary storage of variables within items called variables. Variables are declared via declaration statements. Declaration statements are made up of two parts; a special declaration keyword and a made up variable name. JavaScript uses the keyword `const` in order to declare variables that are constant and will not change during the exectution of a script. They keyword `let`is used to declare variables that are permitted to or expected to change during the course of code execution. Lastly the antiquated keyword `var` was previously used before 2015 to declare all variables in JavaScript and may be encountered in older code. After a variable is declared, or simultaneously during declaration a value may be assigned to a variable using the equals sign as an assignment operator. When reassingning a value after a variable has been declared you should not use the special declaration keyword.

#### Variable Naming Rules

1. The name must begin with a letter, dollar sign, or an underscore.
2. The name can contain letters, numbers, dollar signs, or underscores.
3. You cannot use special keywords as variable names.
4. Variables are case sensitive

#### Variable Naming Conventions

1. Use a name that describes the kind of data to be stored
2. When creating a variable with two or more words capitalize only the first letter of every subsequent word (eg benchMax). This is know as "camel casing". Alternatively, you may use and underscore to separate words.

#### Javascript Data Types

- Numeric Data Type: Unlike other programming languages, Javascript only has one data type for numbers and does all the work behind the scenes converting the variable between an integer, floating point decimal, and big integer.
- String Data Type: Strings consist of text in the form of numbers and other characters typically using ASCII encoding.
- Boolean Data Type: Boolean is the simplest data type and is represented by a single bit. It can only have two values; true or false.

#### Javascript Arrays

Arrays are indexed lists that are constructed to contain like data in an ordered fashion. In JavaScript there is no need to no how many items an array will have since JavaScript dynamically resizes the array behind the scenes based on the need of the script! The items in the array do not need to be the same data type.

Arrays are either declared or constructed. When an array in declared square brackets are used and it is known as an array literal. When an array in constructed, the `new` keyword is used in concjuction with the `Array();` object. Accesing an array index uses slightly different syntax depedning on how the array was created. Array literals are typically the preferred method.

### Chapter 4: Decisions and Loops (Part 1)

For all but the most basic scripts there are multiple potential paths that a program can follow. This is accomplished through the use of coonditionals. Additionally, it frequently may become necessary to run a repetitive set of instructions many times in a row. This is accomplished through the use of loops and is one of the main strong suits of computers.

#### Conditionals

Conditionals work by having a conditional statement, typically with a comparison operator, that evaluates to a boolean true/false value and that based on that result picking on of two paths of instructional code to follow. Additionally logical operators (AND, OR, NOT, XOR, NOR) are frequently used in ordre to combine boolean values.

If statements are the most commonly used conditional operator and determines if a specific code block will be executed. Frequently it is accompanied by an else case for an alternate set of instructions if the initial case is not evaluated to true.

## Things I want to know more about

- Differences in how different web browsers interpret HTML and CSS.
