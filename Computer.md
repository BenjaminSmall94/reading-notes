# The Coder's Computer

[Home](index.md)

## Text Editors

### Basic Text Editors

Every operating system comes with an organic "barebones" text editor. MacOS has *textEdit* and Windows has *Notepad* and Linux platforms come with their 
own uniquie text editor. These basic editors are meant for storing and viewing plain text files and have no features that assist with code completion, 
debugging, or viewing of code. In my opinion, it would be foolish and an irresponsible use of your time to try to code in such an environment.

### Coding Specific Text Editors

The next step up in terms of complexity are Coding Specific Text Editors like Notepad++, BB edit, Visual Studio Code, and Atom. These all provide 
increased functionality over the organic text editors such as code completion, syntax highighting, a variety of themes, and a healthy number of 
extensions for coding with increased complexity. There are numerous free and paid options when it comes to Coding Specific Text Editors.

### Integrated Development Environments

These offer the highest degree of complexity and assistance in coding. They include compilers, debuggers, text and file managerment procedures and 
virtually all cost money.

## The Command Line (AKA Terminal)

The Terminal is an alternate way of interacting with files and your computer rather that the typical graphical user interface. It provides alternate 
and some additional functionality over the GUI.

### Relative Path vs Absolute Pate

It's important to remember that loacations can be accessed in multiple ways either by accessing the full address, or by referencing a address relative to 
your current address.

Additionally there are various shorthands

> - ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with 
> the path /home/ryan/Documents or ~/Documents
> - . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could 
> also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
> - .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in 
> the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.
> - A single slash / denotes the root directory. Is is the very top of the directory structure.

## Files

### Everything is a file

Ok, the first thing we need to appreciate with linux is that under the hood, everything is actually a file. A text file is a file, a directory is a 
file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. To begin with, 
this won't affect what we do too much but keep it in mind as it helps with understanding the behaviour of Linux as we manage files and directories.

## Terminal Cheat Sheet

```
- pwd (print working directory)
- ls [options][location] (list)
- cd [location] (change directory)
- file (obtain information about what type of file a file or directory is.)
- ls -a (List the contents of a directory, including hidden files.)
```
