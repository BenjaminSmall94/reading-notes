# Command Line Practice

[Home](../index.md)

## The Command Line - Intro

The Command Line, called the Terminal in MAC is an alternate way to interface with a computer as opposed to the typical graphical user interface. It is possible to completely leave the GUI behind but is usually benefical to use a hybrid combination of the two. To a trained user, the terminal is much faster and conducting the majority of tasks you would like to accomplish.

## Basic Navigation

The first command to know is `pwd`. This literally prints the current working directory. It lets you know where you are. `ls` lets you see what items are in a directory, by default it will expand your current working directory. Each command can take options and/or arguments to alter the default behaviour of the command.

Paths are the basis of being able to meaningfully interact with files and folders. They come in two varieties; absolute and relative. Absolute paths begin with a `/` and specify a location in reference to the root directory. Relative paths specify a location on relation to the current working directory. Use the command `cd` to change the working directory within the terminal.

## More About Files

Everything is a file in linux based systems, that includes directories and hardware. Additionally Linux is extensionless. That means that linux will ignore the extension at the end of the file name and simply look at the file itself to determine what the file type is. You can use the command `file` in the terminal to explicitly state what the filetype is. Hidden files are denoted by a `.` at the beggining of the file name.

## Manual Pages

Manual pages is the built-in encyclopedia for all commands available in your terminal. The primary way to access it is with the command `man` followed by the command you would like to learn about. Alternatively, you can add the option `-k` followed by a search term and this will display all commands that involve this search term in one way, shape, or another.

## File Manipulation

The first command we will learn for file manipulation is `mkdir`. This command makes a whole new directory name whatever you want wherever you specify (Remember that directories are indeed files). The most common options associated with this command `-p` and `-v`. These will, in order respectively, make necessary parent directories (as applicable) and make the output verbose in terms of exactly what was executed.

Additional Commands include

- `rmdir` removes empty directories
- `touch` creates a blank file
- `cp` copies a file
- `mv` moves or renames a file
- `rm` removes a file (with `r` option can remove non-empty directories as well)

## Cheat Sheet

Reference this [cheat sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php) for a quick reference guide.
