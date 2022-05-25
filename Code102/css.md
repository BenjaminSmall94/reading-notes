# CSS

[Home](../index.md)

## What is CSS

Cascading Styles Sheet (CSS) is a stylesheet programming language that allows a deveelopere to override browser defaults and give a specific design, or style, to an html page. CSS can be used for very basic document text styling — for example changing the [color](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value) and [size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) of headings and links. It is also used for document layout and basic animations.

## Syntax

The basic syntax of CSS involves a *selector*, *properties*, and *values*

```
h1 {
    color: green;
}
```

In this instance "h1" is the **selector** and it finds *all* the h1 tags in your html document. The property is "color" is the **property**, and "green" is the **value**. We just changed the font color of all the text in "h1" tags to green.

## Implementing CSS

There are three ways you can implement CSS.

- External CSS
- Internal CSS
- Inline CSS

Lets look at examples of each in order

### External CSS

```
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="externalstyle.css">
    </head>
    <body>
        <h1>External Example</h1>
        <p>Content</p>
    </body>
</html>
```

A can be seen, the link tag tells the html document and external file to locate and implement the CSS styling.

### Internal CSS

```
<!DOCTYPE html>
<html>
    <head>
        <style>
            h1 {
                color: maroon;
                margin-left: 40px;
            }
        </style>
    </head>
    <body>
        <h1>Internal Example</h1>
        <p>Content</p>
    </body>
</html>
```

As can be seen, the CSS code is contained within a `<style>` tag embedded within the head of the html document.

### Inline CSS

```
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <h1 style="color:green">Inline Example</h1>
        <p style="color:blue;">Content</p>
    </body>
</html>
```

As can be seen the CSS formatting is contained within the specific element tag that is to be modified.

### Implementation Priorities

If their are conflicting/contradicting instructions in a CSS stylesheet, CSS will implement the formatting with the following order of precedence.

1. Inline CSS
2. External and Internal CSS (Higher priority to whichever comes last in stylesheet)
3. Browser defaults

## CSS Color Attribute

Colors in CSS are mainly used for text and background-colors. Its value can be specified in a plethora of ways

- Hex Value
- RGB
- RGBA
- HSL
- HSLA

It is up to you which value you prefer, and each one is fitted better to certain situations.