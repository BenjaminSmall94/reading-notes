# Hashtables

[Home](../index.md)

## What is a Hashtable

### Terminology

1. Hash: The result of taking in an incoming string and converting it to an address in memory or index of an array.
2. Buckets: In the case of an array each index is a bucket, but each bucket may contain multiple values if there is a hash collision
3. Collisions: When two incoming strings evaluate to the same index/address in memory.

### Why we care

Hashtables can hold unique values, form python dictionaries, and support libraries. They enable O(1) constant lookup time.

### Structure

### Hashing

Hashing turns a key value into an integer that can reference an index in an array or an address in memory.

### Collision Resolution

Collisnions are solved by placing linkedlists into each index of the array. Then if more than one value is added to the same index or bucket, it is just appended to the linked list. So unevenly distributed linked lists could lead to nearly O(n) lookup time.

### Internal Methods

- `Add()`
- `Find()`
- `Contains()`
- `GetHash()`

## Things I Want to Know More About

I want to see how you can use hash tables to make challenging coding problems optimized to the quickest possible solution
