# Programming with Javascript

## Control Flow

The *control flow* is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across structures that change the control flow.

Some structures that may affect order of excution:

- Conditionals (if else statements)
- Loops
- Functions

## Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

A JavaScript function is defined with the `function` keyword, followed by a **name**, followed by parentheses **()**.

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas: **(parameter1, parameter2, ...)**

The code to be executed, by the function, is placed inside curly brackets: **{}**

Function **parameters** are listed inside the parentheses () in the function definition.

Function **arguments** are the **values** received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

The code inside the function will execute when "something" **invokes** (calls) the function:

- When an event occurs (when a user clicks a button)
- When it is invoked (called) from JavaScript code
- Automatically (self invoked)

When JavaScript reaches a `return` statement, the function will stop executing.

You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

Functions can be used the same way you use variables.

```javascript
    let x = toCelsius(77);

    let text = "The temperature is " + x + " Celsius";
```

Variables declared within a JavaScript function, become **LOCAL** to the function.

Local variables can only be accessed from within the function.

In JavaScript, parameters of functions default to `undefined`. However, in some situations it might be useful to set a different default parameter.

With default parameters, a manual check in the function body is no longer necessary. You can put 1 as the default value for `b` in the function head:

```javascript
    function multiply(a, b = 1) {

        return a * b;

    }

    multiply(5); // 5
```

## Operators

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

`3 + 4` or `x * y`

A unary operator requires a single operand, either before or after the operator:

`x++` or `++x`

- (+) Addition
- (-) Subtraction
- (*) Multiplication
- (**) Exponentiation (ES2016)
- (/) Division
- (%) Modulus (Division Remainder)
- (++) Increment
- (--) Decrement

An **assignment operator** assigns a value to its left operand based on the value of its right operand:

`x = 5`

Addition assignment: `x += 5` is the same as `x = x + 5`

Subtraction assignment: `x -= 5` is the same as `x = x - 5`

Multiplication assignment: `x *= 5` is the same as `x = x * 5`

Division assignment: `x /= 5` is the same as `x = x / 5`

Remainder assignment: `x %= 5` is the same as `x = x % 5`

A **comparison operator** compares its operands and returns a logical value based on whether the comparison is true.

- (==) equal to
- (===) equal value and equal type
- (!=) not equal
- (!==) not equal value or not equal type
- (>) greater than
- (<) less than
- (>=) greater than or equal to
- (<=) less than or equal to
- (?) ternary operator

**Logical operators** are typically used with Boolean (logical) values; when they are, they return a Boolean value.

- Logical AND (`&&`) - `x == 5 && y == 13`

- Logical OR (`||`) - `x == 5 || y == 13`

- Logical NOT (`!`) - `!5`

`typeof` returns the type of a variable
`instanceof` returns true if an object is an instance of an object type

An **expression** is any valid unit of code that resolves to a value.

`x = y + 5` or `x > 5`

- [Home](README.md)
- [Class 1 Markdown](class1.md)
- [Class 2 The Coder's Computer](class2.md)
- [Class 3 Git & GitHub](class3.md)
- [Class 4 Wireframes and HTML](class4.md)
- [Class 5 CSS](class5.md)
- [Class 6 Javascript Basics](class6.md)
- [Class 7 Programming with Javascript](class7.md)
- [Class 8 Operators and Loops](class8.md)
