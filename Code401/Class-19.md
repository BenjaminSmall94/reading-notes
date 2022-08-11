# Automation

[Home](../index.md)

## Python Regular Expressions

The `re` standard library in python provides excellent functionality for all things regular expressions including methods such as:

- compile()
- search()
- findall()
- sub()
- split()
- match()
- search()
- group()

The letter "r" before a regular expression string tells the python interpreter to interpret the string as a *raw string*

### Special Characters

Special characters include

- \*
- ^
- [ ]
- { }
- .
- $
- \+
- ?
- various \letters to signify many different things.

### Compilation Flages

Compilation flags can be adjusted throught the re object. Common flags include:

> - IGNORECASE (I) - Allows case-insensitive matches.
> - DOTALL (S) - Allows . to match any character, including newline.
> - MULTILINE (M) - Allows start of string (^) and end of string ($) anchor to match newlines as well.
> - VERBOSE (X) - Allows you to write whitespace and comments within a regular expression to make it more readable.

## Shutil

Shutil allows a developed to access high level file management across systems. It is a very useful module.

## Things I Want to Know More About

I want to know more about how python regular expression differ from JavaScript regular expression. What are some common stumbling blocks that people encounter when making the transition?
