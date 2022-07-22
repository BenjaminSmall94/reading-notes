# Linked Lists

[Home](../index.md)

## Big O: Analysis of Algorithm Efficiency Part 1

Big O evaluates the growth rate of efficiency and complexity of space (memory) and time (processing power) required to execute different algorithms with inputs of varying sizes. Big O is generally used to describe the worst case but is also useful when looking at the best and average cases. When looking at Big O it is important to understand the concepts of input size, units of measurement, and orders of growth.

### Input Size

Input size, commonly referred to as "n", describes the cumulative size of all the parameters passed to a function.

### Units of Measurement

#### Running Time

1. Time (usually in milliseconds) - Less robust since different machines will complete the same algorithm much faster than other machines.
2. Number of Operations

#### Memory Usage

1. Bytes (Memory)
   - Input Data
   - Output Data
   - Space needed to run the algorithm

In most modern machines there are megabytes of memory in the cache and gigabytes of RAM available, so space complexity is not as important as it once was.

### Complexities to Know

1. Constant - Complexity does not increase with input size
2. Logarithmic - As input increases, complexity increases at a much lower rate (inverse of exponential)
3. Linear - As input incresaes, complexity increases at the same rate

## Linked List

A collection of nodes all with values and pointers to the next node in the list. For the case of doubly linked lists each node contains two pointers, one to the next node, and one to the previous node. Traversal depends on using the next property of each node until you reach the end of the list.

Linked list gives great advantage in the operation of adding and removing a node since unlike arrays, the whole list does not need to be copied over or shifted. Once you have the index (or node) at which you want to make the swap, the only steps that would be required are manipulating a couple pointers.

> When an array is created, it needs a certain amount of memory. If we had 7 letters that we needed to store in an array, we would need 7 bytes of memory to represent that array. But, we’d need all of that memory in one contiguous block. That is to say, our computer would need to locate 7 bytes of memory that was free, one byte next to the another, all together, in one place.
>
> On the other hand, when a linked list is born, it doesn’t need 7 bytes of memory all in one place. One byte could live somewhere, while the next byte could be stored in another place in memory altogether! Linked lists don’t need to take up a single block of memory; instead, the memory that they use can be scattered throughout.
>
> A linked list is usually efficient when it comes to adding and removing most elements, but can be very slow to search and find a single element.

## Things I Want to Know More About

I want to practice complicated linked list problems to challenge my brain into really understanding linked lists.
