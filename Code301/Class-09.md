# Functional Programming

[Home](../index.md)

## Functional Programming Concepts

1. What is functional programming?
   "Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data" - Wikipedia

1. What is a pure function and how do we know if something is a pure function?
   If it is deterministic, always returning the same result with the same parameters and not dependent on outside variables, as well as having no observable side effects.

1. What are the benefits of a pure function?
   It is easier to test, easier to build.

1. What is immutability?
   When objects are unchangeable. Once they are created they never change.

1. What is Referential transparency?
   When a function is a pure function and uses immutable data

## Node JS Tutorial

1. What is a module?
   Separate parts of code in different files that can be required and called on by your main module to execute certain parts of code.

1. What does the word ‘require’ do?
   In a way it imports the file to be used in your current file.

1. How do we bring another module into the file the we are working in?
   We use the require statement with the path to the module that you need

1. What do we have to do to make a module available?
   We need to determine which parts of the original module are "Public" or available to other modules. So you use a `module.export = ...`
