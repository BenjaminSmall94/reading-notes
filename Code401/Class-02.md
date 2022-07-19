# Testing and Modules

[Home](../index.md)

## In Tests We Trust

> *Test-Driven Development* (TDD) is a strategy to think (and write!) **tests first**.

Test are a small piece of code to test sample inputs for the correct outputs. Projects should be broken down into small components first and tested at each elvel to determine if it is functioning as it should. Test file names should be based off of the module name you are testing. A common mantra to follow in the software testing realm is Arrange, Act, Assert.

> Arrange: you need to organize the data needed to execute that piece of code (input);
> Act: here you will execute the code being tested (exercise the behaviour);
> Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

TDD is driven by the cycle

> 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)
> ✅ Write the feature and make the test pass! (you can dance after that)
> 🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)

Sometimes even more valuable than the tests themselves is the time you take developing them forces you to understand the assignment and build a quality product.

## If name equals main

Python has the special variable `__name__` to indicate whether a file is being executed directly or if it is being run through another file as an imported module. You can then run conditional tests on your files to alter behaviour based on this trait.

## Recursion

As opposed to normal iterative methods, recursion offers a sleek alternative that can often be written in much less code. The downside is that it does require a call stack that can overflow it certain cases.

## Modules and Packages

Modular programming refers to breaking apart large programming tasks into smaller portions. It offers advantages in the realm of simplicity, maintainability, reusability, and scoping.

## Things I Want to Know More About

I want to learn more about package management especially in the case of building my own packages.
