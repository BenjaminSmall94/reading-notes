# Operators and Loops

[Home](../index.md)

## Operators

### Assignment Operators

Assignment operators provide a shorthand for appending to elements together and assigning their new combined value to the first element.

#### Typical Assignment Operators

Performs an operation with two elements and assigns the return value to the first element

| Name | Operators | Meaning |
| ---- | --------- | ------- |
| Assignment | x = f() | x = f() |
| Addition assignment | x += f() | x = x + f() |
| Subtraction assignment | x -= f() | x = x - f() |
| Multiplication assignment | x *= f() | x = x * f() |
| Division assignment | x /= f() | x = x / f() |
| Remainder assignment | x %= f() | x = x % f() |
| Exponentiation assignment | x **= f() | x = x ** f() |

#### Bitwise Assignment Operators

Performs a bitwise operation with two elements and assigns the return value to the first element. The right and left shift operators are still confusing to me but I need to move on and come back to that later. I don't understand how they work with negative numbers.

| Name | Operators | Meaning |
| ---- | --------- | ------- |
| Left shift assignment | x <<= f() | x = x << f() |
| Right shift assignment | x >>= f() | x = x >> f() |
| Unsigned right shift assignment | x >>>= f() | x = x >>> f() |
| Bitwise AND assignment | x &= f() | x = x & f() |
| Bitwise XOR assignment | x ^= f() | x = x ^ f() |
| Bitwise OR assignment | x \|= f() | x = x \| f() |

#### Logical Assignment Operators

Performs a logical operation with two elements and assigns the return value to the first element.

| Name | Operators | Meaning |
| ---- | --------- | ------- |
| Logical AND assignment | x &&= f() | x && (x = f()) |
| Logical OR assignment | x \|\|= f() | x \|\| (x = f()) |
| Logical nullish assignment | x ??= f() | x ?? (x = f()) |

### Comparison Operators

| Operator | Description |
| ------------ | --------------- |
| == | equal to |
| === | equal value and equal type |
| != | not equal |
| !== | not equal value or not equal type |
| \> | greater than |
| < | less than |
| \>= | greater than or equal to |
| <= | less than or equal to |
| ? | ternary operator |

## Loops

### For Loops

For loops repeat a specific section of code until a specific condition is met. Stylistically it is used when the number of interations is known and so the loop will continue until a counter has reached the specified number.

### While Loops

While loops also repeat a specific section of code until a specific condition is met. However they are stylistically used when this condition is vauge and the number of exact iterations may not be known.
