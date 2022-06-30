# Programming with Javascript

### Control Flow

The *control flow* is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across structures that change the control flow.

Some structures that may affect order of excution:

- Conditionals (if else statements)
- Loops
- Functions

### Operators

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

`3 + 4` or `x * y`

A unary operator requires a single operand, either before or after the operator:

`x++` or `++x`

An **assignment operator** assigns a value to its left operand based on the value of its right operand:

`x = 5`

Addition assignment: `x += 5` is the same as `x = x + 5`

Subtraction assignment: `x -= 5` is the same as `x = x - 5`

Multiplication assignment: `x *= 5` is the same as `x = x * 5`

Division assignment: `x /= 5` is the same as `x = x / 5`

Remainder assignment: `x %= 5` is the same as `x = x % 5`

A **comparison operator** compares its operands and returns a logical value based on whether the comparison is true.

Equal (`==`) returns `true` if the operands are equal. `3 == var1` or `"3" == var1` or `3 == '3'`

Not equal (`!=`) returns `true` if the operands are not equal. `var1 != 4` or `var2 != "3"`

Strict equal (`===`) returns `true` if the operands are equal and of the same type. `3 === 3`

Strict not equal (`!==`) returns `true` if the operands are of the same type but not equal, or are of different type. `var1 !== "3"` or 
`3 !== '3'`

Greater than (`>`) returns `true` if the left operand is greater than the right operand. `var2 > var1` or `"12" > 2`

Greater than or equal (`>=`) returns `true` if the left operand is greater than or equal to the right operand. `var2 >= var1` or `var1 >= 3`

Less than (`<`)	returns `true` if the left operand is less than the right operand. `var1 < var2`
"2" < 12

Less than or equal (`<=`) returns `true` if the left operand is less than or equal to the right operand. `var1 <= var2` or `var2 <= 5`

**Logical operators** are typically used with Boolean (logical) values; when they are, they return a Boolean value.

- Logical AND (`&&`) - `x == 5 && y == 13`

- Logical OR (`||`) - `x == 5 || y == 13`

- Logical NOT (`!`) - `!5`

An **expression** is any valid unit of code that resolves to a value.

`x = y + 5` or `x > 5`

### Functions

Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value

Functions should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

A function definition (also called a function declaration, or function statement) consists of the `function` keyword, followed by:

- The name of the function
- A list of parameters to the function, enclosed in parentheses and separated by commas.
- The JavaScript statements that define the function, enclosed in curly brackets, `{...}`

```javascript
    function square(number) {

        return number * number;

    }
```

**Calling** the function actually performs the specified actions with the indicated parameters. For example, if you define the function `square`, you could call it as follows:

`square(5);`

The function executes its statements and returns the value `25`.

#### Function scope

Variables defined inside a function cannot be accessed from anywhere outside the function, because the variable is defined only in the scope of the function. However, a function can access all variables and functions defined inside the scope in which it is defined. However, functions can access global variables.

#### Parameters

In JavaScript, parameters of functions default to `undefined`. However, in some situations it might be useful to set a different default **parameter**.

With default parameters, a manual check in the function body is no longer necessary. You can put 1 as the default value for `b` in the function head:

```javascript
    function multiply(a, b = 1) {

        return a * b;

    }

    multiply(5); // 5
```

[Home](README.md)