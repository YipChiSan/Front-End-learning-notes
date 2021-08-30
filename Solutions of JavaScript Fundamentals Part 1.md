# Solutions of JavaScript Fundamentals Part 1
This file contains my attempt to the Knowledge Check section on this [page](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-1#knowledge-check)

> Name the three ways to declare a variable?

1. `let`– is a modern variable declaration.
2. `var` - is an older way to declare a variable. We normally will not use it now.
3. `const` - is like `let`, but the value of the variable can’t be changed.

> Which of the three variable declarations should you avoid and why?

1. Avoid reserved names. For example, `var` or `return` should be avoided. 
2. Avoid Declaring twice. A variable should be declared only once. A repeated declaration of the same variable is an error. So, we should declare a variable once and then refer to it without `let`.
3. An assignment without `use strict`.

> What rules should you follow when naming variables?

* Use human-readable names like `userName` or `shoppingCart`.
* Stay away from abbreviations or short names like `a`, `b`, `c`, unless you really know what you’re doing.
* Make names maximally descriptive and concise. Examples of bad names are `data` and `value`. Such names say nothing. It’s only okay to use them if the context of the code makes it exceptionally obvious which data or value the variable is referencing.
* Agree on terms within your team and in your own mind. If a site visitor is called a “user” then we should name related variables `currentUser` or `newUser` instead of `currentVisitor` or `newManInTown`.

> What should you look out for when using the + operator with numbers and strings?

Check out this [page](https://www.w3schools.com/js/js_numbers.asp). This is too long to memorise.

> How does the `%` operator work?

The modulus operator (`%`) returns the division remainder.

> Explain the difference between == and ===.

In short, the equality operator `==` does type coercion while the identity operator `===` does not do type coercion. However, there are some interesting cases. Please check out this [page](https://stackoverflow.com/questions/359494/which-equals-operator-vs-should-be-used-in-javascript-comparisons/38856418#38856418).

> When would you receive a NaN result?

NaN is a JavaScript reserved word indicating that a number is not a legal number.

Trying to do arithmetic with a non-numeric string will result in `NaN` (Not a Number):
```
let x = 100 / "Apple";  // x will be NaN (Not a Number)
```
However, if the string contains a numeric value , the result will be a number:
```
let x = 100 / "10";     // x will be 10
```
Watch out for `NaN`. If you use `NaN` in a mathematical operation, the result will also be `NaN`:
```
let x = NaN;
let y = 5;
let z = x + y;         // z will be NaN
```
Or the result might be a concatenation:
```
let x = NaN;
let y = "5";
let z = x + y;         // z will be NaN5
```
`NaN` is a number: `typeof NaN` returns number:
```
typeof NaN;            // returns "number"
```
> How do you increment and decrement a number?

* The increment operator (`++`) increments numbers.
* The decrement operator (`--`) decrements numbers.

> Explain the difference between prefixing and post-fixing increment/decrement operators.

If used postfix, with operator after operand (for example, `x++`), the increment operator increments and returns the value **before** incrementing.
```
let x = 3;
y = x++;

// y = 3
// x = 4
```
If used prefix, with operator before operand (for example, ++x), the increment operator increments and returns the value **after** incrementing.
```
let a = 2;
b = ++a;

// a = 3
// b = 3
```

> What is operator precedence and how is it handled in JS?

Operator precedence describes the order in which operations are performed in an arithmetic expression. This is the same as an arithmetic expression.

> How do you log information to the console?
`console.log()`

> What does unary plus operator do to string representations of integers?

It can convert something into a number. This [page](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Unary_plus) contains some examples.

