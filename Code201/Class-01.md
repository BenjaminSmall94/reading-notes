# Class 1: HTML, CSS, Javascript Refresher

[Home](../index.md)

## HTML5 & CSS

### Chapter 1: Structure

This chapter describes how HTML uses elements that are bound by tags to provide structure to a webpage. This structure is very similar to how we provide structure to websites and word documents. Each HTML tag not only provides a default display for elements in a webpage, but also provides semantic meaning that can by interpretted by web browsers to ease consumption of data as well as accessiblity to visually impaired individuals.

Elements have opening and closing tags. Within each tag a sequence of letters defines what kind of tag it is. Additionally within the opening tag attributes can be assigned. `<html>` Tags define the start and end of HTML code. `<head>` Provides information about the page rather than what is displayed in it, such as a `<title>` tag which tells the browser what name to display on your tab. `<body>` Tags encapsulate everything that is to be shown on the page.

### Chapter 8: Extra Markup

This chapter covers various miscellaneous features of HTML that are not easily grouped into any other chapters. These is very important to know as they allo developers to further structure and add semantic meaning to their websites.

#### Evolution of HTML

- HTML4: released in 1997
- XHTML 1.0: released on 2000
- HTML 5: released in 2000

Each version was intended as an improvement on the last and enabled web browsers and developers to incorporate new features while fixeing things about previous versions. 

#### Doctypes

A `<!DOCTYPE>` is a sigular tag that is used to help browsers distiguish between versions. Usually a webpage will render just fine and browser are able to infer what language they are reading. However it is considered good form and can occasionally help with rendering a webpage correctly.

#### Other Miscellaneous Features

- Comments in HTML are denoted as `<!-- -->` and provide developers a way to remind themselves or others working on their code, the purpose of specific parts of code. Additionally comments can be useful for debugging/figuring out what is wrong with your webpage.
- ID and class atributes allow HTML to give an unique identifier to either a single element or a group of elements. This then allows developers to format said items in a unique way.
- The `<div>` and `<span>` elements allow developers to group elements or text into a wrapper tag where no other sematic tag would be appropriate. `<dov>` is a block element and `<span>` is an inline element.
- The `<meta>` tag allows a developer to provide information about a page that is not displayed on a page for a number of reasons but primarily for search engine optimization.
- Lastly, there are a number of special characters that are reserved for special meaning in HTML. In order to display them you must type in the special sequence of characters, and then HTML will display them on the fully rendered webpage.

### Chapter 17: HTML5 Layout

HTML introduced a slew of new features over HTML4. A prominent change was the additional of several new semantic tags to provide meaning to many portions of a webpage that previously would have simply resided inside `<div>` tags. Additionally, HTML5 promoted the use of an `<a>` tag surounding a block element to make an entire block a link.

#### New Semantic Tags

- `<header>`
- `<footer>`
- `<nav>`
- `<article>`
- `<aside>`
- `<section>`
- `<hgroup>`
- `<figure>`

#### Reverse Compatiblity

Older browsers need to be told that these new elements should be treated as *block* elements and not *in-line* elements. Even older browsers need JavaScript to run and correct the formatting of these new elements, but this requires Javascript to be installed in the browser.

### Chapter 18: Process and Design

#### Understanding your audience

The look and design of a website is paramount when it comes to building a good website. However, there is no *best design* that works in every scenario. Equally important to the content on the site, is the expected audience that will be using your website. Without properaly understanding who they are, what they expect, and what they want, you will never be able to build a good website.

#### Tools to design your website

- **Sitemaps** are a great way to plan out the flow of your website. If you are having trouble sorting your information, the practice of *card sorting* will help you group information.
- **Wireframes** are a great way to plan out the look of each of your pages

#### Design Considerations

Considering the *visual hierarchy* will assist you in making sure your content in navigable, and important information sticks out. Consider using *size*, *color*, and *style* to make important information stand out.

Grouping like information through, proximity, closure, continuance, white space, color, and/or borders will increase the readability of your website.

Navigation bars should be clear, concise, and selective. They should also provide context as to where you are in the site, and be interactive and consiststed.

By employing these simple practices you can greatly increase the quality of your webstie.

## Javascript and JQuery

### Chapter 1: The ABC's of Programming

#### What is a script

Much like a handbook or user manual, a script is a set of directions to be executed based on the needs of the current situation. All of the instructions involved in a script need not, and likely will not be executed every signle time a program is called upon. Only the line that are relevant and helpful to the current situation will be executed.

#### Writing a Script

Follow these steps when writing any script

1. Define the goal
2. Design the script
3. Code each step

In doing this, you can progress from a broad goal, and then break it down into easily understandable steps. Frequently you will find, the instruction you need to give to a computer are different and much more fundamental than if you were instructing a human to conduct the same task. Additionally, every single step needs to be written in a language that a computer can understand. Similar to every other language, this involves vocabulary and syntax.

#### Components of Script

Objects are a data represenation of a real world object or concept. They are defined by their;

- Properties: characteristics which contain and name and a value to encapsulate the current and sometimes unchangeable state of an object.
- Events: ways in which a site user can interact with an object. Whether that is hover their mouse, clicking a box, typing on the keyboard, or using another device to interact with the computer and webpage, these events trigger a certain response based on the current situation.
- Methods: the set of instructions to run following an event that will either change one of it's own properties, or another object's properties.

#### The Document Object

The document object allows your script to access the html code of an associated website in order to change its properties, add or remove events, and activate its methods.

#### The Trifecta of Website Development

1. HTML: Structure
2. CSS: Design
3. Javascript: Behavior

In order to link to an external Javascript file (best practice) you need to put a `<script>` tag in the html file you want to associate to with a `src` attribute set to the locatioo of your JavaScript file. It is possible to put internal script that falls between the opening and closing `<script>` tags, however this is generally frowned upon.

## Things I want to know more about

- This was all pretty familiar up to this point. I look forward to furthering and refining my knowledge as this course goes on!
