# Solutions of JavaScript Fundamentals Part 2
This file contains my attempt to the Knowledge Check section on this [page](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-2#knowledge-check)

> What are the eight data types in JavaScript?

1. [Boolean type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#boolean_type)
2. [Null type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#null_type)
3. [Undefined type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#undefined_type)
4. [Number type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#number_type)
5. [BigInt type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#bigint_type)
6. [String type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#string_type)
7. [Sytmbol type](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#symbol_type)
8. [Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#objects)

> Which data type is NOT primitive?

Object

> What is the relationship between null and undefined?

`undefined` means a variable has been declared but has not yet been assigned a value while `null` is an assignment value. It can be assigned to a variable as a representation of no value.

> What is the difference between single, double, and backtick quotes for strings?

Double and single quotes are “simple” quotes. There’s practically no difference between them in JavaScript.

Backticks are “extended functionality” quotes. They allow us to embed variables and expressions into a string by wrapping them in `${…}`.

> How do you escape characters in a string?

backslash (`\`)

> What are methods?

Programming functions

> What is the difference between slice/substring/substr?

* `slice()` and `substring` are basically the same but they have some slightly difference when index is negative. We mainly use `slice()` because it has the least number of unexpected behaviours. 
* As for `substr()`, it has a different signature. Its signature is `substr(startIndex, length)`. For more detailed information, check out this [page](https://www.bennadel.com/blog/2159-using-slice-substring-and-substr-in-javascript.htm).

> What are the three logical operators and what do they stand for?

1. || (OR)
2. && (AND)
3. ! (NOT)

> What are truthy and falsy values?

In JavaScript, a truthy value is a value that is considered true when encountered in a Boolean context. All values are truthy unless they are defined as falsy (i.e., except for `false`, `0`, `-0`, `0n`, `""`, `null`, `undefined`, and `NaN`).

> What are conditionals?
> What is the syntax for an if/else conditional?
> What is the syntax for a ternary operator?

This [Page](https://javascript.info/ifelse)

> What is nesting?

This [Page](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions#nested_functions_and_closures)
