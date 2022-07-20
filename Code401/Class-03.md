# FileIO and Exceptions

[Home](../index.md)

## Read and Write Files in Python

### File Components

Files are made up of three mane parts

1. Header (type of file, size, name)
2. Data
3. End of file (EOF)

### Character Encoding

Two common encoding standards are the ASCII and UNICODE formats. They are related but while ASCII can only represent 128 characters, UNICODE can represent 1,114,112.

### Opening and Closing files

`file = open('example.txt')` would open the file and return a file Object.

The use of a try-finally block ensures that you close all your files even if encountering and error

```python
try:
  # Actual Code Here
finally:
  file.close()
```

The other way to ensure a file is closed is to use a "with" statement

```python
with open('example.txt') as reader:
  # Code Goes Here
```

Additionally a second argument can be sumbitted as a string flag to indicate additional options

> |  Character | Meaning  |
> | --- | --- |
> | 'r' | Open for reading |
> | 'w' | Open for writing |
> | 'rb' or 'wb' | Open in binary mode (read/write using byte data) |

### File Objects

File objects are objects that allow users to interact with files in various ways in the programming language of their choosing. There are three different categories of file objects

- Text files
- Buffered binary files
- Raw binary files

## Exceptions in Python

### Syntax Error vs Exception

Syntax error is just an incorrectly written statement, example and extra open parenthesis. Exceptions occur during execution with completely valid code.

### Raising Exceptions

`raise Exception("error message")`

However this would not make much sense to only have an exception in your code. You should have a check that happens so that when a condition is met, then an exception in raised. You can also design your own exceptions by designing it in a class.

## Things I want to know more about

I want to keep seeing how files and exceptions are used in python. I am blown away by how simple the syntax looks like for file interaction. I did a little independent research on vanilla javascript in order to get it to effectively interact with files in a similar fashion and it was much more complicated. I am excited to see all the different things you can do with this!
