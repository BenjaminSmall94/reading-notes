# Forms and JS Events

[Home](../index.md)

## HTML and CSS

### Chapter 7 Forms

HTML has an element tag `<form>` that is used to capture user input of all types and submit it either to be used on the client-side for some form of manipulation or to be sent to a server and stored on a database. There are many common components of HTML forms for many different things

#### Form Components

- Adding Text

  - Text Input (single-line)
  - Password Input (masks the input characters)
  - text area (for multiple lines or paragraphs) (is a separate tag, `<textarea>`)

- Making Choices

  - Radio Buttons (Allow only one item to be selected)
  - Checkboxes (Allow multiple items to be selected)
  - Drop-down boxes (Allow specific items from a list) (is a separate tag, `select`)

- Submitting Forms

  - Submit Buttons
  - Image Buttons
  - File Upload (allows users to browse to upload specific files for their local system)

#### Form Default Behavior

By default forms will submit the information to a server specified by the URL value associated to its action value. The method by which it uploads is determined by its method attribute and can be either `get` or `post`.

#### HTML5 New Features

HTML5 has a slew of new features regarding forms. If older browsers encounter this they will just revert them to the older equivalent versions of these items. Examples include, date, email, URL, and search inputs as well as the `placeholder` attribute of text inputs.

### Chapter 14: Lists and Forms

#### Lists

##### list-style-type

This property allows you to alter the default formatting of ordered and unorderd lists as well as list elements.

###### Unorderd Lists

Unorderd lists can have the following values for `list-style-type`

- none
- disc
- circle
- square

Additionally the `list-style-image` property can be applied to `<ul>`s in order to use an image in place of the bullet point.

###### Ordered Lists

Ordered lists can have to following values for `list-style-type`

1. decimal
2. decimal-leading-zero
3. lower-alpha
4. upper-alpha
5. lower-roman
6. upper-roman

#### Table Properties

- width
- padding
- text-transform
- letter-spacing
- font-size
- border-top
- border-bottom
- text-align
- background-color
- :hover

#### Styling Forms

It is important to style forms in order to look pretty and be readable and understandable. One particularly interesting thing you can do is alter the cursor styles. The most commonly used cursor styles are auto, crosshair, default, pointer, move, text, wait, help, url("cursor.gif");

## JavaScript and JQuery

### Chapter 6: Events

It is vital to making interactive and exciting webpages to have interactivity. Events are key to enabling this. User action triggers events, which fire code, which interacts with the user.

#### Types of Events

There are 6 main categories of events

- UI Events
- Keyboard Events
- Mouse Events
- Focus Events
- Form Events
- Mutation Events

#### JavaScript Event Fundamentals

The sequence for enabling and event in JavaScript is:

1. Select an Element
2. Specify what Event trigger the Code
3. Specify the code to be triggered

There are three ways to bind an event to an element

1. HTML Event Handlers (Bad Practice - Antiquated)
2. Traditional DOM Event Handlers
3. DOM Level 2 Event Listeners

#### Event Flow

If an element that is a descendent or ancestor of another element has a similar event attached to it, the DOM/JavaScript need to know which events to execute first. The default is event bubbling, but can be overwritten to execute via event capturing.

#### The Event Object

Funtions that are triggerd by an event can take one optional variable, and that variable is the event which has several attributes and methods.

##### Event Variables

- target
- type
- cancelable

##### Event Methods

- preventDefault()
- stopPropagation()

#### Event Usage

There are a billion different ways to use events to make your website cool and interactive it's up to you to figure out the best way to do that!

## Things I want to know more about

I just want to get practice and gain familiarity with using all the different event types and event attributes. I think that will all just come with time and practice.